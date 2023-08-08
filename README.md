# CricketStoreMicroservice


## Architecture Diagram

![Diagram](/SolutionItems/architecture.drawio.svg)


MS | API  |  Method  | Path  |
|:-----|:-----|:--------:|------:|
| **Product** | Get by id | GET | /{id}
| **Product** | Get all | GET | /
| **Product** | Create product | POST | /
| **Product** | Delete by id | DELETE | /{id}
| **Product** | Update by id | PUT | /{id}


MS | API  |  Method  | Path  |
|:-----|:-----|:--------:|------:|
| **Basket** | Get by id | GET | /{id}
| **Basket** | Get all | GET | /
| **Basket** | add item to basket | POST | /
| **Basket** | Delete by id | DELETE | /{id}
| **Basket** | Update by id | PUT | /{id}


MS | API  |  Method  | Path  |
|:-----|:-----|:--------:|------:|
| **User** | Get by id | GET | /{id}
| **User** | Get all | GET | /
| **User** | Create user | POST | /
| **User** | Delete by id | DELETE | /{id}
| **User** | Update by id | PUT | /{id}

MS | API  |  Method  | Path  |
|:-----|:-----|:--------:|------:|
| **Order** | Get by id | GET | /{id}
| **Order** | Get all | GET | /
| **Order** | create order | POST | /
| **Order** | Delete by id | DELETE | /{id}
| **Order** | Update by id | PUT | /{id}

MS | API  |  Method  | Path  |
|:-----|:-----|:--------:|------:|
| **Notification** | Send notification | POST | /
