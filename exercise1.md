# Exercise 1 - Warming up

## Common steps in a CI setup (Linting, testing, building)

1. Linting: 
    - **Clang-Format**: It formats C/C++ Code according to a set of style rules (Indentation, spacing, lines breaks).
    - **Clang-tidy**: It provides an extensible framework for diagnosing and fixing typical programming errors.

2. Testing:
    - **Unity**: It is a lightweight and user-friendly unit testing framework for C/C++.
    - **Alternatives**: CUnit, GoogleTest(GTest), Check

3. Building
    - **gcc/g++**: The GNU compiler collection is commonly used to compile C/C++ programs.
    - **Alternatives**: Clang, Intel C/C++ Compiler

## Alternatives to set up the CI

- **Cloud-based**:
    - Travis-CI, CircleCI, Azure Pipelines, AWS CodePipeline

- **Server-based**:
    - Travis-CI Enterprise, Circle Server, TeamCity

## Self-hosted or cloud-base environment

For this hypothetical situation, where the team is small (6 people) and the application will be released soon, the best option would be the easiest and fastest one to set up and configure.

Cloud based options are probably better in this situation, since the configuration is simpler compared to server based options.

One issue about cloud based option is the resources limitations, the team will be limited to the resources given by the cloud system to build their project, but in this particular situation the project might be small so this shouldn't be a problem.

Looking at price differences between both options the cloud should be better as well, because the team will be billed the build time only (This is something important to consider in bigger projects), and if they want a server-based option, they need to buy a server upfront in addition to the CI system.

