# introsde2017-finalproject
User preferences based on artists and artist events
API REFERENCE: https://kamauz.docs.apiary.io/#reference

![alt text](https://github.com/introsde-kamauz/introsde2017-finalproject/blob/master/Project%20Scheme.png?raw=true)

This application has been developed to improve the iteraction between citizen and their favorite artists. It can be used to work as a comunication bridge and to constantly inform the users for new events or new artists that could interesting.

# Architecture

- Process Centric: service that handle the entire process
- Recommendation Business Logic: service that contain complex operations that can be implemented in the process centric
- Experience Adapter & Resource Adapter: services that group more resources and provide minimal functions to be handled in the business logic
- Meteo Adapter & Maps Adapter: services that interface with the external libraries and provide simple functions




