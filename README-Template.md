# DeveloperWeek 2020 Hackathon Challenge

As a team we are interested in using the HERE API to produce a real-time interactive application to simulate traffic lights based on streaming data. The Map API is to determine coordinates of longitude and latitude and analyze the traffic flow on each street. For this proof of concept, we used sixteen points, on a four by four grid in a small sample map of downtown San Francisco. To determine the color of the light, the current traffic flow value is used as a baseline, with a negative flow indicating red and a positive flow indicating green.

For our implementation of our application, we used React Framework with Javascript  Reinforcement Learning framework using Q-learning. Our data is parsed from a JSON format and passed on to our model to generate a dynamic graphical representation of traffic four-way light. The goal for this work is to optimize traffic lights to . For example, by knowing the total time a driver experiences a green or red light, one can optimize their route to take in consideration of these variables. Current routing and navigation systems do not account for traffic lights in causing congestion and user delay. 

# Architectural Overview
![Test Image 3](/diagram3.jpg)

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

Our proof of concept simply makes use of a localhost, we also plan on creating an instance running as a webapplication on a hosted environment using Heroku.

```
Give examples
```

### Installing



## Running the tests

Explain how to run the automated tests for this system

### Break down into end to end tests

Explain what these tests test and why

```
Give an example
```

### And coding style tests

Explain what these tests test and why

```
Give an example
```

## Deployment

Add additional notes about how to deploy this on a live system

## Built With

* React/Node.js - The web framework used for interactivity with the API 
* Visual Studio Code  - IDE 
* HERE Maps API  - Used the REST API to send requests for functionality of our application

## Contributing

Please read [CONTRIBUTING.md](https://gist.github.com/PurpleBooth/b24679402957c63ec426) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags). 

## Contributors

* **Sachin Shastei** - ML Engineer
* **Taylor Knulp-McDonna** - Data Engineer
* **Bruno Tapia Sierra** - Front end Developer
* **Chang Seong Kang** Front End Developer
*  **Sasha Tooryani** Devops Engineer

## License

This project is licensed under the MIT License 

## Acknowledgments

* To DeveloperWeek staff and Hackathon volunteers, also Galvanize for allowing to use workspace
* Sponors Yubikeys, Agora, HERE for mentoring and documentation
* etc

