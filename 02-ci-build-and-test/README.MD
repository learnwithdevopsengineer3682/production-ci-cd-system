# Episode 2: CI Build & Test

In this episode, we move from a basic pipeline to a real CI pipeline.

## What we add:
- Docker image build
- Running application inside pipeline
- Test stage

## What we demonstrate:
A pipeline can pass even when the application is broken.

## Key Learning:
CI/CD pipelines only execute steps.
They do not guarantee correctness unless tests are meaningful.

## Fix:
We replace fake tests with real validation using application health checks.