# UPTDNet_dataset
This is the Gowalla and Foursquare check-in dataset used in our paper "UPTDNet: A user preference transfer and drift network for cross-city next POI recommendation".

## Gowalla dataset
The Gowalla dataset is downloaded from http://www.yongliu.org/datasets/ .
We extract the check-in records in two cross-city pairs, including Dallas-Austin and LosAngeles-SanFrancisco. 

File Gowalla_Dallas_Austin.csv and Gowalla_LosAngeles_SanFrancisco.csv contain check-ins with 7 columns, which are:
1. userid (anonymized)
2. placeid (ID of check-in POI)
3. datetime (UTC time)
4. lng (longitude of check-in POI)
5. lat (latitude of check-in POI)
6. spot_categ (category of check-in POI)
7. cross_city_mode ("A_B" stands for user from city A in city B)

## Foursquare dataset
The Foursquare dataset is the Global-scale Check-in Dataset with User Social Networks downloaded from https://sites.google.com/site/yangdingqi/home/foursquare-dataset .
We extract the check-in records in cross-city pair Washington-Baltimore. 

File Foursquare_Washington_Baltimore.csv contains check-ins with 8 columns, which are:
1. userid (anonymized)
2. placeid (ID of check-in POI)
3. time (UTC time)
4. timeoffset (the offset in minutes between when this check-in occurred and the same time in UTC, i.e., UTC time + offset is the local time)
5. lng (longitude of check-in POI)
6. lat (latitude of check-in POI)
7. spot_categ (category of check-in POI)
8. cross_city_mode ("A_B" stands for user from city A in city B)
