# 2T-MDVRP-RS-TW

A repository with instances for the 2T-MDVRP-RS-TW.

These instances are built to emulate the city center of Amsterdam, the Netherlands. In the instances,  both robot stations and customer locations are uniformly distributed with radius of 7.5 [km], mirroring the densely populated landscape of Amsterdam. Conversely, the depots are positioned in the final 1.5 [km] of the radius, being strategically situated on the outskirts of the city. The depots remain within accessible proximity, facilitating seamless transportation of parcels between the urban core and the periphery. Thus, we aim to accurately capture the intricate dynamics of the urban logistics within the densely populated city of Amsterdam. Additionally, we provide a second set of instances, corresponding to a Square city with a significantly larger area. The square instance set reflects realistic urban environments, characterized by clustered distributions of neighborhoods and business districts. To simulate this scenario, we utilized a Gaussian clustering distribution to determine the locations of customer sites and robot stations, while depot locations were randomly allocated. Specifically, three clusters were created for instances with 50 and 100 customers, five clusters for instances with 150 customers, and six clusters for instances with 200 customers. 

The 2T-MDVRP-RS is a generalization of the Uncapacitated Routing-Scheduling Problem (URSP). In the 2T-MDVRP-RS-TW, a fleet of trucks supplies facility locations to dispatch delivery robots that serve customers with their corresponding parcels in the form of round-trips. Therefore, the 2T-MDVRP-RS-TW depicts a two-tier transportation system, focusing on last-mile delivery operations, where autonomous vehicles, such as delivery robots, are involved in the delivery process and together should minimize logistic costs while meeting time windows constraints.

Comments within an instance's file start with /* and end with */ have to be ignored.

This repository contains the instances used for the paper "The Two-Tier Multi-Depot Vehicle Routing Problem with Robot Stations: A Solution Approach for Soft and Hard Time Windows". Campuzano Giovanni, Mes Martijn, & Lalla-Ruiz Eduardo. DOI:

You are kindly requested to cite this paper if these instances are relevant to your research.
