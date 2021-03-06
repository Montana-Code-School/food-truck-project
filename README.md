# Truck Yeah!
## V 0.5
###### Live Demo: https://truck-yeah.herokuapp.com/

*Truck Yeah* is a mobile-responsive web application designed to connect food truck owners with hungry customers. 

Trucks are entered into a central database, along with information regarding their operating hours, common locations and details on the food they serve.

*Truck Yeah* automatically generates truck profiles based upon this information, and serves it up to customers by category - i.e., 'Open Now,' 'Lunch,' or 'Dinner.'

The *Truck Yeah* stack is composed of (back-to-front):
- MongoDB
- Node / Express
- ReactJS (JSX)
- Limited EJS
- Webpack (browser compiling)

Also notable are the inclusion of:
- Passport (user authentication)
- Google Maps Javascript API


![Imgur](http://i.imgur.com/goWTTXw.png)
![Imgur](http://i.imgur.com/fF6cUvo.png)
![Imgur](http://i.imgur.com/RIVwJ8E.png)
![Imgur](http://i.imgur.com/1KJ7ACb.png)



###VERSION MAP: 

##### V 1.0 - 
- Mobile-Native port to iOS / Android.

  ![Imgur](http://i.imgur.com/dU3aQLM.png)
  ![Imgur](http://i.imgur.com/NEUiAZG.jpg)

- Truck owners' tooling / dashboard. 
  - Edit profiles.
  - Output current location via iOS / Android location services.
  - Blast current location to Social Media.
  
- Location recognition for consumers.
  - Generate directions to individual trucks.
  - Populate trucks within user radius (ex. 25mi / 50mi)
  
- Search for trucks in a different city.

##### V 2.0
- Admin-free truck entry.
  - Crowd-sourced / 'Claim your page'?
  - Ownership auth with Twitter?

- Customer login auth with Facebook. 
  - 'Favorite' the trucks you really like, and get push notifications when they're close to you.
  - Send out a food request - if enough people in one area 'ping,' a truck might decide to show up!
  
- Truck owners' analytics //  *FREEMIUM FEATURE*

##### V 3.0
- In-App ordering / Payment via Stripe // *FREEMIUM FEATURE*
  
