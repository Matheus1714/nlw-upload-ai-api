# NLW | Upload AI API

![GitHub](https://img.shields.io/github/license/Matheus1714/nlw-upload-ai-api
)

## Table of Content 📜
<!--ts-->
   * [About](#about-ℹ️)
   * [About NLW](#about-nlw-🚀)
   * [Technologies Used](#technologies-used-⚙️)
   * [Features](#features-✅)
   * [Package Dependencies](#package-dependencies-⬇️)
   * [Running the Project](#running-the-project-🏃)
   * [What I learn](#what-i-learn-📝)
   * [Acknowledge](#acknowledge-☺️)
   * [License](#license-📖)
<!--te-->

## About ℹ️

Welcome to the Upload AI api project, where you can effortlessly upload videos and have automatic titles and descriptions generated for you.

<p align="right"><a href="#readme-top">🔝 Return</a></p>

## About NLW 🚀

NLW (Next Level Week) is an event organized by Rocketseat, dedicated to exploring cutting-edge technologies and empowering programmers to build high-quality projects quickly.

This project was created during NLW to embrace and master the latest technologies, resulting in an application powered by multiple advanced technologies.

<p align="right"><a href="#readme-top">🔝 Return</a></p>

## Technologies Used ⚙️

The technologies utilized in this project include:

* [Fastify](https://fastify.dev/)
* [Typescript](https://www.typescriptlang.org/)
* [Prisma](https://www.prisma.io/)
* [OpenAI](https://openai.com/)

<p align="right"><a href="#readme-top">🔝 Return</a></p>

## Features ✅

- [X] Create Routes
- [X] Add Prima DB
- [X] Integrate OpenAI

<p align="right"><a href="#readme-top">🔝 Return</a></p>

## Package Dependencies ⬇️

Here is a list of the project's package dependencies:

```json
"devDependencies": {
    "@types/node": "^20.6.0",
    "dotenv": "^16.3.1",
    "prisma": "^5.2.0",
    "tsx": "^3.12.9",
    "typescript": "^5.2.2"
},
"dependencies": {
    "@fastify/cors": "^8.3.0",
    "@fastify/multipart": "^7.7.3",
    "@prisma/client": "5.2.0",
    "ai": "^2.2.12",
    "fastify": "^4.23.0",
    "openai": "^4.6.0",
    "zod": "^3.22.2"
}
```

<p align="right"><a href="#readme-top">🔝 Return</a></p>

## Running the Project 🏃

1. Install the project dependencies:

```shell
pnpm i
```

2. Create Prisma Database

```shell
pnpm prisma migrate dev --name init
```

3. Create dataset

```shell
pnpm prisma db seed
```

4. Access prisma studio

```
pnpm prisma studio
```

5. Configure enviroment variables. Add your OpenAI key.

```env
DATABASE_URL="file:./dev.db"
OPEN_AI_KEY="..."
```

6. Execute the following command in your terminal to run the project:

```
pnpm run dev
```

## Acknowledge ☺️

A special thanks to Rocketseat and their dedicated instructors who provide incredible content to the React community, making projects like this possible. Your guidance and support are greatly appreciated.

<p align="right"><a href="#readme-top">🔝 Return</a></p>

## License 📖

This project is open-source and is distributed under the MIT License. Feel free to explore, modify, and utilize the codebase according to the terms outlined in the license.

<p align="right"><a href="#readme-top">🔝 Return</a></p>