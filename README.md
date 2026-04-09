Smart Parking Management System (Comic-Con Event)

A relational database schema designed for a large-scale event parking system (such as Comic-Con India), where thousands of vehicles are managed across multiple zones, levels, and reserved categories.
This system supports vehicle tracking, parking allocation, session management, ticketing, and payment processing in a structured and scalable way.


 Features
* Vehicle entry and exit tracking
* Vehicle type classification (bike, car, SUV, EV, etc.)
* Structured parking with zones and levels
* Smart parking spot allocation based on vehicle type
* Reserved parking categories (VIP, staff, exhibitors, EV charging)
* Ticket generation at entry
* Parking session tracking (entry → exit lifecycle)
* Payment handling with status tracking
* Real-time parking availability monitoring


Relationships

One Vehicle_Type → Many Vehicles

One Vehicle → Many Parking Sessions

One Parking_Zone → Many Parking Levels

One Parking_Level → Many Parking Spots

One Vehicle_Type → Many Parking Spots

One Access_Category → Many Parking Spots

One Parking Ticket → One Parking Session

One Parking Spot → Many Parking Sessions

One Access_Category → Many Parking Sessions

One Parking Session → Many Payments
