
Lista de depedencias
- fastify
- @prisma/client
- zod
  - validador de schemar & typescript

Lista de depedencias de -D
- typescript
- @types/node
- tsx -lib para executar e compilar codigos .js & .tsx
- tsup -lib para realizar o build do app
- prisma -lib de ORM



Configurações
- yarn tsc --init
  - inicializar a configuração do typescript
  - change: "target": 'es2016' to 'es2020'
- yarn prisma  init
  - inicializar as config do prisma
- yarn psirma migrate dev
  - roda a migrate
- yarn prisma studio
  - start do cliente de d.b web do prisma