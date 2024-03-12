# manheim
Manheim Logistics Coding Exercises

Following are two short coding exercises to complete. Please deliver your solution as a link to a
public GitHub repository.
These exercises do not need to be “production” quality, but we are trying to get a sense for
how you organize your thoughts into code and how you like to work.
We think both exercises can be completed in about 2-4 hours, but please take as much or as
little time as you need to show us what you can do. We do ask that you return your solution to
us within seven days.

Exercise #1
Write a shell script that prints a list of all the open pull requests in all the GitHub organizations
to which you have access. Assume that the environment variables GH_PAT and GH_HOST will
be provided. Your solution will need to run on a minimal Ubuntu Server instance (such as a
Docker container). You may install and require additional packages or utilities, if necessary, but
this exercise is really about what you can do with the lowest common denominator computing
environment.

Exercise #2
Write a Terraform configuration that creates an ECS Service which will run a stock nginx Docker
container (nginx:latest). Assume that your configuration will be given an ID for a pre-existing
VPC and a list of Subnet IDs to use as inputs. Your solution should output the public-facing URL
to where the nginx server can be accessed in a browser. You may not use any modules from the
Terraform registry for this exercise.
