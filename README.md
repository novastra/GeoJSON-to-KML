Google Maps JSON to KML converter
==========

Convert Google Maps JSON from <a target="_blank" href="https://takeout.google.com/settings/takeout">Google Takeout</a> to a KML file that you can use for Google MyMaps for instance.

The code is 100% client-side using recent Javascript blob file handling. 

<h3>Demo</h3>
A working demo is available <a href="http://novastra.net/demo/JSONtoKML">here</a>

<h3>Description</h3>
The file input creates a blob for the JSON file with a fake local URL. 

When ready, an AJAX request is made to access the JSON content. 

Then it can be converted to KML escaping special chars in the process.

<h3>Todo list</h3>
The code is quite a quick & dirty solution for Google Maps takeout JSON file. Many improvements can be made.
<ul>
<li>Implement automatic recursive analysis on the component of the JSON to have all possible GeoJSON features starting by the lowest level of information</li>
<li>Add a check on the blob object file to validate the JSON structure</li>
</ul>
