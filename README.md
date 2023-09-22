# Epic-Eats
Epic Eats is a user-friendly desktop app made with Python and MongoDB. Customers can select items, and a unique QR code is generated for their order. The admin panel helps manage orders and check the QR code's validity. The system aims to make canteen operations smoother and enhance the user experience for both customers and the canteen staff.

## Demo Video
https://www.youtube.com/watch?v=rz7G4oQP4Oo

## Prerequisites
- Python 


- ### Client
    Customers can use the client application to place new orders, view already ordered orders. Once the order is placed, A QR Code is generated. Customer needs to scan this QR Code with the Canteen's Scanner to get food and final receipt. 

- ### Admin
    The Canteen manager can use this portal to add/remove receipes, update receipes price/quantity, view ordes.
  
- ### Scanner
    This scanner is placed in canteen. It scans the QR codes and gives order bill.

## Features
- It uses token based authentication, so fake QR Codes are identified. 
- The admin has a option to tag any item as special, so its diaplayed under "special items" category for customer.
- The customer has a option to tag a order as take away.
