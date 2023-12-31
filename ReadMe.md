# MoonQuake

## SUMMARY
When they explored the Moon, NASA’s Apollo astronauts left behind several instruments to collect geophysical data near each Apollo landing site. Your challenge is to develop an app for the public that plots the seismic data these instruments transmitted back to Earth on an interactive 3-D digital moon globe.

## BACKGROUND
Astronauts left several Passive Seismic Experiments (PSE) on the lunar surface during the Apollo missions. These instruments were designed to monitor the environment of each Apollo landing site for at least a year after the astronauts departed. Two different types of PSE packages were set up: Apollo 11 astronauts deployed Early Apollo Surface Experiments Package (EASEP) units pictured in Figure 1 below, and astronauts on the Apollo 12, 14, 15, and 16 missions deployed the more advanced Apollo Lunar Surface Experiments Package (ALSEP) units shown in Figure 2. The seismometers on these devices detected moonquakes, impacts from meteorites, and impacts of man-made origin (also known as artificial impacts), and transmitted the data to Earth where it is still available for use today. Newly updated lunar seismic data curated in NASA’s Planetary Data System is available that includes date, time, latitude, longitude, magnitude, and depth, along with data descriptions and software to help users read the data. Numerous moonquakes occur during sunset and sunrise when the lunar surface temperature changes rapidly on either side of the day/night terminator line. Many of those moonquakes even occur on mapped fault lines.

[Challenge](https://www.spaceappschallenge.org/2023/challenges/make-a-moonquake-map-20/)

#### Tech  

[ThreeJs]([https://threejs.org/](https://threejs.org/))  
[Fundamental]([https://threejs.org/manual/#en/fundamentals](https://threejs.org/manual/#en/fundamentals))


#### Run

To run locally : 
```npx vite```


#### Ressources

https://svs.gsfc.nasa.gov/4720
https://pds-geosciences.wustl.edu/missions/lro/

[NASA Apollo 11 Passive Seismic Experiment (part of EASEP package)](https://moon.nasa.gov/resources/13/apollo-11-seismic-experiment/)
https://www.hq.nasa.gov/alsj/HamishALSEP.html
https://svs.gsfc.nasa.gov/cgi-bin/details.cgi?aid=4720
https://ntrs.nasa.gov/api/citations/20200001816/downloads/20200001816.pdf
https://nssdc.gsfc.nasa.gov/misc/documents/b53211.pdf
https://pds-geosciences.wustl.edu/missions/apollo/seismic_event_catalog.html
https://pds-geosciences.wustl.edu/missions/apollo/apollo_pse.htm

- [Module Python Séismologie](https://docs.obspy.org/)
- [yoshio Nakamura](https://scholar.google.com/citations?user=WJybDq8AAAAJ&hl=en)
- [Planetary Data System](https://pds-geosciences.wustl.edu/missions/apollo/apollo_pse.htm)
- [README for pds](https://pds-geosciences.wustl.edu/lunar/urn-nasa-pds-apollo_pse/readme.txt)
- [Github Plannetary Data](https://github.com/cerinunn/pdart/blob/master/getting_started.ipynb)

Le Proj de l'an dernier : https://2022.spaceappschallenge.org/challenges/2022-challenges/moonquake-map/teams/selene-5/project


CSA Challenges: Space Apps Challenge | Canadian Space Agency (asc-csa.gc.ca)

NASA Global Offers (hosting, cloud services, etc..): NASA Space Apps Challenge

Global Space Apps discussion platform: https://github.com/nasa/spaceapps


CSA Open Data Portal: Open data and information Portal (asc-csa.gc.ca)

Government of Canada Open Data: Open Government | Open Government, Government of Canada

CSA Open Data/Code landing page: Open data and information | Canadian Space Agency (asc-csa.gc.ca)

EODMS (Canadian synthetic aperture radar data, free login required for most things): https://www.eodms-sgdot.nrcan-rncan.gc.ca/index-en.html

RADARSAT-1 Data on AWS: RADARSAT-1 - Registry of Open Data on AWS

Canadian Astronomy Data Centre (CADC): https://www.cadc-ccda.hia-iha.nrc-cnrc.gc.ca/en/

CSA open code (including code and non-code data tutorials): Agence spatiale canadienne - Canadian Space Agency - GitHub

#### Ideas/ToDo  

- Display  
- [x] sphere  
- [ ] point on a sphere  
- [ ] point inside a sphere  
- [x] skin on the sphere  
- Interactions  
- [x] Rotation  
- [ ] click on sphere / point  
- [ ] transparence  
- animations  
- [ ] ondes  
- [ ] lignes  
- [ ] couleur ?  
- séisme  
- interface  
- pseudo real-time ?

#### Des exemples stylé  
[https://eyes.nasa.gov/apps/mars2020/#/home](https://eyes.nasa.gov/apps/mars2020/#/home)
[https://www.instagram.com/reel/Cx_BlJxukuk/?igshid=MzRlODBiNWFlZA==](https://www.instagram.com/reel/Cx_BlJxukuk/?igshid=MzRlODBiNWFlZA==)
[https://trek.nasa.gov/moon/](https://trek.nasa.gov/moon/)