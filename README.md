@startuml
left to right direction
actor "Пользователь" as fc
rectangle Требования {
  usecase "Найти автомойку" as UC1
  usecase "Выбрать дату и время" as UC2
  usecase "Оплатить" as UC3
  usecase "Выбор услуг" as UC4
  usecase "Поддержка" as UC5
}
fc --> UC1
fc --> UC2
fc --> UC3
fc --> UC4
fc --> UC5
@enduml
