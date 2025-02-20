[![Open in GitPod](https://img.shields.io/badge/Gitpod-Ready--to--Code-blue?logo=gitpod)](https://gitpod.io/#https://github.com/EddieHubCommunity/LinkFree) ![Uptime](https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2FEddieHubCommunity%2Fmonitoring%2Fmaster%2Fapi%2Flink-free-linkfree-io%2Fuptime.json) [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) [![GitHub release (latest by date)](https://img.shields.io/github/v/release/EddieHubCommunity/LinkFree)](https://github.com/EddieHubCommunity/LinkFree/releases) ![GitHub repo size](https://img.shields.io/github/repo-size/EddieHubCommunity/LinkFree)

# What is LinkFree?

A platform where people in tech can have a single hub to showcase their content in order to accelerate their career, whilst contributing to an Open Source project and being part of a community that has a say in where the project is going.

Your profile will have links to your social media and content. You can also add your timeline, testimonials, and upcoming events that you are participating in.

Here is an example of a LinkFree Profile https://linkfree.io/eddiejaoude

![Example profile and statistics page on LinkFree with light and dark mode](https://user-images.githubusercontent.com/624760/230707268-1f8f1487-6524-4c89-aae2-ab45f0e17f39.png)

## Tech Stack

LinkFree is built using the following technologies:

- [Next.js](https://nextjs.org/) - a framework for building server-rendered React applications
- [MongoDB](https://www.mongodb.com/) - a NoSQL database
- [Tailwind CSS](https://tailwindcss.com/) - a utility-first CSS framework      

## Quickstart

You have 4 options to contribute to the repo, please pick your favourite from:

1. [GitHub UI (recommended for adding/editing your profile)](https://github.com/EddieHubCommunity/LinkFree#github-ui)
2. [Gitpod](https://github.com/EddieHubCommunity/LinkFree#gitpod)
3. [Local development](https://github.com/EddieHubCommunity/LinkFree#local-development)
4. [Local development with Docker Compose](https://github.com/EddieHubCommunity/LinkFree#local-development-with-docker-compose)

Brief documentation is below, but full documentation can be found here https://linkfree.io/docs

> **Warning**:
> Your DB will be empty, you will need to load the data into the database! You can do this by visiting the url `/api/system/reload?secret=development`

### GitHub UI

This is great if you only want to add your Profile or make changes to it.

Here is the **QuickStart** guide to add your profile - https://linkfree.io/docs/quickstart

> **Note**: give extra attention to JSON formatting and the GitHub Action after you create the Pull Request

Read more in the official documentation - https://linkfree.io/docs/environments/github-ui

### Gitpod

In the cloud-free development environment which will have all the dependencies you need (for example MongoDB).

You can use Gitpod in the cloud [![Gitpod Ready-to-Code](https://img.shields.io/badge/Gitpod-Ready--to--Code-blue?logo=gitpod)](https://gitpod.io/#https://github.com/EddieHubCommunity/LinkFree/)

Read more in the official documentation - https://linkfree.io/docs/environments/gitpod 

### Local development

This environment is fully on your computer and requires each dependency (for example MongoDB) to be installed and set up, but it gives you the most flexibility for customisation.

#### Prerequisites

Before contributing or adding a new feature, please make sure you have already installed the following tools:

- [NodeJs](https://nodejs.org/en/download/) (Works with Node LTS version v18.16.1)
- [MongoDB](https://www.mongodb.com/home)
- Optional [NVM](https://github.com/nvm-sh/nvm): Switch Node version by using `nvm use` (on Windows, use `nvm use v18.16.1`). If this is not installed, run `nvm install v18.16.1`.

#### Commands

You can set this up locally with the following steps:

1. copy the `.env.example` file to `.env` and update any details required
1. MongoDB is required, it is possible to use `docker compose up` to start the MongoDB service
1. `npm ci`
1. `npm run dev`

Read more in the official documentation https://linkfree.io/docs/environments/local-development#local-development

### Local development with Docker Compose

This will allow you to run your favourite IDE but not have to install any dependencies on your computer like NodeJS and MongoDB.

#### Prerequisites

- [Docker](https://www.docker.com/)
- [Docker Compose](https://github.com/docker/compose) V2.

#### Commands

1. `docker compose up` 

Read more in the official documentation - https://linkfree.io/docs/environments/local-development#docker-compose

### How to add YOUR Profile

Step by step quickstart guide can be found in the full docs here - https://linkfree.io/docs/quickstar

## GitHub Accelerator

LinkFree was accepted into the GitHub Accelerator program...
![GitHub Accelerator](https://user-images.githubusercontent.com/624760/235968674-01cc3149-f9c3-48e2-9dc5-677789de8456.png)
https://accelerator.github.com

## Support

Don't forget to leave a star ⭐️.

## Our Pledge

We take participation in our community as a harassment-free experience for everyone and we pledge to act in ways to contribute to an open, welcoming, diverse and inclusive community.  

If you have experienced or been made aware of unacceptable behaviour, please remember that you can report this.  Read our [Code of Conduct](https://github.com/EddieHubCommunity/LinkFree/blob/main/CODE_OF_CONDUCT.md) for more details.
