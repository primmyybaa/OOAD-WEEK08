# OOAD-WEEK08

## Use Case Diagram 

### Use Case Diagram 1
code 
```
@startuml
User --> (Use Website) 
:Admin Website: ---> (Use Website) 
:Admin Website: -->(Create Website)
@enduml
```
diagram 
<img src = "https://github.com/primmyybaa/OOAD-WEEK08/blob/master/Homework/usecase1.png?raw=true">

### Use Case Diagram 2
code
```
@startuml
:user: -left-> (Comment) 
:user: -right-> (press Like) 
:user: -up-> (share post) 
:user: -down-> (post somethings)
@enduml
```
diagram
<img src = "https://github.com/primmyybaa/OOAD-WEEK08/blob/master/Homework/usecase2.png?raw=true">

### Use Case Diagram 3
code
```
@startuml
title Simple <b>Usecase</b> of facebook
"Use facebook" as (Use) 
User -> (Use)
@enduml
```
diagram
<img src = "https://github.com/primmyybaa/OOAD-WEEK08/blob/master/Homework/usecase3.png?raw=true" >

### Use Case Diagram 4
code
```@startuml
:user: -left-> (Comment) 
:user: -right-> (press Like) 
:user: -up-> (share post) 
:user: -down-> (post somethings)
note left of (Comment) : This is one action \n that you can do \n on facebook
note right of (press Like) : You can Do this \n when you like some post

@enduml
```
diagram
<img src = "https://github.com/primmyybaa/OOAD-WEEK08/blob/master/Homework/usecase4.png?raw=true">
### Use Case Diagram 5
code
```@startuml
left to right direction
skinparam packageStyle rect
actor User
actor Admin
rectangle login {
User -- (sign on)
(sign on) -- Admin
(allow new user) -- (Admin) 
User -- (accept agreement)
}
@enduml
```
diagram
<img src = "https://github.com/primmyybaa/OOAD-WEEK08/blob/master/Homework/usecase5.png?raw=true">


