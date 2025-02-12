# DevMate
# auth router

POST /login
POST /signup
POST /logout
![Image](https://github.com/user-attachments/assets/6ee4194b-730b-4208-8ad9-94dfcde5c283)

# profile router

GET /profile/view
PATCH /profile/edit
PATCH /profile/password

![Image](https://github.com/user-attachments/assets/dfd6eba0-f134-46ff-bf25-0ccb5ed1f7a0)

# connection router

POST /request/send/:status/:userId     -> ignoring (left swipe) / sending (right swipe) connection request 
POST /request/view/:status/:requestId  -> accepting/rejecting the connection request received from other users

![Image](https://github.com/user-attachments/assets/aa5f02a3-b25b-4c2f-8198-db9922cf3310)

# user router
GET /user/connection
GET /user/requests/received
GET /user/feed


*status :  [ ACCEPTED, REJECTED, PASS, LIKE ]




# features to consider adding later

1) chat
2) add forgot password feature
