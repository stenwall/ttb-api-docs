|key|example|descripton|
|---|---|---|
|`ScheduledDepartureDateTime`|`2021-11-02 00:00:00`|Tågets trafikdygn. Ingenting som rör appen.|
|`AdvertisedTrainIdent`|`19`|Tågets nummer.|
|`LocationSignature`|`fln`|Stationens signatur.|
|`LocationName`|`Falun central`|Stationens namn.|
|`TrackAtLocation_depature`|`1a`|Spåret tåget avgår från på stationen.*(OBS! Om trafikverket inte har annonserat ut någon avgångstid, så kommer denna key att vara en kopia av `TrackAtLocation_arrival`)*|
|`AdvertisedTimeAtLocation_depature`|`2021-11-02 11:35:00`|Trafikverkets utannonserade/planerade avgångstid från stationen.*(OBS! Om trafikverket inte har annonserat ut någon avgångstid, så kommer denna key att vara en kopia av `AdvertisedTimeAtLocation_arrival`)*|
|`EstimatedTimeAtLocation_ttb_depature`|`2021-11-02 11:35:00`|Trainbrains estimerade avgångstid.*(OBS! Om trafikverket inte har annonserat ut någon avgångstid så kommer denna key att vara en kopia av `EstimatedTimeAtLocation_ttb_arrival`)*|
|`EstimatedTimeAtLocation_depature`|`2021-11-02 11:35:00`|Trafikverkets estimerade avgångstid. *(OBS! Om trafikverket inte har annonserat ut någon estimerad avgångstid så kommer denna key vara satt till `NA`)*|
|`prognostid_depature`|`2021-11-02 11:35:00`|Tiden när Trainbrain gjorde sin prognos för avgång.|
|`ttb_id_depature`|`1f124f8a4e7ecb832105160f14582dab`|Id:t för tågets avgång från stationen i fördelningskurvan.*(OBS! Om trafikverket inte har annonserat ut någon avgångstid så kommer denna key att vara en kopia av `ttb_id_arrival`)*|
|`TrackAtLocation_arrival`|`1a`|Spåret tåget ankommer till på stationen.*(OBS! Om trafikverket inte har annonserat ut någon ankomsttid, så kommer denna key att vara en kopia av `TrackAtLocation_departure`)*|
|`AdvertisedTimeAtLocation_arrival`|`2021-11-02 11:35:00`|Trafikverkets utannonserade/planerade ankomsttid till stationen.*(OBS! Om trafikverket inte har annonserat ut någon ankomsttid, så kommer denna key att vara en kopia av `AdvertisedTimeAtLocation_departure`)*|
|`EstimatedTimeAtLocation_ttb_arrival`|`2021-11-02 11:35:00`|Trainbrains estimerade ankomsttid.*(OBS! Om trafikverket inte har annonserat ut någon ankomsttid, så kommer denna key att vara en kopia av `EstimatedTimeAtLocation_ttb_departure`)*|
|`EstimatedTimeAtLocation_arrival`|`2021-11-02 11:35:00`|Trafikverkets estimerade ankomsttid. *(OBS! Om trafikverket inte har annonserat ut någon estimerad ankomsttid så kommer denna key vara satt till `NA`)*|
|`prognostid_arrival`|`2021-11-02 11:35:00`|Tiden när Trainbrain gjorde sin prognos för ankomst.|
|`ttb_id_arrival`|`1f124f8a4e7ecb832105160f14582dab`|Id:t för tågets ankomst till stationen i fördelningskurvan.*(OBS! Om trafikverket inte har annonserat ut någon ankomststid så kommer denna key att vara en kopia av `ttb_id_departure`)*|
|`depature_exists`|`1`|Om trafikverket har utannonserat en avgångstid, så kommer denna key att vara satt till `1`, annars till `0`.|
|`arrival_exists`|`1`|Om trafikverket har utannonserat en ankomsttid, så kommer denna key att vara satt till `1`, annars till `0`.|
