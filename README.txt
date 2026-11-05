# Jayhind Sweets — Order & Collect (Static Demo)

## Run locally
Open `index.html` in a modern browser. No build tools or server are required.

## Included
- Responsive menu with Sweets and Namkeen filters
- Search, pack-size selection, basket and quantity controls
- Order token (JH-0001, JH-0002...) and random pickup counter (1–5)
- Printable pickup receipt
- Supplied Jayhind logo and historical shop photograph

## Important production limitation
This is a front-end-only static demo. Orders and the sequence number are saved in the browser's localStorage only. They are not transmitted to Jayhind staff, and separate devices/browsers will have separate order sequences. The random counter is assigned in the browser and is not coordinated with live counter capacity. Before using for real customers, connect an API/database and a staff-facing order dashboard; generate order numbers and assign counters on the server.
