
Daml Music Store App
Overview
This project was created by using the empty-skeleton template. The project adopts and exemplifies the proposal-accept design pattern. It was designed for a Music Store scenario.
The client can create an OrderProposal contracts & storeAdmin can exercise "checkOrders", "Reject" or "Review". The store when reviewing can accept the order and after that can also update the order with the Shipped status

II. Workflow
- Client creates a OrderProposal contract, the client can also cancel a OrderPoposal
- StoreAdmin can Reject with a reason or Review the orderProposal, the Review choice will create a Order with Status approved 
- StoreAdmin can at any time check the existing order with "CheckOrders"
- StoreAdmin can change the status of the order to shipped one a order approved is shipped


III. Challenge(s)
SDK version is 2.8.5 and the code itself does not cause any issues/errors
The project was created by using empty-skeleton

IV. Compiling & Testing
To compile and test, run the pre-written script in the Test.daml under /daml OR run:

$ daml start