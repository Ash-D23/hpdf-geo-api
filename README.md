# hpdf-geo-api

This API does the following :
1.Generates the distance matrix from the origin and destination address
2.Generates the lat,lng for the particular address
3.Generates the address from the lat and lng values

The input are passed through the url and output is of the form of json

To execute the file Clone the project and follow the steps :
1.Install the modules by typing 'npm install' in the command prompt 
2.Type the following in the url and see the results :
    http://localhost:3000/api/address?origin={origin address}&destination={destination address}
    http://localhost:3000/api/location/{location}
    http://localhost:3000/api/coordinates?lat={latitude}&long={longitude}
    
Replace {} with the inputs you want and note to replace the API key inside server.js with your own key
