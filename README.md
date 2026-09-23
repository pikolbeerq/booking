# Dink-Ally Sports Center Court Booking v3

GitHub-ready mobile booking prototype exclusive to Dink-Ally Sports Center.

## Booking rules
- Customer chooses a date.
- Court hours: 8:00 AM through 5:00 AM the following day.
- Rate: PHP 300 per hour.
- Customer can select 1 to 8 hourly slots.
- Proceed to Payment shows the selected hours and total.
- In this prototype, the payment screen uses a **Simulate Successful Payment** button.
- After simulated successful payment, selected slots are marked Reserved.

## Important before production
This version stores bookings in the browser only. For real multi-device reservations and real payment confirmation, connect Firebase (or another shared backend) plus a payment gateway/webhook. Reservation locking should be done server-side to prevent double booking.
