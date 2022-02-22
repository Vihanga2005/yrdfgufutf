FROM quay.io/lyfe00011/test:beta

RUN git clone https://github.com/Vihanga2005/yrdfgufutf /root/WhatsAsenaDuplicated
WORKDIR /root/WhatsAsenaDuplicated/
RUN yarn install --no-audit
RUN git clone https://github.com/Zenoixnoize/uploads
RUN cp -R /root/Utils/* /root/WhatsAsenaDuplicated 
CMD ["node", "bot.js"]
