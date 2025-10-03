FROM debian:latest
RUN export node_version="0.10" \
&& apt-get update && apt-get -y install nodejs="$node_verion"
WORKDIR /use/share/app
COPY package.json .
RUN npm install node-static

EXPOSE 8000
CMD ["npm", "start"]