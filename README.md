# File Metadata Microservice

A microservice that takes a local file and uploads it onto the server, storing it in a folder designated in dotenv as process.env.ONLINE_STORAGE

Instructions for building your project can be found at https://www.freecodecamp.org/learn/apis-and-microservices/apis-and-microservices-projects/file-metadata-microservice

## [Run from repl.it](https://boilerplate-project-filemetadata.hurricanemark.repl.co)

## [Git source](https://github.com/hurricanemark/microservice-file-metadata.git)


## Optionally, clone from [github]((https://github.com/hurricanemark/microservice-file-metadata.git)) and run from the terminal (regardless, you must setup and configure your own mongodb database in place of my *process.env.ONLINE_STORAGE where you define server side folder name*)!:

```
npm install

npm start
```

## Application features and constraints

Use the multer npm package to handle file uploading.

You should provide your own project, not the example URL.

You can submit a form that includes a file upload.

The form file input field has the name attribute set to upfile.

When you submit a file, you receive the file name, type, and size in bytes within the JSON response.