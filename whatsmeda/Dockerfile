FROM fusuf/whatsasena:latest

RUN git clone https://github.com/harddecode/WhatsMedaDuplicated /root/WhatsMedaDuplicated
WORKDIR /root/WhatsMedaDuplicated/
ENV TZ=Europe/Istanbul
RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["node", "bot.js"]
