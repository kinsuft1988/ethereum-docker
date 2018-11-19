FROM node:10.1.0

RUN git clone https://github.com/kinsuft1988/ethInteract.git

WORKDIR /ethInteract

RUN npm install

EXPOSE 3001

ENV NAME EthInteract

CMD ["node", "ethWeb3Server"]