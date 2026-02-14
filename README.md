# edusevapp

Java backend project (Gradle) for an educational context. Domain models (User, Teacher, Region, EducationalUnit, etc.), JPA repositories, and Spring Boot–style application configuration.

## Tech stack

- **Java** · **Gradle**
- **Spring Boot** (see `build.gradle` / `pom.xml` for dependencies)
- JPA / repositories, `application.properties` for configuration

## Requirements

- JDK 11+
- Gradle (or use the wrapper: `gradlew`)

## Setup & run

1. Clone the repository.
2. Configure `src/main/resources/application.properties` (and optional `application-dev.properties`) if needed.
3. Build and run:
   ```bash
   ./gradlew build
   ./gradlew bootRun
   ```
   Or open the project in IntelliJ IDEA and run the main application class.

## Project structure

- `src/main/java/gr/aueb/cf/edusevapp/` — main application, models, repositories
- `src/main/resources/` — `application.properties`, optional profiles
- `src/test/` — tests

## License

MIT
