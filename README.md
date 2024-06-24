# Learn-DataSources-APIs

## Description

API collection to do CRUD operations on data sources

## Installation

### Postman

Postman is a collaboration platform for API development. It simplifies each step of building an API and streamlines collaboration, enabling you to create better APIs faster.

To install Postman, follow these steps:

1. Visit the [Postman website](https://www.postman.com/downloads/).
2. Download the version suitable for your platform.
3. Run the installer.

## API List

The `API_Export.json` file contains the following APIs:

- `GET /learn/api/public/v1/dataSources`: Returns a list of data sources.
- `POST /learn/api/public/v1/dataSources`: Creates an data sources.
- `GET /learn/api/public/v1/dataSources/{dataSourceId}`: Returns the data source with the specified Id.
- `DELETE /learn/api/public/v1/dataSources/{dataSourceId}`: Deletes an data source with the specified Id.
- `PATCH /learn/api/public/v1/dataSources/{dataSourceId}`: Updates an data source with the given Id.

## Usage

After importing the `API_Export.json` file into Postman, you can use the APIs by sending requests to them. Ensure to set up the environment variables correctly:

- `$LEARN_DOMAIN`: Learn Server FQDN
- `$APP_KEY`: Your application key here
- `$APP_SECRET`: Your application secret here
- `$ACCESSTOKEN`: Obtain the access token from the API request '/learn/api/public/v1/oauth2/token' using the above values and replace the variable
- `$DATASOURCE_ID_GET`: Id of the data source to be searched
- `$DATASOURCE_ID_DELETE`: Id of the data source to be deleted
- `$DATASOURCE_ID_PATCH`: Id of the data source to be updated