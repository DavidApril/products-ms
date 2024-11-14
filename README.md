<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="120" alt="Nest Logo" /></a>
</p>

# Products Microservice

A NestJS microservice for managing product data with TCP transport.

## Description

This microservice handles product management operations including:
- Creating products
- Retrieving products (single and paginated list)
- Updating products
- Soft deleting products

## Features

- Built with NestJS framework
- Uses TCP transport for microservice communication
- Prisma ORM for database operations
- Input validation using class-validator
- Pagination support
- Soft delete functionality

## Installation

1. Clone the repository:
```bash
git clone 
```

2. Install dependencies

```bash
npm install
```
```bash
yarn install
```

3. Create a copy of ```.env.template``` rename ```.env``` and fill required variables

4. Execute prisma migrations 
```bash
npx prisma migrate dev
```

5. start microservice
```bash
npm run start:dev
```
