# Schema, vecka 22
###### Backend med Node.js, vecka 3 av 5

## Introduktion

Att skydda användardata och dokumentera vår backend är avgörande för att bygga professionella applikationer. I denna modul lär vi oss hur man krypterar lösenord, använder JSON Web Tokens (JWT) för autentisering och hur man skyddar olika delar av ett API. Vi går även igenom hur man dokumenterar sina endpoints med Swagger för att göra API:er enklare att förstå och använda. Fokus ligger på säkerhet, tydlighet och utvecklarupplevelse. När du är klar med denna modul kommer du kunna bygga säkra backendapplikationer med professionell dokumentation!


## Mål för veckan:

1. Kunna kryptera lösenord på serversidan med t.ex. bcrypt
2. Kunna skapa och hantera autentisering med JWT
3. Förstå säkerhetsaspekter vid utveckling av API:er
4. Kunna dokumentera ett API med hjälp av Swagger
5. Kunna läsa, förstå och ge feedback på någon annans backend-kod


## Resurser

### Presentationer

* 01 - [Auth](https://docs.google.com/presentation/d/1nLBDcXpzWVzZGTO-g0JGGI9cGbd8-L12/edit?usp=sharing&ouid=117251319654116712560&rtpof=true&sd=true)

### Inspelade föreläsningar

### Lektionsrepon

* [Bcrypt & JWT, 25 maj](https://github.com/fu-node-webb25/week-22-lecture-25-maj)

### Filmer


### Länkar

* [Jsonwebtoken documentation](https://www.npmjs.com/package/jsonwebtoken)
* [Bcrypt documentation](https://www.npmjs.com/package/bcrypt)
* [Swagger documentation](https://swagger.io/docs/)

### Övningar 

Denna vecka är tanken att ni fortsätter arbeta med era Todo APIer. Ni skall:
* Kryptera alla lösenord innan de skickas till databasen
* Använda jsonwebtoken till autentisering och auktorisering istället för ```global.user``` från förra veckan
* Dokumentera ert API med Swagger 

Om ni vill så kan ni ju även passa på att bygga en frontend-app till ert API. Glöm isåfall inte bort att läsa på om [cors](https://www.npmjs.com/package/cors) så att ni kommer åt er server från klienten.
