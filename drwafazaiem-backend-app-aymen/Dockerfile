FROM node:20.5.0  

WORKDIR /drwafazaiem-backend-app-aymen

## vous devez ici placer le nom de votre dossier backend

COPY package.json package-lock.json ./
#RUN npm install -g npm@10.8.1

RUN npm install -f

COPY . .

EXPOSE 6668

CMD ["node","server.js"]
