[![Build Status](https://dev.azure.com/Mengly123123/Web2/_apis/build/status%2FWeb2-ASP.NET%20Core%20Pipeline?branchName=master)](https://dev.azure.com/Mengly123123/Web2/_build/latest?definitionId=2&branchName=master)

# .NET6 Tablet Web Service

This is a sample project that demonstrates the implementation of a Web API in .NET6. The project is built using the latest version of .NET, offering powerful features and improvements.

## Getting Started

1. Clone the repository to your local machine:

```console
cd project-directory
```

2. Install the .NET6 SDK from [here](https://dotnet.microsoft.com/download/dotnet/6.0).

3. Navigate to the project directory:

```console
cd project-directory
```

4. Build the project:

```console
dotnet build
```

5. Run the project:

```console
dotnet run
```

The Web API will be hosted locally on `https://localhost:5001`. You can test the API endpoints using a tool like [Postman](https://www.postman.com/) or by sending HTTP requests directly in htpp file in each controller.

## Project Structure

The project follows a standard structure for a .NET Web API project:

- **Controllers**: Contains the API controllers that handle incoming requests and generate responses.
- **Models**: Defines the data models used for input and output in the API.
- **Services**: Encapsulates the business logic and operations performed by the API.
- **Data**: Handles data access and persistence, interacting with the database or external services.
- **Utils**: Includes utility classes or functions used by the API.

## API Endpoints

The sample project includes the following endpoints:

- **GET /api/users**: Retrieves a list of all users.
- **GET /api/users/{id}**: Retrieves details of a specific user by their ID.
- **POST /api/users**: Creates a new user based on the request body.
- **PUT /api/users/{id}**: Updates an existing user by their ID.
- **DELETE /api/users/{id}**: Deletes a user by their ID.

Please note that these endpoints are provided as examples and may not cover all possible scenarios or include all necessary error handling.

## Dependencies

The project includes the following dependencies:

- ASP.NET Core 6.0
- Newtonsoft.Json (optional: can be replaced with the built-in System.Text.Json)
- Any additional dependencies can be found in the `csproj` file.

## Testing

The project includes unit tests to ensure the correctness of the implementation. You can run the tests using the following command:

## Contributing

Contributions to the project are welcome! If you find any bugs, have suggestions, or would like to add new features, please feel free to open an issue or submit a pull request.

## License

This project is licensed under the [AMK License](LICENSE.md).
