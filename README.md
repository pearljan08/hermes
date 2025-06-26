# My Monorepo

This is a Yarn monorepo setup that contains multiple packages. The structure of the repository is designed to facilitate the development and management of related packages in a single repository.

## Packages

- **package-a**: This package contains functionality for greeting. It exports a function `hello` that returns a greeting message.
- **package-b**: This package complements package-a by exporting a function `world` that returns a different greeting message.

## Getting Started

To get started with this monorepo, follow these steps:

1. **Install Dependencies**: Run the following command to install all dependencies for the monorepo and its packages:
   ```
   yarn install
   ```

2. **Building Packages**: Each package can be built independently. Navigate to the desired package directory and run:
   ```
   yarn build
   ```

3. **Testing Packages**: To run tests for a specific package, navigate to the package directory and execute:
   ```
   yarn test
   ```

## Structure

The repository is structured as follows:

```
my-monorepo
├── packages
│   ├── package-a
│   └── package-b
├── package.json
├── yarn.lock
├── README.md
└── yarn.workspaces.json
```

## Contributing

Contributions are welcome! Please feel free to submit a pull request or open an issue for any enhancements or bug fixes.

## License

This project is licensed under the MIT License.