# Web Component - Image in the background of a website v.1.0.2

Place a full size image in the background of the website. [Demo](|http://edgarszagorskis.github.io/img-background/index.html)

## Usage

### For VanillaJS

Put the `<img-background>` web component on your website and include img-background.html, for example, after opening `<body>` tag:
   
    <body>
        <img-background src="path-to-your-image"></img-background>
        <link rel="import" href="./dist/img-background.html">
        <!--- rest of site --->
    </body>

#### For Polymer Project

Put the `<img-background>` web component on your website and include img-background-polymer.html, for example, after opening `<body>` tag:

     <body>
        <img-background src="path-to-your-image"></img-background>
        <link rel="import" href="../dist/img-background.html">
        <!--- rest of site --->
        <script src="//cdnjs.cloudflare.com/ajax/libs/polymer/0.2.3/platform.js"></script>
        <script src="//cdnjs.cloudflare.com/ajax/libs/polymer/0.2.3/polymer.js"></script>
        <link rel="import" href="./dist/polymer-project/img-background.html">
    </body>
    
## License

[MIT License](http://en.wikipedia.org/wiki/MIT_License)
