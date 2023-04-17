# WebsiteLoaders

WebsiteLoaders
WebsiteLoaders is a collection of loading animations built with HTML, CSS, and JavaScript. These loaders can be used to enhance the user experience while waiting for your website to load.

Demo
Check out the demo page here.

Installation
To use these loaders, you can download the source files from the src directory, or include the CSS and JavaScript files from the dist directory in your project.

html
Copy code
<link rel="stylesheet" href="path/to/websiteloaders.min.css">
<script src="path/to/websiteloaders.min.js"></script>
Alternatively, you can install WebsiteLoaders using npm:

bash
Copy code
npm install websiteloaders
Usage
To use a loader, simply add the loader's CSS class to an HTML element. For example, to use the wl-double-ring loader:

html
Copy code
<div class="wl-loader wl-double-ring"></div>
You can customize the color and size of the loader using CSS variables. For example:

css
Copy code
.wl-loader {
  --loader-color: red;
  --loader-size: 50px;
}
Contributing
Contributions are welcome! If you find a bug or have an idea for a new loader, please open an issue or submit a pull request.
