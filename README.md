# Play with Containers

## Project Description

Dockerised the last CRUD-master assignment.

Each microservice received it's own docker container, so did each of the microservice database.

Also added volumes to the database for data persistency.

In total, 6 docker containers, 3 volumes, 1 network was added and conneted to eachother as required per project assignments.

## Table of Contents

- [How to run](#howtorun)
- [Audit](#audit)
- [Video](#videos)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)
- [Authors](#authors)

## How to run

Have Docker and Postman installed

Git clone the project, cd inside it and run

```python
docker-compose up
```

Wait 5-10m until docker loads all containers.

Open Postman and query the Gateway container with beforementioned APIs as seen in the video.

## Audit

To audit the program, follow the steps [here](https://github.com/01-edu/public/tree/master/subjects/devops/play-with-containers/audit).

## Project Videos

Video: https://youtu.be/MGmq2ekKq_E

## Contributing

We welcome contributions! Please contact one of the authors in discord if you would like to contribute to future projects.

## License

This project is licensed under the MIT License. See the [LICENSE](https://opensource.org/license/mit) file for details.

## Contact

For any questions or suggestions, feel free to contact us directly at `Kood / Jõhvi Discord`.

## Authors

_Authors: [Jaanus Saar](https://01.kood.tech/git/jsaar)_
