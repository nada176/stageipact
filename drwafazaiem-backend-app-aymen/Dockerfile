FROM node:20.5.0  

WORKDIR /drwafazaiem-backend-app-aymen

# Copier package.json et package-lock.json dans le répertoire de travail
COPY package.json ./
COPY package-lock.json ./

# Installer les dépendances
RUN npm install -f

# Copier le reste de l'application
COPY drwafazaiem-backend-app-aymen/ .

EXPOSE 6668

CMD ["node", "App.js"]
