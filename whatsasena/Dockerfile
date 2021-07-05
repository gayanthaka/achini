
FROM fusuf/whatsasena:latest

RUN git clone https://github.com/gayanthaka/achini /root/achini
WORKDIR /root/achini/
ENV TZ=Europe/Istanbul
RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["node", "bot.js"]
