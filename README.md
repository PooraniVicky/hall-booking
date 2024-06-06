# Hall-Booking-API-Task

## Back-end Deployed URL:
https://hall-booking-2-53in.onrender.com


## 1. Create Room

Endpoint to create a new room with specified number of seats, amenities, and price per hour

POST-Method
https://hall-booking-2-53in.onrender.com/rooms

        {
            "seats": 3,
            "amenities": ["TV","Doublebed","AC"] ,           
            "pricePerHour": 2500
        }

------------------------------------------------------------------------------------------------------------------

## 2. Book a Room

Endpoint to book a room, checks for availability and creates a booking if available

POST-Method
https://hall-booking-2-53in.onrender.com/bookings

    {
        "customerName": "Poorani",
        "date": "06-04-2024",
        "startTime": "14:00",
        "endTime": "20:00",
        "roomId": 3
    }

----------------------------------------------------------------------------------------------------------------------

## 3. List all rooms with booked data
 
Endpoint to list all rooms along with their booking details

GET - Method
https://hall-booking-2-53in.onrender.com/rooms


-----------------------------------------------------------------------------------------------------------------------

## 4. List all customers with booked data

Endpoint to list all customers along with their booking details

GET - Method
https://hall-booking-2-53in.onrender.com/customers

--------------------------------------------------------------------------------------------------------------------

## 5. List how many times a customer has booked the room

Endpoint to list all bookings made by a specific customer with detailed booking information

GET - Method
https://hall-booking-2-53in.onrender.com/customer/Guest

----------------------------------------------------------------------------------------------------------------------

