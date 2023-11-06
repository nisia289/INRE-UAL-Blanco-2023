@startuml
left to right direction
actor "Manager" as Manager
actor "Commercial" as Commercial
actor "Administrator" as Administrator
actor "Customers" as Customers

rectangle "Hotel Reservation System" {
  usecase "Consult Reservations" as ConsultReservations
  usecase "Make Offers" as MakeOffers
  usecase "Manage New Reservations" as ManageReservations
  usecase "Manage New Requests" as ManageRequests
  usecase "Recalculate Prices" as RecalculatePrices
  usecase "Temporary Block Reservation" as TemporaryBlock
  usecase "Check Availability" as CheckAvailability
  usecase "View Offers" as ViewOffers
  usecase "Search Elements" as SearchElements
  usecase "Display Calendar" as DisplayCalendar

  Manager --> ConsultReservations 
  Commercial --> ConsultReservations 
  Commercial --> MakeOffers 
  Commercial --> ManageReservations
  Commercial --> CheckAvailability
  Administrator --> ManageReservations
  Administrator --> MakeOffers 
  Administrator --> ManageRequests
  Commercial -> RecalculatePrices
  Commercial --> TemporaryBlock
  Customers --> CheckAvailability
  Administrator --> CheckAvailability
  Administrator --> ViewOffers
  Commercial --> ViewOffers
  Customers --> ViewOffers
  SearchElements --> CheckAvailability
  SearchElements --> ViewOffers
  CheckAvailability --> DisplayCalendar
  MakeOffers --o TemporaryBlock
  MakeOffers ..> RecalculatePrices
}
@enduml

'Assumptions:

'The manager and the commercial can consult reservations.
'The commercial makes offers and manages new reservations.
'The administrator manages new requests and also makes offers.
'Making offers by the commercial involves a recalculation of prices and optionally the temporary blocking of a reservation.
'Customers, administrators, and commercial staff can check availability and view offers.
'The consultation of availabilities and booking queries have the common functionality of searching elements.
'The availability query entails a functionality that displays a calendar.
