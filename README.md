# location-system-api


About the project:


Location-system-api gives the set of nearyby stations, leisure-spots and set of postal codes based on the postal code / station names passed.


API End-points:


-> To get the nearby stations:

    : http://location-system-api.us-e2.cloudhub.io/api/locations/postalCodes
    
    queryParam to be passed: address  (eg: Leeds)
    
-> To get the nearby attraction spots:

     : http://location-system-api.us-e2.cloudhub.io/api/locations/attractionspots
     
    queryParam to be passed: address   (eg: London Waterloo)
    
-> To get the set of postal codes:

     : http://location-system-api.us-e2.cloudhub.io/api/locations/stations
     
    queryParam to be passed: address     (eg: Woking)
