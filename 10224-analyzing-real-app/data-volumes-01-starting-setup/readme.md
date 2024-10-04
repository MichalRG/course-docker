commands to run
docker build -t feedback-node:web .
docker run --rm --name feedback-app -p 3000:8000 --env-file ./.env -d -v /app/temp/ -v "{absolutePathToCatalog}\data-volumes-01-starting-setup:/app" -v /app/node_modules -v feedback:/app/feedback feedback-node:web
