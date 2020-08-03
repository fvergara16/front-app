# front-app
frontend

- docker build -t front-image .
- docker run -p 81:80 --rm -it --name front-container front-image:latest

- http://localhost:81/examples/carousel/
- http://localhost:81/examples/blog/
- http://localhost:81/examples/checkout/
- etc…
