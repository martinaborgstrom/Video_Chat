# Hello World
Una Web App per lo scambio di messaggi real-time ed effettuare videochiamate 1-1

<img width="3071" height="1565" alt="image" src="https://github.com/user-attachments/assets/4271d1c5-0219-4589-9a65-9e70acb1f65f" />

### How to start Web Application
Come prima cosa sono richiesti i seguenti elementi:
Installare:
- Node.js
- npm
- ReactJS
- MongoDB Compass

In mongoDB, creare denominata ```helloWorld```, utilizzata per salvare gli utenti e i messaggi.

Impostare le variabili d'ambiente:
```
PORT = <port_number>
JWT_SECRET = <jwt_secret>
```

Installare le dipendenze e avviare server:
```
npm install
cd backend/src
node index.js
```
Avviare React:
```
cd fronted
npm start
```

Accedere alla web application all'indirizzo ```http://localhost:3000```
