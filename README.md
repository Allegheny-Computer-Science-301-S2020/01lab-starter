
# cs301-S2020-lab01-starter

Designed for use with [GitHub Classroom](https://classroom.github.com/), this repository contains the starter files for the lab of this course.

## Objectives


Google Analytics is one of the most popular enterprise web analytics platform that provides rich insights into website traffic and marketing effectiveness. In the first part of the lab you are invited to investigate the available tools on Google analytics and summarize your understanding of these tools. You are also asked to discuss some of the ethical implications that may result from the collected information of visitors to a website. In the second part of the lab you are asked to explore the issues which follow the theme of the speaker about marketing research.


## Testing your assignment
This assignment uses [Docker](https://www.docker.com) and [GatorGrader
tool](https://github.com/GatorEducator/gatorgrader) to check whether your assignment satisfies the minimum submission requirements.
First, you need to make sure you have installed [Docker
Desktop](https://www.docker.com/products/docker-desktop) and have it running.
Then, you can use you can use the [GatorGrader
tool](https://github.com/GatorEducator/gatorgrader)
to verify that the minimal content of your reflection document satisfies the
requirements specified in the lab assignment sheet. To 
run the GatorGrader application to start `gradle grade` as a containerized
application, using the [DockaGator](https://github.com/GatorEducator/dockagator)
Docker image available on
[DockerHub](https://cloud.docker.com/u/gatoreducator/repository/docker/gatoreducator/dockagator).
First, to ensure that the following command will work correctly, you
must create the cache directory by running the command `mkdir
$HOME/.dockagator`.
Then, to see if your submission satisfies the minimal requirements, you can run the following command in the terminal:

```bash
docker run --rm --name dockagator \
  -v "$(pwd)":/project \
  -v "$HOME/.dockagator":/root/.local/share \
  gatoreducator/dockagator
```

This command will use `"$(pwd)"` (i.e., the current directory) as
the project directory and `"$HOME/.dockagator"` as the cached GatorGrader
directory. Please note that both of these directories must exist, although only
the project directory must contain something. Generally, the project directory
should contain the source code and technical writing of this assignment, as
provided to a student through GitHub. Additionally, the cache directory should
not contain anything other than directories and programs created by DockaGator,
thus ensuring that they are not otherwise overwritten during the completion of
the assignment.  If the above `docker run` command does not work correctly on
the Windows operating system, you may need to instead run the following command
to work around limitations in the terminal window:

```bash
docker run --rm --name dockagator \
  -v "$(pwd):/project" \
  -v "$HOME/.dockagator:/root/.local/share" \
  gatoreducator/dockagator
```

## Assistance

If you are having trouble completing any part of this project, then please talk with either the course instructor or a tech-leader during the lab session. You can also schedule a meeting during the course instructor's office hours.
