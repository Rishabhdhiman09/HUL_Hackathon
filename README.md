# HUL_Hackathon

Problem Statement:

i. Distributor plan their deliveries based on the orders from the retailers. Most of the delivery vehicles have a combination of Sales Beat based in their deliveries. There is no optimisers to decide on the fact that if the vehicles are running overload or underload or optimising the kms

ii. Group of shaktis are covered by separate salesman and doesn’t cover the GT outlets (retailers). As shaktis are in interior rural, so throughput of shaktis are not good, there is always a problem with ensuring delivery for the orders. There should be mushroom model wherein the deliveries of shaktis should be combined with the delivery of GTs routes

Requirements:

i. Do a dynamic routing to each of the distributors to retailers. Once the distributor gets the order for the day how best he can fulfil those order given his delivery fleet (savings in kms and loading) for Metros and Tier-1 cities ii. Sales beat optimisation: District to be mapped out the Shaktis, Distributors and GT markets. Output required is which shaktis to be marked to which distributor and which Shakti to be mapped to which salesman so that the delivery in combination to the sales beat Requirements: Change management w.r.t behavioural change: Delivery person might get a different route at given days which is not the case in the existing scenario wherein the delivery person are set for set retailers. So, the solution is to distribute it into multiple zone (static cluster in dynamic modelling)

Objective of Algorithm:

To minimize the delivery distance (route optimization)
To deliver goods to shaktis without vehicle underloading
