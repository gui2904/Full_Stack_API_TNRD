# Full Stack API TNRD
This full stack program has its frontend in TypeScript, NodeJs uses TailWind. The backend was built in Rust and the database is postgres. Everything is then containerized with docker.

## To run locally
To get the application running on your local machine, follow these steps:

1. **Build the Docker containers**  
   Run the following command to build the Docker images:
   ```bash
   docker compose build
   docker compose up -d

## To view the database
`docker exec -it db psql -U postgres`
