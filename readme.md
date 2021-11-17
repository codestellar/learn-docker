# Learn Docker
The goal is to do a handson on Docker

## What should one know?
- What is docker?
    - A platform that makes development and deployment much easier and unified as we'll be making an image that includes the application, it's configuration and it's dependencies

- What is an image repository?
    - So, once the image is created, that should be stored somewhere for re-use or for deployment and that store is called docker repository. You can have your own docker repository and Docker hub is a public repository.

- What problem it solves?
    - Well, just imagine, you are a team of 10. You are developing a complex application and that is having 10 different dependencies like database, redis, nodejs, .net etc. What you would need to do? Install the Application requirements on all the Operating Systems and you may face different issues. And what if you want to run the different versions of the application?

    - Same is the case with deployment, for deployment you have to produce artifacts and then write docs of instructions on how to deploy a particular component.

    - Docker gives you the unified platform to make the development and deployment easier.

- What is docker image?
    - Actual package that contains Application, Configuration dependencies, start script.
- What is Container?
    - Application instance running the image