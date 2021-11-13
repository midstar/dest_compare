# Destination Comparison 

A generic HTML/CSS/Javascript page for displaying comparison of 
destinations. The properties of the destinations are defined in
a separate database which is dynamically loaded based on the
URL parameter called "data". 

Features:

* Compare destination properties in a table or in graphical plot
* View the destinations on a map
* View the distance to each destination based on your current location
* Full localization support

# How it works

Localization data, destination properties and all destinations are
defined in a separate database. The database is a javascript file
containing javascript objects (key/value pairs).

By default the database is called data.js and located in the same
directory as the html page (index.html). However, the database
file might be located elsewhere based on the "data" URL parameter.

# Example

This software was originally written to compare different ski
areas in Sweden. 

Check it out [here on GitHub Pages](https://midstar.github.io/sweski/html/index.html).
