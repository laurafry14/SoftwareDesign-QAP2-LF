An assignment for Keyin College Software Development Program to build a simple REST API then test is in a local running Docker container.

To test the API first run a POST for each entity using the following URL: http://localhost:8080/{enter entity here}

You can then run a GET using the same URL.

To test the search use the following URL (example to search for Toronto in City entity): http://localhost:8080/city/search/findByName?name=Toronto

To run the project in Docker run the following command: 
    docker build -t keyin/qap2_s4_2023 .

Then run:
    docker-compose up
