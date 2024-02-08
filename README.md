If you have a list of the hosts, the hosts must have either single quotes, or double-quotes around them.  If they're already comma-separated, this will be easy to do in Excel.
Select the cells, in the Home tab, select Format→Format Cells.  Choose Custom, and in the Type text box, enter: '@'.

If the list you have is not CSV formatted, or the cells are in a row instead of a column, select the individual cells in the column (not the column itself) and copy them, make a new Excel file, or a new sheet.  Click the paste icon, and choose Transpose Paste.
Save the file and open it with a text editor.  The hostnames should now all have quotes around them, and comma-separated.

Create a variable in Powershell (in this script, it's default hosts) and make it equal to the pasted comma-separated, enclosed in single-quotes hostnames.
Run the script.
