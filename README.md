![image](https://github.com/timiwashima/hostAndOU/assets/52045865/c25c4da7-e64e-486b-86da-4c65a48742bf)

If you have a list of the hosts, the hosts must have either single quotes, or double-quotes around them.  If they're already comma-separated, this will be easy to do in Excel.

![image](https://github.com/timiwashima/hostAndOU/assets/52045865/762f82f8-8d8f-49bd-8b9c-83108a2979ae)

Select the cells, in the Home tab, select Format→Format Cells.  Choose Custom, and in the Type text box, enter: '@'.

![image](https://github.com/timiwashima/hostAndOU/assets/52045865/66900c23-b434-4cf8-96a4-d24c16caa489)

If the list you have is not CSV formatted, or the cells are in a row instead of a column, select the individual cells in the column (not the column itself) and copy them, make a new Excel file, or a new sheet.  Click the paste icon, and choose Transpose Paste.
Save the file and open it with a text editor.  The hostnames should now all have quotes around them, and comma-separated.

Create a variable in Powershell (in this script, it's default hosts) and make it equal to the pasted comma-separated, enclosed in single-quotes hostnames.
Run the script.
