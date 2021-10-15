# RideShare-Final-Project
Car rideshare 

The scope of the project is to develop a limited rideshare Dapp:

    
    the "Rider":

        1. Register as user of the platform to be able to request rides, the "Rider" => in the Blockchain
        2. Request "Rides" introducing the destination address. The pick-up location shall be collected automatically form a Geolocation service,       and time as current time? => Front-end interface => to the Blockchain
        
    
    the "Driver":
    
        1. Register as user of the platform to be able to create rides, the "Driver" => in the Blockchain
        2. Create rides for specific times-date, from and to locations. => in the Blockchain
                Locations must already exist in the zonesprices table => in the Blockchain
                
        3. Gets automatic notification if a ride is requested from a Rider => in the Blockchain
        4. Accepts or Rejects ride requests. => in the Blockchain //Internally... validate time of ride... Inactive a ride if time past... 
        
     
    the "Rider":
        1. Pay for the ride when ride is finished => in the Blockchain
        
        
NOTES: 

-Rider must loop through available rides with the options to select rides available by price and distance?
-Cancel a ride? Driver created ride and Rider requested ride...
        
        
