# SpringBoot Day 1 - Project 1

A simple Spring Boot starter application for Day 1 learning and practice.

## Project Overview

This repository contains a basic Spring Boot application built with Maven. It demonstrates the standard project structure, build lifecycle, and simple test setup for a beginner-friendly Spring Boot project.

## Features

- Spring Boot application entry point
- Maven build configuration
- Unit test integration
- Standard `src/main/java` and `src/test/java` layout

## Requirements

- Java 17 or newer
- Maven 3.8+

## Build and Run

1. Open a terminal in the project root.
2. Build the application:
   ```powershell
   mvn clean package
   ```
3. Run the application:
   ```powershell
   mvn spring-boot:run
   ```

## Run Tests

Execute the unit tests with:

```powershell
mvn test
```

## Project Structure

- `pom.xml` - Maven project configuration
- `src/main/java/com/day1/App.java` - Main application class
- `src/test/java/com/day1/AppTest.java` - Basic unit test

## Notes

This project is intended for learning Spring Boot basics and understanding a minimal Maven-based Java application setup.
