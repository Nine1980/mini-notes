mkdir webapp && cd webapp
mkdir frontend

cd frontend
npx create-next-app@latest . --typescript --tailwind --eslint

npm install axios react-hook-form zod

npm i -g @nestjs/cli
nest new backend

npm install prisma @prisma/client
npx prisma init

npx prisma migrate dev

npm install @nestjs/config
