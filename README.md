# Star Wars GraphQL API

## Description
This application serves as a comprehensive data hub for the Star Wars universe, leveraging the SWAPI (Star Wars API) to provide users with extensive information about various entities within this iconic series. 
Built using Node.js with NestJS and GraphQL, it offers a robust and efficient way to access data about films, species, vehicles, starships, and planets from the Star Wars franchise. 
The application not only fetches and displays data but also enhances user experience through advanced features like caching, pagination, and detailed analytics of film scripts.

## Features
- [ ] `Data Retrieval`: Users can query detailed information about different entities in the Star Wars universe, including:
  - `Films`: Access data about each Star Wars film.
  - `Species`: Explore various species featured in the series, with details.
  - `Vehicles`: Get information on a wide range of vehicles.
  - `Starships`: Delve into details about different starships.
  - `Planets`: Discover various planets within the Star Wars galaxy.

- [ ] `Pagination and Filtering`

- [ ] `Caching Mechanism`: Implement a 24-hour caching strategy for all data fetched from the SWAPI.

- [ ] `Analytical Insights`:
  - [ ] `Word Frequency`: Analyzes film scripts to identify and count unique words.
  - [ ] `Character Mentions`: Determines which characters are mentioned most across all film scripts.

- [ ] `GraphQL Interface`: Utilize GraphQL for efficient and flexible data queries, allowing users to request exactly what they need, reducing bandwidth and improving response times.

- [ ] `Testing`: Covering both unit and integration tests.

- [ ] `Documentation`: Detailed documentation for all endpoints and functionalities.

- [ ] `Docker Integration`: Facilitate easy setup and deployment with Docker Compose, allowing developers to run the API in any environment with minimal configuration.