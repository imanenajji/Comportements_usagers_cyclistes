# Comportements_usagers_cyclistes

Test technique python


Données mises à disposition : 
Vous trouverez dans le dossier zippé « date_bike_sharing.zip » une base de données du site Metro Bike Share qui est un fournisseur de systèmes de vélos en libre-service, comme le vélib’, et qui se site en Californie aux Etats-Unis. Le fichier s’appelle final-bike-sharing-2017-2020.csv.

Objectif :
Vous êtes Metro Bike Share, et vous voulez comprendre le comportement usager des cyclistes pour ainsi améliorer le service apporté.

Consigne :
Vous avez libre choix sur les graphiques que vous trouverez pertinents à fournir pour atteindre l’objectif.
Dans un notebook, vous devez fournir le code, les graphiques et vos interprétations. La qualité du code, son optimisation et sa docstring seront pris en compte. 


Data Format
Each .csv file contains data for one quarter of the year. Each file contains the following data points:
•	trip_id: Locally unique integer that identifies the trip
•	duration: Length of trip in minutes
•	start_time: The date/time when the trip began, presented in ISO 8601 format in local time
•	end_time: The date/time when the trip ended, presented in ISO 8601 format in local time
•	start_station: The station ID where the trip originated (for station name and more information on each station see the Station Table)
•	start_lat: The latitude of the station where the trip originated
•	start_lon: The longitude of the station where the trip originated
•	end_station: The station ID where the trip terminated (for station name and more information on each station see the Station Table)
•	end_lat: The latitude of the station where the trip terminated
•	end_lon: The longitude of the station where the trip terminated
•	bike_id:  Locally unique integer that identifies the bike
•	plan_duration: The number of days that the plan the passholder is using entitles them to ride; 0 is used for a single ride plan (Walk-up)
•	trip_route_category: "Round Trip" for trips starting and ending at the same station or "One Way" for all other trips
•	passholder_type: The name of the passholder's plan
•	bike_type: The kind of bike used on the trip, including standard pedal-powered bikes, electric assist bikes, or smart bikes.
Data Processing
Data will be cleansed prior to publication according to the following criteria:
•	Staff servicing and test trips are removed.
•	Trips below 1 minute are removed.
•	A "Virtual Station" listed in the checkout and return kiosks, is used by staff to check in or check out a bike remotely for a special event or in a situation in which a bike could not otherwise be checked in or out to a station.
•	Trip lengths are capped at 24 hours.
•	Some short round trips or long trips may be the result of system or user error, but have been kept in the dataset for completeness.
Station Information
•	Station Table (Updated 2024-07-01)
Data Format
•	Station ID: Unique integer that identifies the station (this is the same ID used in the Trips and Station Status data)
•	Station Name: The public name of the station. "Virtual Station" is used by staff to check in or check out a bike remotely for a special event or in a situation in which a bike could not otherwise be checked in or out to a station.
•	Go live date: The date that the station was first available
•	Region: The municipality or area where a station is located, includes DTLA (Downtown LA), Pasadena, Port of LA, Venice
•	Status: "Active" for stations available or "Inactive" for stations that are not available as of the latest update
Station Status
Live station location and status information is available in the following formats:
•	GeoJSON
•	GBFS


https://bikeshare.metro.net/about/data/

![image](https://github.com/user-attachments/assets/4078be07-9ee7-4375-be83-4da0d7421c52)
