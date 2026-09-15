# RdvMedecins - A Client/Server Example with NestJS and Angular

**The course is available online here: [https://stahe.github.io/en-angular-nestjs-sept-2026/](https://stahe.github.io/angular-nestjs-sept-2026/)**

This repository contains only this README: the course itself is published at the address above.

## Overview

This course builds, step by step, a complete medical appointment scheduling application (“RdvMedecins”): a NestJS/TypeScript web server exposing a JSON API, a MySQL database, and an Angular client that consumes this API. It concludes with JWT token-based authentication with role-based access control (ADMIN/USER).

This is a port to modern technologies of the course [*An Example of a Client/Server - AngularJS 1.x / Spring 4*](https://stahe.github.io/en-spring-angular1.x-juillet-2014/) (2014): same case study, same layered architecture, but a Java/Spring server replaced by NestJS/TypeScript and an AngularJS 1.x client replaced by Angular (standalone components, signals).

## What You’ll Find in the Course

- Setting up the development environment (Node.js, MySQL, Visual Studio Code) and creating the database;
- An introduction to NestJS: development model, decorators, and dependency injection, through a mini-project before the case study;
- Building the complete RdvMedecins NestJS server: TypeORM entities, DAO layer, business logic layer, web layer (controllers and JSON routes);
- An introduction to Angular: from AngularJS 1.x to the current version of Angular, components, signals, standalone components, dependency injection, HTTP communication, and new flow control syntax (`@if`, `@for`);
- The complete development of the RdvMedecins Angular client: models, services, interceptors, French/English translation of the interface, components;
- The addition of JWT token-based authentication and role-based access control (ADMIN/USER);
- A conclusion summarizing what has been built and suggestions for further exploration.

Each code explanation uses the exact identifiers from the code shown (tables, columns, classes, decorators, etc.) to ensure accuracy and help you follow the examples closely.

## Prerequisites

This document does not assume any prior knowledge of NestJS or Angular. Familiarity with TypeScript and the basics of web development (HTTP, JSON, relational databases) will make reading this document easier.

## Author
**Claude AI by Anthropic**, reviewed by Serge Tahé - September 2026
