FROM node:12

WORKDIR /usr/src/app

RUN apt update && apt install git -y

RUN git clone https://github.com/danangekal/ikan-id

WORKDIR ikan-id

RUN sed -i 's/3000/30007/g' .env.example

RUN cp .env.example .env.production

RUN yarn install

RUN yarn add sharp

RUN yarn build

CMD ["yarn","start"]
