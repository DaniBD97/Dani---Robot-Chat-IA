

## Mini Proyecto para usar la API de OpenAi

Este proyecto usa Drizzle ORM y Open AI en NEXTJS 15

## Primero instalamos las Dependencias para Este proyecto



```bash
npm install drizzle-orm pg dotenv

Or

yarn install drizzle-orm pg dotenv

```

.drizzle-orm: ORM para manejar PostgreSQL.
.pg: Cliente de PostgreSQL para Node.js.
.dotenv: Para manejar variables de entorno (credenciales de la base de datos).


```bash

DATABASE_URL=postgresql://usuario:contraseña@localhost:5432/NombreBaseDeDatos

```

## Inicia Drizzle

```bash

npm install drizzle-kit -D

```
## Configura Drizzle

```bash

{
  "schema": "./src/schema.ts",
  "out": "./drizzle"
}


```

## Configura El Archivo de Drizzle


```bash

npx drizzle-kit generate
npx drizzle-kit push



```

Luego de configurar la base de datos para guardar los mensajes del chat tienes que ingresar la configuracion de Open AI
Que son la key en el archivo .Env y el metodo que te da para usar los modelos disponibles segun tu plan/suscripción
Todo eso encontrado en la pagina de OpenAi al momento de pedir la key

## https://platform.openai.com/api-keys






