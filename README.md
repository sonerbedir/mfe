<h3>Aim</h3>

This application has been developed using Webpack's Module Federation Plugin. The purpose here is to create Microfrontend applications that operate independently with the Module Federation Plugin. It has been deployed from the production environment using Amazon AWS S3 Bucket.


<h3>Setup</h3>
To set up the applications in the local environment:

To begin, navigate to each application folder, and install dependencies using either npm install or yarn install, depending on your preference.

Each application carries its own set of dependencies; therefore, it is necessary to install them independently. The applications operate in isolation within their respective roots. When accessing port 8080, you will observe that the Container and Marketing applications run simultaneously. Going to port 8081 will demonstrate that the Marketing application can operate independently. Essentially, we are testing the concurrent operation of independent applications working together.

Marketing: localhost:8081
Container: localhost:8080

production: https://d1c528h86wppvj.cloudfront.net/
