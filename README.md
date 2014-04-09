Docker-Fundamentals
=======================

Repository for Docker Fundamentals course materials

http://www.slideshare.net/dotCloud/why-docker

# Instructor Guide for Docker Fundamentals 

## Installation

You'll need the [Puppet Labs fork of
Showoff](https://github.com/puppetlabs/showoff/).

    $ git clone https://github.com/puppetlabs/showoff.git
    $ cd showoff
    $ gem build showoff.gemspec
    $ sudo gem install ./showoff-*.gem

Showoff is tested with Ruby 1.8.7, 1.9.3, and 2.0. It should install
cleanly on these versions.

## Running the training

    $ showoff serve

You should be able to see the slides at:

    http://localhost:9090

You should be able to see the exercises at:

    http://localhost:9090/supplemental/exercises

The user name is ``docker`` and the password is ``maersk``.

## Training images

The training is based on using Amazon EC2 instances.

There are AMI instances in US East and US West 1.

| Region     | AMI          |
|------------|--------------|
| us-east-1  | ami-5364783a |
| us-west-1  | ami-bcd1e8f9 |

## Feedback

Feedback: [education@docker.com](mailto:education@docker.com)


