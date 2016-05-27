## Template was created using - bootstrap3-jade-node-express-grunt

## Install dependencies

+ install [NodeJS] (globally)
+ install [NPM] (globally)
+ install [Grunt] (globally)

## How to run the app

+ Install the module using `npm install` command (locally, a node_modules directory will be created)
+ Start the server using the `grunt` command
+ open [http://localhost:3001/](http://localhost:3001/) home page

## Documentation
+ start the server using `grunt`
+ click on the links leading you to the [Bootstrap] templates translated into Jade
+ Use the *.jade files into your projects !

+ how did we convert the html into jade
    + We use [html2jade] to translate automatically the html into a jade file
    + Remove the characters as Jade complains as it believes it has to interpret the code  `=================================================`
    + replace inside the jade file the path to the JS and CSS files from [Bootstrap Twitter]:  `../..` with the parameter `#{pathToAssets}`
    + change the link to the custom made CSS made for each template stored under the `bootstrap-3.0.0/examples/` directory :  `#{pathToSelectedTemplateWithinBootstrap}`

