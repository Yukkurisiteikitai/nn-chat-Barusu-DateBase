# nn-chat-Barusu-DateBase


[モジュール]
@prisma/client: 5.13.0
http-auth: 4.2.0
prisma: 5.13.0
pug: 3.0.2

[ソフト]
docker 
VScode
tarminal(mac)

[起動プロセス]
docker compose up -d
docker compose exec app bash
yarn install
npx prisma db push
npx prisma generate
node index.js
