# Node - Amazon
[![Build Status](https://github.com/sumanbh/node-amazon/actions/workflows/build.yml/badge.svg)](https://github.com/sumanbh/node-amazon/actions/workflows/build.yml)

Amazon look-a-like with Node, and Angular 11 with server-side rendering. Demo at: https://sumanb.com

## Requirements
You need to have **Node 10** or higher and **PostgreSQL 9.5** or higher installed.

## Setup
1. Install dependencies
    ```
    yarn install
    ```
    
2. Config is in: ``config/amazon.json``. Make changes there as you see fit (database host, user + password, port, OAUTH etc)
    
3. Initialize the database: ``yarn init:db``. This creates the database (default is node_amazon_dev), and initializes the tables with the seed data.

4. We can now run the development server: ```yarn start```
