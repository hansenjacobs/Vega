# Vega
Vega is an imaginary car sales company. Sellers can have their vehicle listed for sale with Vega while buyers can use Vega to search for potential purchases.

The application is built using Visual Studio 2017 utilizing ASP.Net Core, Entity Framework Core and Angular. All CRUD operations are completed using RESTFUL APIs.

Requirements
---
### Listing Cars
Cars will be listed by calling Vega, providing relavent information and Vega will list the vehicle in the DB/app.

### Buying Cars
Once a buyer has found a car they are interested in, they will call Vega and the remainder of the transaction will happen 'offline'.

### Vehicle Records
- Make (Chevrolet)
- Model (Volt)
- Model Year (2012)
- Features (ABS Breaks, Airbags, Cup Holders, Plug-in EV, ect)
- Registered?
- Owner (name, phone, email)
- Photos - one or more
##### Features 
* There is a standard list of features
* A vehicle can have multiple features
* Many vehicles can have the same feature(s)

### Pages
#### Vehicle List
This page will list all vehicles. A user will be able to sort & filter. The page should include pagation dividing by 10 vehciles per page.
* There should be a link on each displayed vehicle to view the full details of the vehicle
* There should be a link to Add a Vehicle
#### View Vehicle
This page will display all details of a vehicle.
#### Add Vehicle
This page will allow the user to fill in the form to add a vehicle to the DB

### Roles
#### Moderator
* Add Vehicle
* Update Vehcile
* Delete Vehicle
#### Admin
* View Reports
#### Anonymous
* View Vehicle List
* View Vehicle Details
