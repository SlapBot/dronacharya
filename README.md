# Dronacharya

Drone and UAV traffic management system to address detection of drones and UAVs, unlawful trespassing by drones, collision avoidance, route monitoring and much more.

Live at: [dronacharya.slapbot.me](http://dronacharya.slapbot.me)
## Whats it about?

- Prototyped in [MoveHack](http://pib.gov.in/newsite/PrintRelease.aspx?relid=181379) - Was selected as top 10 overall solutions across all challenge themes among [7,500 individuals and 3,000 teams](https://www.thehindubusinessline.com/info-tech/7500-individuals-register-for-movehack-niti-aayogs-global-mobility-hackathon/article24736986.ece) that globally competed for Hackathon.

- Won the cash prize of ₹10,00,000 and received an invitation to attend the [Global Mobility Summit 2018](http://movesummit.in/about.php) at Vigyan Bhawan, Delhi by NITI AAYOG to meet major CEOs across automobiles, aviation, mobility organisations and receive the award by Prime Minister of India, Narendra Modi.

- [Detecting Drones](https://github.com/slapbot/drone-detection) Using Fast R-CNN of resnet50 model trained with publically available images, [Smart-contract](https://github.com/slapbot/SmartFlightContract) based Flight plan approval subject to risk factors (evaluated programmatically), Multiple entities (DGCA, city/state governments) will digitally sign the approval and publish on a permissioned blockchain. (indium.network), Shows all drones and geofences on [satellite map](http://dronacharya.slapbot.me/dashboard/monitoring), In case of violation, alerts both the operator and authorities.

## Links

- [Drone-Detection](https://github.com/slapbot/drone-detection): A deep learning neural net model to detect drone/drones from a given picture using Using Fast R-CNN architecture via Keras-Retinanet Implementation. (Dataset and Pre-Trained model provided)

- [Drone-Monitoring](https://github.com/slapbot/drone-monitoring): Using D3.js and Mapbox API, a dashboard was built to demonstrate how a drone can be monitored through a web interface and various alerts, emergency operations can be executed on the fly.

- [Smart Flight Contract](https://github.com/slapbot/SmartFlightContract): Smart-contract based Flight plan approval subject to risk factors (evaluated programmatically) - Multiple entities (DGCA, city/state governments) will digitally sign the approval and publish on a permissioned blockchain. (indium.network)



## Global Mobility Summit

NITI Aayog launched MoveHack a global mobility hackathon to crowdsource solutions aimed at the future of mobility in India.

Envisaged to be one of the largest hackathons globally, Move Hack is focused on 10 themes and structured over three legs: online, followed by Singapore leg, and the finals in New Delhi.
<hr>

#### Drone and UAV Traffic Management
Dronacharya was submitted as a solution to cater the needs of UAV Management from the air traffic control to detection and reporting of illegal flights.

#### Process
Solution involved practices like Machine Learning to tackle the issue of detection, MQTT to stream the real time data for accurate geolocation of a given drone, Blockchain network to create an approval pipeline with publically readable scope for anyone with a smartphone can check for geofence violations, And many more
