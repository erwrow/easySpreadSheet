# easySpreadSheet
An easy to implement <a href="https://erwrow.github.io/easySpreadSheet/ejemplo.html">spreadsheet</a> for javascript

To use this code, just copy the function "crearTabla" and assign it to a variable and if needed just chage the properties of the table, you must parse the following data to it:<br><br>
*A prefix ID (this must be the same ID of the element where you are going to append the table).<br>
*An array of arrays (or objects) for the header.<br>
*An array of arrays (or objects) for the body.<br>
*A properties object that tells the spreadsheet how to behave.<br><br>

The properties are fixed, where the programmer can enable or disable whenever they want, but now there some properties that can be changed by the user (if this is enabled).<br>
To generate the table just call the function "generarTablaEditable" associated with the objetc to your variable.
