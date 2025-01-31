
#  /app /usr  /lib tiene este directorio
FROM  node:19.2-alpine3.17

#  cd app
WORKDIR /app
# PATH DE DIRECTORIO ROOT    && DESTINO DENTRO DE WORKDIR
# Dest /app
COPY app.js package.json ./

# INSTALAR DEPENDENCIA
RUN npm install


# RUN 

CMD ["node","app.js"]
