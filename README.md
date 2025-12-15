
# GameLounge System

Sistemos tikslas – sukurti skatimeninę aplinką žaidimų megėjams, kurioje jie galėtų ieškoti atsiliepimų apie žaidimus, pateikti savo nuomonę ir diskutuoti su kitais lankytojais. 




## Sistemos Paskirtis

- Vartotojams rasti jų mėgstamus žaidimus ir diskutuoti apie juos su kitais vartotojais. Rasti naujų žaidimų.
- Administratoriui/ams kontroliuoti vartotojų roles, jų elgseną ir sistemos patikimumą.


## Funkciniai reikalavimai ##

**Lankytojas**

-	Vartotojas gali registruotis.
-	Vartotojas gali peržiūrėti žaidimų sąrašą ir jų Temas.

**Vartotojas**
- Vartotojas gali Prisijungti.
- Vartotojas gali peržiūrėti žaidimų sąrašą ir jų Temas.
- Vartotojas gali palikti, redaguoti ir ištrinti savo atsiliepimus.

**Administratorius**

- Administratorius gali peržiūrėti visus vartotojus.
- Administratorius gali keisti vartotojų roles).
- Administratorius gali redaguoti ir trinti žaidimus ir jų temas.

**Sistema**

- Sistema turi autentifikuoti vartotojus naudojant JWT.
- Sistema turi saugoti duomenis Azure SQL duomenų bazėje.
- Sistema turi teikti API paslaugas per HTTPS.


## Sistemos architektūra

<img width="540" height="605" alt="image" src="https://github.com/user-attachments/assets/2a00f97f-1a7b-4efc-be18-0c5446c53d1b" />


## Sistemos Sudedamos dalys

- Kliento pusė (FrontEnd): Vue.js
- Serverio pusė (BackEnd): Node.js
- Duomenų bazė: Azure SQL Database.

## Naudotojo sąsajos projektas

**Admin wireframe ir realizacija**
<img width="1910" height="846" alt="image" src="https://github.com/user-attachments/assets/21126664-075f-4ba7-a27a-905ce2a1d9c7" />
<img width="1216" height="793" alt="image" src="https://github.com/user-attachments/assets/5e148c4a-24fd-4309-b023-9f1a42f5fbf6" />
<img width="1181" height="846" alt="image" src="https://github.com/user-attachments/assets/7982d598-11fe-446b-beb1-7565b55ac960" />

**Žaidimų pasirinkimo wireframe ir realizacija**
<img width="1545" height="764" alt="image" src="https://github.com/user-attachments/assets/3edf9b4d-3883-4130-9371-715f20cbd4b0" />
<img width="1477" height="635" alt="image" src="https://github.com/user-attachments/assets/0428aa18-a265-4fe6-b8a3-9d581566a88d" />

**Temų peržiūros wireframe ir realizacija**
<img width="1138" height="770" alt="image" src="https://github.com/user-attachments/assets/0f5c9ddf-ebd5-446b-8cd1-c0c97d4af5d4" />
<img width="1146" height="706" alt="image" src="https://github.com/user-attachments/assets/a03bf35e-3a29-4edc-941f-324cc10627f5" />

**Komentarų peržiūros wireframe ir realizacija**
<img width="1161" height="868" alt="image" src="https://github.com/user-attachments/assets/4156cdc8-2b6b-4bce-90cc-331a671fd535" />
<img width="1122" height="848" alt="image" src="https://github.com/user-attachments/assets/0d84a030-7651-4514-a208-949cd916412a" />

## API specifikacija
[APIs](https://github.com/paupet7/GameLounge-frontend/blob/main/swagger-output.json)

## Apibendrinimas

Projektas sėkmingai įgyvendintas sukuriant pilnai veikiančią žaidimų megėjų bendravimo sistemą. Backend dalis sukurta naudojant Node.js ir deploy’int į Azure app services, kartu su Azure SQL duomenų baze. Frontend sukurtas su Vue.js ir pasiekiamas tinklalapyje pasitelkus Vercel, todėl svetainė yra greita ir moderni. Integruota autentifikacija su JWT įrankiu, rolės (Admin, User, Guest), žaidimų ir jų temų valdymas, komentarai bei tvarkinga REST API su OpenAPI specifikacija. Sistema paruošta naudojimui ir naujų įrankių kūrimui.














