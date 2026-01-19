@startuml Хостел  
left to right direction  
  
package "Система управления хостелом" {  
  usecase (просматривает свободные комнаты) as ViewRooms  
  usecase (бронирует комнату) as BookRoom  
  usecase (оплачивает проживание) as PayStay  
  usecase (заселяется в комнату) as CheckIn  
  usecase (выселяется из комнаты) as CheckOut  
  usecase (оставляет отзыв) as LeaveReview  
    
  usecase (регистрирует гостя) as RegisterGuest  
  usecase (выдает ключи) as GiveKeys  
  usecase (принимает оплату) as AcceptPayment  
  usecase (управляет бронированиями) as ManageBookings  
  usecase (формирует отчеты) as GenerateReports  
    
  usecase (убирает комнаты) as CleanRooms  
  usecase (сообщает о проблемах) as ReportIssues  
    
  usecase (настраивает систему) as ConfigureSystem  
  usecase (управляет персоналом) as ManageStaff  
  usecase (просматривает статистику) as ViewStatistics  
}  
  
actor Гость as Guest  
Guest --> ViewRooms  
Guest --> BookRoom  
Guest --> PayStay  
Guest --> CheckIn  
Guest --> CheckOut  
Guest --> LeaveReview  
  
actor Администратор as Admin  
Admin --> RegisterGuest  
Admin --> GiveKeys  
Admin --> AcceptPayment  
Admin --> ManageBookings  
Admin --> GenerateReports  
  
actor Горничная as Cleaner  
Cleaner --> CleanRooms  
Cleaner --> ReportIssues  
  
actor Менеджер as Manager  
Manager --> ConfigureSystem  
Manager --> ManageStaff  
Manager --> ViewStatistics  
Manager --> GenerateReports  
  
@enduml  
