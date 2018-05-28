# Vehicles

Vehicles are the foundation of a transportation service, and hence Mobility as a Service. There are many types of vehicles that are managed by a Transportation Service Provider \(TSP\), such as bus, tram, train, taxi, ferry, and rental cars. A TSP may have a fleet of many vehicles of different types, schedules, routes, etc.

Mobility as a Service operators need to know what types of vehicles are available, their locations, and other details in order to extend the TSP service offering to new customer segments.

## Vehicle types

A TSP should make available a list of vehicle types, such as [car classifications](https://en.wikipedia.org/wiki/Car_classification), that are part of their fleet. This can consist of standardized classifications for vehicles as well as additional metadata about vehicle characteristics \(e.g. wi-fi onboard, A/C, emissions per kilometer\).

## Vehicle locations

People are increasingly coming to expect real-time updates about transportation vehicle locations. This provides situational awareness about timing and delays, while building confidence and trust in the transportation provider.

Vehicle location information consists primarily of periodic updates about the vehicle's [geographic coordinates](https://en.wikipedia.org/wiki/Geographic_coordinate_system) \(latitude and longetude\), direction, and movement. This information can be made available via a 'streaming' API, which pushes vehicle locations to all subscribers on an interval.

## Vehicle actions

When designing a **Vehicle API**, at least some of the following actions are important to MaaS providers:

* _get_ available vehicles
  * by type
  * by location
  * by availability

## Further reading

* [ACRISS Car Classification Codes](https://en.wikipedia.org/wiki/ACRISS_Car_Classification_Code)



