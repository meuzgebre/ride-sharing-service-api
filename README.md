# Ride Sharing Service API

This is an open source API for a ride sharing service built using Node.js, Express.js and MySQL. It provides various endpoints for users to create, view, update and delete rides.

### Installation

To install the required modules, run the following command:

```
npm install
```

### Configuration

To configure the database connection, create a .env file and add the following variables:

```
DB_HOST=localhost
DB_USER=root
DB_PASSWORD=password
DB_NAME=rideshare
```

### Usage

To start the server, run the following command:

```
npm start
```

he API endpoints are available at http://localhost:3000/api.

### API Endpoints

``` GET /rides ``` - get all rides

``` POST /rides ```  - create a new ride

``` GET /rides/:id ``` - get a ride by ID

``` PUT /rides/:id ``` - update a ride by ID

``` DELETE /rides/:id ``` - delete a ride by ID


### Contributing

Contributions to this project are welcome! To contribute, please follow these steps:

Fork this repository
1. Create a new branch (git checkout -b feature/my-new-feature)
2. Make your changes
3. Commit your changes (git commit -am 'Add some feature')
4. Push to the branch (git push origin feature/my-new-feature)
5. Create a new Pull Request

### Purpose

The purpose of this open source project is to provide a reusable backend API for ride sharing services. By making this code available to the community, we hope to promote the development of more affordable and accessible ride sharing services.

Please ensure that your code adheres to the existing coding standards and includes appropriate unit tests.

## License

This project is licensed under the Creative Commons Attribution-ShareAlike 4.0 International Public License - see the [LICENSE](LICENSE) file for details.
