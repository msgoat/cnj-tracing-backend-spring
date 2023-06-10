# cnj-tracing-backend-spring

Cloud native Java backend using Micrometer Telemetry/OpenTelemetry via Jaeger based on Spring Boot.

## Status

![Build status](https://codebuild.eu-west-1.amazonaws.com/badges?uuid=eyJlbmNyeXB0ZWREYXRhIjoiLzNFNml2UG5qTi9DR1Y4dkFIUnNPMnhRbjA1UVpJbmpiZDNPYlc1TFEvYjltSDdyUnBEMUJKV3l5bFI2Q0VxM2JmREgzK3Jjd0Z1WEdXSHFJOUNOZ2U4PSIsIml2UGFyYW1ldGVyU3BlYyI6IkZrN0g5SXVydk4xTDB1M3UiLCJtYXRlcmlhbFNldFNlcmlhbCI6MX0%3D&branch=main)

## Release information

Check [changelog](changelog.md) for latest version and release information.

## HOW-TO run this showcase locally

In order to run the whole showcase locally, just run the following docker commands in the project folder:

```shell 
docker compose up -d
docker compose logs -f 
```
The showcase application will be accessible via `http://localhost:38100`.

The Jaeger UI will be available at `http://localhost:37100`.

Press `Ctlr+c` to stop tailing the container logs and run the following docker command to stop the show case:

```shell 
docker compose down
```

