# Pseudonymization app
The purpose of this application is to pseudonymize certain columns in a test dataframe. 
The first source (foreign API) is ARES https://wwwinfo.mfcr.cz/ares/ares_xml.html.cz. 
The second source (foreing API) is Airport info (https://rapidapi.com/Active-api/api/airport-info/details). 
The aim is to gain a test data which can be considered as personal client data (in real cases have to be pseudonymized). These APIs will then be combined together with offline datasets. The result of this procedure is a plain text dataframe which will be pseudonymized.

The created API will communicate using PKCS11 (Cryptoki) library with HSM Simulator provided by Utimaco (https://support.hsm.utimaco.com/hsm-simulator) to be able to perform all cryptographic operations.

A logged in user can generate test dataframes and later download it in both forms (plain text/encrypted)

The final application will be available on this url https://via.novascomp.synology.me/

#### I am solving this topic (data pseudonymization) in my diploma thesis
