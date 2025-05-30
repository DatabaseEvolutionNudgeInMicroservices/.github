# DENIM

DENIM provides developers with a suite of tools for downloading, reverse engineering, and visualizing microservices.

Repositories:

| Tools | Description | Repository | Docker Image |
| ------| ----------- | ---------- | ------------ |
| Web | It is the user interface. It communicates through HTTP requests with the user. It also communicates with other services through API requests in order to respond to user's needs according to the proposed features. | [Web](https://github.com/DatabaseEvolutionNudgeInMicroservices/web/) | [Web](https://hub.docker.com/repository/docker/maxiandr/denim-web) |
| Downloading | It aims to help the user to download, in one shot, with git, one or several microservices applications composing a microservices architecture and spread across multiple, distributed, and heterogenous repositories. According to a given JSON list of repositories links and hash as input, it returns a ZIP file containing all the architecture as output. | [Downloading](https://github.com/DatabaseEvolutionNudgeInMicroservices/Downloading/) | [Downloading](https://hub.docker.com/repository/docker/maxiandr/denim-downloading) |
| Reverse Engineering | It aims to reverse engineer, statically and dynamically, a microservices architecture in order to retrieve insights about the data access. According to a given ZIP file containing the microservices architecture as input, it returns a requested analysis report in JSON as output. | [Reverse Engineering](https://github.com/DatabaseEvolutionNudgeInMicroservices/reverse-engineering/) | [Reverse Engineering](https://hub.docker.com/repository/docker/maxiandr/denim-reverse-engineering) |
| Visualization | It aims to transform a static analysis report into visualizations. According to given a analysis report in JSON as input, it returns a one of the requested visualization model object in JSON as output. | [Visualization](https://github.com/DatabaseEvolutionNudgeInMicroservices/visualization/) | [Visualization](https://hub.docker.com/repository/docker/maxiandr/denim-visualization) |
| Evolution | It aims to retrieve, based on an analysis report, some evolution insights. According to a given analysis report in JSON as input, it returns a one of the requested evolution insight in JSON as output. | [Evolution](https://github.com/DatabaseEvolutionNudgeInMicroservices/evolution/) | [Evolution](https://hub.docker.com/repository/docker/maxiandr/denim-evolution) |

The architecture and the installation instructions are available [here](https://github.com/DatabaseEvolutionNudgeInMicroservices/denim).
