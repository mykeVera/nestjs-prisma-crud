*** NEST JS + PRISMA (Sqlite) ***

## 1. Inicializamos un nuevo proyecto de Nest JS

```bash
nest new nestjs-prisma-crud
```
## 2. Instalamos Prisma

```bash
npm i prisma -D
```

## 3. Configuramos Prisma con Sqlite

```bash
npx prisma init --datasource-provider sqlite
```

## 4. Ejecutamos los archivos de migraciones dandole un nombre

```bash
npx prisma migrate dev --name init
```
