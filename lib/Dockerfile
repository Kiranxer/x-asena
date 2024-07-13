FROM quay.io/loki-xer/jarvis-md:latest
RUN git clone https://github.com/Kiranxer/x-asena /root/x-asena/
WORKDIR /root/x-asena/
RUN yarn install --network-concurrency 1
CMD ["node", "bot.js"]
