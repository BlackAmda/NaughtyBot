FROM fusuf/whatsasena:latest

RUN git clone https://github.com/BlackAmda/NaughtBot /root/NaughtBot
WORKDIR /root/NaughtBot/
ENV TZ=Europe/Istanbul
RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["node", "bot.js"]
