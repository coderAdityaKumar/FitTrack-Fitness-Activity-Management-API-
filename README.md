# Fitness Monolith

Minimal Spring Boot monolith for fitness-related services (backend only).

## Build & run

Using the Maven wrapper:

Unix / macOS
```
./mvnw clean package
./mvnw spring-boot:run
```

Windows (PowerShell / CMD)
```
mvnw.cmd clean package
mvnw.cmd spring-boot:run
```

## Tests

Run unit tests:

```
./mvnw test
```

## Notes
- This repository now includes a `.gitignore` to exclude `target/`, IDE files, OS artifacts, logs and temporary files.
- Keep source files in `src/` and commit `pom.xml`, `mvnw`, and `.mvn/wrapper` so the project builds on CI and other machines.
