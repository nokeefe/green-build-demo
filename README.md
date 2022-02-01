# green-build-demo


- [Description](#description)
- [Running Locally](#running-locally)
- [Additional Resources](#additional-resources)

---

## Description

A simple hello-world demo with docker to demonstrate a green build on CircleCI.

## Running locally

- Clone this repo.
- Open the ```config.yml``` file in the ```green-build-demo/.circleci/``` folder.
- Add an addition ```echo``` command below the existing ```hello world```, for example:

    ```- run: echo "testing the echo functionality!"```
- Commit and push the files.
- Go to the Projects page in the CircleCI app.
- Click the **Set Up Project** button next to your project.
- Trigger your first build.

## Additional Resources

- [Your First Green Build](https://circleci.com/docs/2.0/getting-started/)
- [Hello World](https://circleci.com/docs/2.0/hello-world/)
- [FAQ](https://circleci.com/docs/2.0/faq/)
- [Using Contexts](https://circleci.com/docs/2.0/contexts/)