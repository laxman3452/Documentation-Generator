This package helps developers build next js /docs page without needing to build entire documentation page on their own so that developers only focus on data and information of their software products/API's.

# Documentation Generator

## Prerequisites

To use this package, ensure you have the following:
- A **Next.js** application.
- A **MongoDB** database using **Mongoose** ORM

To use this package, ensure you have installed the following:
-  **mongodb** **mongoose** package.

  
## Installation

Run the following command to install the package:
```sh
npm i documentation-generator
```

## Setup

1. Add your MongoDB connection URL to a `.env` file:
   ```sh
   mongoConnURI=your_mongodb_connection_url
   ```

2. Ensure your application is configured to use the `mongoConnURI` variable in database initialization.

## Usage

**Route to** your-domain/docs e.g (**localhost:3000/docs** or **domain.com/docs**) and customize docs.

## License

[MIT](LICENSE)
