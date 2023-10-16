serve:
	sh ./dev.sh

# target: down - stop and down docker stack
down:
	docker compose -f docker-stack.yml down

back:
	cat postgres_air_2023.sql | docker exec -i posopt-db-dev psql -U postgres
