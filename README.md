# docker For Creating a Image:-docker build -t nodeapp:v3 -f Dockerfile.dev .
For Creating a Container:-docker run --name my-node-app -p  8000:3000 -v $(pwd):/user/src/app -v /user/src/app/node_modules nodeapp:v3
This will run localhost:8000 
For checking the file:-docker exec -it with-ignore /bin/sh
