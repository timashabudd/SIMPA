FROM fusuf/whatsasena:latest

RUN git clone https://github.com/timashabudd/DARK-QUEEN-NEW /root/ales
WORKDIR /root/ales/
RUN git clone https://github.com/timashabudd/DARK-QUEEN-NEW/Config
RUN git clone https://github.com/timashabudd/DARK-QUEEN-NEW
ENV TZ=Europe/Istanbul
RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["node", "bot.js"]
