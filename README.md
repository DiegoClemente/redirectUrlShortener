# Redirect Url Shortener

Redirect Url Shortener is a Java-based URL shortener service designed to work with AWS Lambda and S3.

## Project Overview

This project aims to provide a simple yet efficient URL shortening service. It utilizes AWS Lambda for serverless computing and S3 for storage, making it a scalable and cost-effective solution.

## Technologies Used

- Java 17
- Maven
- AWS Lambda
- Amazon S3
- Jackson (for JSON processing)
- Lombok (for reducing boilerplate code)
- Log4j2 (for logging)

## Project Structure

```
RedirectUrlShortener
├── pom.xml
└── src
├── main
│   ├── java
│   │   └── com
│   └── resources
└── test
└── java
```

## Dependencies

The project uses the following main dependencies:

- `aws-lambda-java-core` (version 1.2.1)
- `aws-lambda-java-log4j2` (version 1.4.0)
- `aws-java-sdk-s3` (version 2.17.106)
- `lombok` (version 1.18.34)
- `jackson-databind` (version 2.12.3)

## Building the Project

To build the project, use the following Maven command:

```bash
mvn clean package
```

This will create a JAR file that can be deployed to AWS Lambda.

## Configuration

Make sure to configure your AWS credentials properly to allow the Lambda function to interact with S3.

## Contributing

Contributions to the RedirectUrlShortener project are welcome. Please feel free to submit a Pull Request.

<h2 id="license">📜 License</h2>
<p>Distributed under the MIT License. See <a href="LICENSE">LICENSE</a> for more information.</p>

<footer>
        <p>💻 Made with ❤️ by Diego Clemente</p>
</footer>