FROM fusuf/whatsasena:latest

RUN git clone https://https://github.com/HUSNIV2/HUSNI__v2/root/WhatsAsenaDuplicated
WORKDIR /root/WhatsAsenaDuplicated/
ENV TZ=Europe/Istanbul
RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["node", "bot.js"]
