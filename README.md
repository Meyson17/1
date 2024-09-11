
![PP1FIiD05CRtSuf7zrtOFrifU0OF4AQJ6eW99DEL2D4iBHJSg-09qjXesjHuXU_To9auC1G9ONu3l-zxmrlaEiZq-ZOMiGerwPIoQ7MZQHbbIkeeJKGWTPhH26_eqV46N-QiKV4Z6diVKP1JA8NLWsGLAy8x5sYm-_FmZPQtT2U8rhcIGQveX1TKE9Y6bWpK1dgSp7_0aSkXyFhguYp](https://github.com/user-attachments/assets/c6b96e75-4a85-4a1b-a8bc-4d7a5932ad1a)

<code>
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
<code>
