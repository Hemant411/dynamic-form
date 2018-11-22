# dynamic-form
jQuery Dynamic Forms
====================

Plugin to dynamically create forms. The plugin has been originally designed to run on the server (in Node.js, using [express-jsdom](http://github.com/fgnass/express-jsdom)), but of course works perfectly well in the browser, too.
![Screenshot](https://raw.githubusercontent.com/Hemant411/dynamic-form/master/screenshot.png)

## Usage

  $("#dynamic_form").dynamicForm("#dynamic_form","#plus5", "#minus5", {
		        limit:10,
		        formPrefix : "dynamic_form",
		        normalizeFullForm : false
		    });
