## Probability Based Sampling Tracing

### Installation

1. Clone this repo.
2. Install dependencies: `npm install`.
3. Run migrations: `npx prisma migrate dev`.
4. Start jaeger: `docker-compose up -d`
5. Start the server: `npm run dev`.
6. Test out the example endpoint a few times: [http://localhost:4000/users/random](http://localhost:4000/users/random).
7. See the generated traces in Jaeger: <http://localhost:16686/>
