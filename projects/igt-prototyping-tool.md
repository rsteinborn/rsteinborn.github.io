# IGT Prototyping Tool

## Description

This project is a Java-based tool for prototyping medical Image Guided Therapy (IGT) applications. It provides basic functionalities for IGT, including tracker connection using OpenIGTLink, and allows for convenient implementation of IGT functionalities using reported information.

## Key Features

- Tracker connection using OpenIGTLink
- Basic IGT functionalities
- OpenCV and OpenIGTLink integration
- Gradle build system

## Technologies Used

- Java (minimum version 11, supports LTS versions up to 17)
- Gradle
- OpenCV
- OpenIGTLink

## Development History

This tool started as a student project and is currently actively maintained by various students of THU (Technische Hochschule Ulm).

## Building and Running

To build and run the project:

For Windows:

```bash
./gradle.bat build # builds the project
./gradle.bat run # runs the main program
```

For Linux:

```bash
./gradlew build
./gradlew run
```

## Coding Guidelines

The project uses Checkstyle to enforce basic style checks:

- Use spaces for indentation, not tabs
- Don't use Umlaut characters
- End files with a new line
- Don't leave trailing spaces at the end of a line

The project is set to Java 11 language level for compatibility with older Java versions.

## Contribution

When cloning this repository, make sure to contribute changes to this repository and not the parent repository.

## GitHub Repository

[Link to the project repository](https://github.com/rsteinborn/IGTPrototypingTool)

## License

This project is licensed under the Apache-2.0 license.
