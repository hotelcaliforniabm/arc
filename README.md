# Arc
A nifty way to build modular off grid solar power systems.

![alt text](https://github.com/hotelcaliforniabm/arc/blob/master/arc_v2_exterior.jpg "Arc v2 exterior")

## Overview
This system was primarily designed to provide 30kwh of daily capacity for our Burning Man camp. It provides 25.6vdc electricity because we have found that to be best compromise in terms of energy efficency and appliance requirements.

Given that it is not a super common standart (vs. 110-220vac) we also started to design custom appliances that benefit from it by being oders of magnitude more efficent than off the shelf solutions.

### Appliance types we run:
* Lights (24vdc LED fixtures)
* PA System (we currentely run a custom 2kw RMS PA and are planning to expand to 6kw this year)
* Fridges (there is a bunch of 24v fridges available on the market)
* Water pumps (there is a bunch of 24v fridges available on the market)
* Various low voltage (5-12vdc) appliances such as DMX controllers, wifi access points, ipads, etc. (those can easily be fed by using step down voltage converters)

## System Architecture
The system is designed to consist of multiple independend units which allows for simpler deployment across the perimeter, reduced complexity and higher redundancy.

We run 7x Arcs for our camp at this time. Each one of them has 2,560kwh storage capacity for a total of 17,920kwh. Each is charged by two 350w solar panels.

# Arc components
On a high level each arc consists of the following components:
* Battery
* Battery management controller
* Housing with outlets

![alt text](https://github.com/hotelcaliforniabm/arc/blob/master/arc_v2_bmc.jpg "Arc v2 battery management controller")

## Todo's
Easy status monitoring
Easy to track down and fix issues
Maximize hardware utilization
Easy & cheap to build
Mass manufacturable
Inter arc load balancing

## Thanks
Mark Omerod for starting this project in 2015
Kuy Mainwaring for being part of the brain trust around this over the years
Drew Moxon for really being the man enabling me and my silly ideas
All the amazing souls at Hotel California for making this happen

## License
Copyright (c) 2017-2019 Matthias Wagner

## Safety Disclaimer
This project and the material covered is for informational purposes only. We take no responsibility for what you do with this knowledge. We can not be held responsible for any property or medical damages caused by items you read about here. We would advise you to check your local laws. Some of the items we refer to are illegal in some areas, and we would highly advise you against building these in said areas.

The material is for informational purposes only. By taking any information or education material, you assume all risks for the material covered. You agree to indemnify, hold harmless, and defend this project from any and all claims and damages as a result of any and all of the information covered.

By taking and/or using any informational resources from this project, you agree that you will use this information in a safe and legal manner, consistent with all applicable laws, safety rules, and good common sense. You further agree that you will take such steps as may be reasonably necessary or required by applicable law to keep any information out of the hands of minors and untrained and/ or immature individuals.
