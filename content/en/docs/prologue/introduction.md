# The best deploy experience

## Intro

[bohr.io](https://bohr.io/) is a free fullstack `deploy` platform focused on **developer experience**.

Here you can host for free your projects, websites, blogs, landing pages, e-commerces, APIs, platforms or any other web application.

Like Github, bohr.io is being built on bohr.io. It means that **there are no limits to what you can build here** - from small projects to large platforms with high volume of access. 

## Technology

bohr.io is built with the most advanced infrastructure technologies. We are 100% **serverless** and much of the platform runs directly on the **edge**, enabling the experience with the lowest possible latency. 

For example: if you now run `npx bohr` in your terminal, bohr.io raises a local development server and automatically creates a tunnel so you can share an external URL pointing to your localhost. This tunnel will be created on the edge server closest to you.

_**Serverless computing powered by AWS, and edge computing powered by Cloudflare, make bohr.io auto-scalable, as so all the applications hosted here**_.

## Developer Experience

**bohr.io is fully integrated with Github**. When you click *Use this template*, bohr.io is automatically triggered from **Github Actions**, builds and deploys a new environment and makes it available directly on Github:

[PRINTS from GITHUB HERE]

## Supported Languages

## Supported Frameworks


## Features

 - Envs
 - Authenticação
 - Tunel
 - Built-in CMS

## Configuration

 - Build commands
 - Runtimes

## Community

## Testing a quote

> _**bohr.io is built with the most advanced infrastructure technologies. We are 100% serverless and much of the platform runs directly on the edge, enabling the experience with the lowest possible latency**_ - Lucas Boemeke, CTO at bohr.io

## Usage

```
name: bohr.io deploy
on: push
permissions: write-all
jobs:
  deploy:
    name: Deploy on bohr.io
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v3
      - uses: bohr-io/action@main	  
```

## Testing a table

| First header  | Second header | 
| :---: | :---: |
| Content cell  | Content cell  |
| Content cell  | Content cell  |
| Content cell  | Content cell  |
