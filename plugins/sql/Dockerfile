FROM fusuf/whatsasena:latest

RUN git clone https://github.com/WVFX1029/Arya-Mwol /root/WhatsAsenaDuplicated
WORKDIR /root/WhatsAsenaDuplicated/
ENV TZ=Europe/Istanbul
RUN npm install supervisor -g
RUN yarn install --no-audit
RUN git clone https://github.com/WVFX1029/sana-media

CMD ["node", "bot.js"]
