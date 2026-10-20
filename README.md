# Farmers Market Database

12-table MySQL database for managing farmers market vendors, permits, stall bookings, inspections, attendance, and sales.

What's in it:
- ER diagram and 12 linked tables
- Triggers, like one that blocks stall bookings when a vendor's permit has expired
- A stored procedure that registers a new vendor, books their stall, and schedules an inspection in one step
- Queries for reports like top vendors and average sales per market day
