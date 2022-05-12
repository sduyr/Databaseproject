# Databaseproject

The aim of this project is to design and implement a simplified taxicab system (e.g. Uber)to gain an understanding of all the steps involved in using a relational database for a practical application.

Some basic requirements of the system are specified below. You can add to these requirements
or make additional assumptions as needed.
 Vehicles are identified by a vehicle-id. Each vehicle of a specific type: sedan, SUV or
van. A vehicle has a fixed capacity of passengers and luggage.
 Each vehicle is owned by a driver. The SSN identifies the driver, and other related
attributes such as name, gender, DOB, etc. are stored.
 Customers are identified by their email-id. Other attributes of the customer such as
name, gender, DOB, etc. are stored.
 Customers can request a ride and a specific vehicle is assigned to the ride. The source
location name, destination location name, start time of the ride and end time of the
ride is stored. The dollar amount for a ride is also stored.
 Customers can provide feedback for a ride in numerical scores for safety, customer
service, cleanliness, condition of the vehicle and overall satisfaction.
 Vehicles are tracked using GPS. You can assume that there is a derived attribute that
maps GPS coordinates of the vehicle to a specific location name.
 Customers are also tracked using GPS. You can assume that there is a derived attribute
that maps GPS coordinates of the customer to a specific location name.
 A customer may also have one or more coupons that can be applied to a ride. Each
coupon has a fixed discount percentage for the ride.
