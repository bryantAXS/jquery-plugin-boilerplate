# jQuery Plugin Boilerplate.

This is not my code, it was just so great I needed to save it somewhere.  All the credit goes to Stefan Gabos (http://stefangabos.ro/jquery/jquery-plugin-boilerplate-oop/)

## Usage

	$(document).ready(function() {

    // create a new instance of the plugin
    var myplugin = new $.pluginName($('#element'));

    // call a public method
    myplugin.foo_public_method();

    // get the value of a public property
    myplugin.settings.property;

	});