FROM node:20

ENV DEBIAN_FRONTEND=noninteractive

RUN apt -y update && apt -y install --no-install-recommends xorg openbox libnss3 libasound2 libatk-adaptor libgtk-3-0

RUN npm install -g electron --unsafe-perm=true --allow-root

CMD electron .
