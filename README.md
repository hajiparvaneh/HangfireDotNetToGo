# HangfireDotNetToGo

This is a sample .NET 7 project that demonstrates how to integrate Hangfire for job scheduling and uses PostgreSQL as the backend to store Hangfire jobs.

## Getting Started

### Prerequisites

Before you start, make sure you have the following prerequisites installed on your development environment:

- [.NET 7 SDK](https://dotnet.microsoft.com/download/dotnet/7.0)
- [Docker](https://www.docker.com/get-started)
- A PostgreSQL database running locally or in a Docker container (if you're not using the Docker setup)

### Running the Application

#### 1. Https: Run in IDE

1. Clone this repository to your local machine.

2. Open the project in your preferred IDE (e.g., Visual Studio).

3. Make sure you have a PostgreSQL database set up and running. You can use a local PostgreSQL server or run one in a Docker container.

4. Update the connection string in the appsettings.json file to point to your PostgreSQL database.

5. Build and run the application. Hangfire jobs will be scheduled and managed using the PostgreSQL database.

#### 2. Docker: Web and DB on Docker

1. Clone this repository to your local machine.

2. Ensure you have Docker installed and running.

3. Open a terminal and navigate to the project directory.

4. Run the following command to start the application along with a PostgreSQL database in Docker containers:

   ```bash
   docker-compose up
   ```
This will start both the web application and the PostgreSQL database in Docker containers. Hangfire jobs will be managed using the PostgreSQL database within the Docker container.


## Contributing
Feel free to contribute to this project by creating pull requests or reporting issues.

## License

This project is open source and free to use. You are welcome to use, modify, and distribute it without any licensing restrictions. Enjoy! ??