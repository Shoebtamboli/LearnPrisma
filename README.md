## How to run

```
git clone the repo
cd prismagraphql
npm i
npm run dev
```

### Navigate to [localhost:4000](http://localhost:4000) in your browser and explore the API.

## How to migrate

### The below command creates migration directory

```
npx prisma migrate dev --name init
```

## Generate TypeGraphQL

### Run below command to generate TypeGraphQL classes and CRUD resolvers based on your Prisma schema.

```
npx prisma generate
```

## Run below command to open prisma studio

```
npx prisma introspect
npx prisma studio
```

### Navigate to [localhost:5555](http://localhost:5555) in your browser and explore the prisma studio.
