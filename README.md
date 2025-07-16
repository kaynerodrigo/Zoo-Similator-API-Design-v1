| Resource | HTTP Method | Full URL Resource | Use Case Representation |
|---|---|---|---|
| Zoos (Viewed) | GET | /zoos | Visitor list all zoos |
| Tickets | GET | /zoos/{zooId}/tickets | Ticket vendor of the zoo shows the ticket list |
| Visitor (Purchase) | POST | /zoos/{zooId}/tickets/purchases | Visitor purchases a ticket |
| Tickets (Verify) | POST | /zoos/{zooId}/tickets/{ticketId}/verifies | Ticket vendor verifies a ticket (adds a stamp) |
| Visitors | POST | /zoos/{zooId}/visitors | Visitor get registered (receives a wristband) |
| Visitors (Viewed) | GET | /zoos/{zooId}/visitors/{visitorId} | Visitor gets details of a visitor |
| Animals (Viewed) | GET | /zoos/{zooId}/animals | Visitor list all animals of the zoo |
| Animals (Viewed) | GET | /zoos/{zooId}/animals/{animalId} | Visitor gets details of an animal |
| Tickets (Purchase) | GET | /zoos/{zooId}/tickets/{ticketId}/purchases | Visitor gets details of a purchased ticket |
| Tickets (Verify) | GET | /zoos/{zooId}/tickets/{ticketId}/verifies | Ticket vendor gets details of a verified ticket |
| Animals (Update) | PUT | /zoos/{zooId}/animals/{animalId} | Zookeeper updates details of an animal |
| Animals (Delete) | DELETE | /zoos/{zooId}/animals/{animalId} | Zookeeper deletes an animal |
| Animals (Add) | POST | /zoos/{zooId}/animals | Zookeeper adds an animal |
