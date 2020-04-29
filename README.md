# Google-Scholar-Web-App-DB

A web-app to visualize the different researchers on Google Scholar along with their relationships to other researchers.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. The instructions are assuming you are using a macintosh machine. There should be similar commands for windows and linux.

### Prerequisites

You will need to have npm, sqlite3, and Neo4j installed.

```
brew install npm
brew install sqlite3
```
https://neo4j.com/download/


### Installing

Go to the api directory and install the dependencies
```
cd api
npm install
```

Go to the react-google-scholar directory and install the dependencies 
```
cd react-google-scholar
npm install
```

Create a new project in Neo4j and set the password to 'cs411'. Move the /neo4jdata/ csv files into your projects import folder and run the cypher to import the database. 

## Running Project

Go to the api directory and run the graphql server
```
cd api
npm start
```

Go to the Neo4j Desktop app and run the Neo4j server


Go to the react-google-scholar directory and run the react program
```
cd react-google-scholar
npm start
```

After doing this http://localhost:3000/ will open up in the default browser and you should be able to access the project.

## Built With

* [React.js](https://reactjs.org/) - The web framework used
* [Graphql](https://graphql.org/) - Backend 
* [Apollo](https://www.apollographql.com/) - Used to connect the graphql server with react

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

