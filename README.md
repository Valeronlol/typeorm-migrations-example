# Working example in 2022 for migration Typeorm. v0.3.6

### How to configure?
- `npm i`
- `docker-compose up -d`

### Migrations
- `npm run migration:create src/migrations/name` - create empty template for migration
- `npm run migration:generate src/migrations/name` - generate by diff in entity changes.
- `npm run migration:up src/migrations/test` - rollout 
- `npm run migration:down` - revert last migration
