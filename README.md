This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).


## Getting Started

check if you have docker and docker compose setup / installed on your machine

```bash
docker -v
docker-compose -v
```

Building the docker image
```bash
docker build -t docker-next 
```

## How to run the application

Run the development server:

```bash
docker-compose up
```
To install new dependencies

```bash
docker-compose run --rm app npm install <package name>
```
Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.
