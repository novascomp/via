# Pseudonymization app
Uploaded to hosting on Thursday 22. 12. 2022
https://via.novascomp.synology.me/

The purpose of this application is to pseudonymize certain columns in a test dataframe. 
The first source (foreign API) is ARES https://wwwinfo.mfcr.cz/ares/ares_xml.html.cz. 
The second source (foreing API) is Airport info (https://rapidapi.com/Active-api/api/airport-info/details). 
The aim is to gain a test data which can be considered as personal client data (in real cases have to be pseudonymized). These APIs will then be combined together with offline datasets. The result of this procedure is a plain text dataframe which will be pseudonymized.

The created API will communicate using PKCS11 (Cryptoki) library with HSM Simulator provided by Utimaco (https://support.hsm.utimaco.com/hsm-simulator) to be able to perform all cryptographic operations.

A logged in user can generate test dataframes and later download it in both forms (plain text/encrypted)

Timetable is available during term on this page https://via.novascomp.synology.me/
The final application will be available here: https://via.novascomp.synology.me/

Timetable from older version of web page:
5. week HSM configuration BACKEND
6. PKCS #11 API basis BACKEND
7. PKCS #11 API basis 2 BACKEND
8. Swagger API
9. Dat Gen Microservice
10. Pseudonymization PKCS#11 Microservice
11. Frontend preparation
12. Frontend preparation
13. Dockerizing app

#### I am solving this topic (data pseudonymization) in my diploma thesis


