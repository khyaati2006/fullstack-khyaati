# Concurrent Ticket Booking System (Redis Lock)

## Aim
To create a concurrent ticket booking system with seat locking using Redis.

## Technologies
- Node.js
- Express.js
- Redis
- Artillery (load testing)

## Run

npm install
npm start

API:
POST /api/book

Example JSON:

{
 "seatId": "A1",
 "user": "John"
}
