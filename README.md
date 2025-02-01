## Next.js App Router Course - Starter

This is the starter template for the Next.js App Router Course. It contains the starting code for the dashboard application.

For more information, see the [course curriculum](https://nextjs.org/learn) on the Next.js Website.



 ## How to run it
 ## 1. pnpm install
 ## 2. create a .env in root folder
 ## 3. attach the following content into .env
 ## 4. pnpm run dev
##===========================================================================
 # Recommended for most uses
DATABASE_URL=postgres://neondb_owner:npg_hpodeb1FrL4Y@ep-rough-pond-a41hxhx7-pooler.us-east-1.aws.neon.tech/neondb?sslmode=require

# For uses requiring a connection without pgbouncer
DATABASE_URL_UNPOOLED=postgresql://neondb_owner:npg_hpodeb1FrL4Y@ep-rough-pond-a41hxhx7.us-east-1.aws.neon.tech/neondb?sslmode=require

# Parameters for constructing your own connection string
PGHOST=ep-rough-pond-a41hxhx7-pooler.us-east-1.aws.neon.tech
PGHOST_UNPOOLED=ep-rough-pond-a41hxhx7.us-east-1.aws.neon.tech
PGUSER=neondb_owner
PGDATABASE=neondb
PGPASSWORD=npg_hpodeb1FrL4Y

# Parameters for Vercel Postgres Templates
POSTGRES_URL=postgres://neondb_owner:npg_hpodeb1FrL4Y@ep-rough-pond-a41hxhx7-pooler.us-east-1.aws.neon.tech/neondb?sslmode=require
POSTGRES_URL_NON_POOLING=postgres://neondb_owner:npg_hpodeb1FrL4Y@ep-rough-pond-a41hxhx7.us-east-1.aws.neon.tech/neondb?sslmode=require
POSTGRES_USER=neondb_owner
POSTGRES_HOST=ep-rough-pond-a41hxhx7-pooler.us-east-1.aws.neon.tech
POSTGRES_PASSWORD=npg_hpodeb1FrL4Y
POSTGRES_DATABASE=neondb
POSTGRES_URL_NO_SSL=postgres://neondb_owner:npg_hpodeb1FrL4Y@ep-rough-pond-a41hxhx7-pooler.us-east-1.aws.neon.tech/neondb
POSTGRES_PRISMA_URL=postgres://neondb_owner:npg_hpodeb1FrL4Y@ep-rough-pond-a41hxhx7-pooler.us-east-1.aws.neon.tech/neondb?pgbouncer=true&connect_timeout=15&sslmode=require

# `openssl rand -base64 32`
AUTH_SECRET=
AUTH_URL=http://localhost:3000/api/auth

#============================================================================================================================