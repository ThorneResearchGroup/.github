Welcome to the Thorne Research Group public code repository

*** Each repository is under HEAVY development and is not suitable for production use

The repositories here are the very same repositories we use in production, so if you're looking to setup your own local instance of any individual/combination of repositories, you will have everything you need.

Each project created by TRG is broken down into four sections, where applicable:
1. The backend or API server and micro services
2. The schema or model used to ingest or egress an interchange format
3. The library containing the REST client and functions used in the backend
4. The user interface (webui, cli, tui)

With that in mind, the repositories are laid out to be one repository per section.

1. Backend-*
2. Schema-*
3. Library-*
4. WebUI-*, CLI-*, TUI-*

Where the * is the name of the project. Eg if the name of my project was BabyGalago, the backend repo would be called Backend-BabyGalago.

Each of the backends have Docker images generated for them, which can be found here: https://hub.docker.com/repositories/jthorne94

Each of the schemas are published as a github package

Each of the libraries are published as a github package. You can use the library for communicating with the backend, or you can import the library as a dependency and run the same functions that the backend runs.

