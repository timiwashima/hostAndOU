![image](https://github.com/timiwashima/hostAndOU/assets/52045865/c25c4da7-e64e-486b-86da-4c65a48742bf)

If you have a list of the hosts, the hosts must have either single quotes, or double-quotes around them.  If they're already comma-separated, this will be easy to do in Excel.

![image](https://github.com/timiwashima/hostAndOU/assets/52045865/762f82f8-8d8f-49bd-8b9c-83108a2979ae)

![image](https://github.com/timiwashima/hostAndOU/assets/52045865/66900c23-b434-4cf8-96a4-d24c16caa489)

Select the cells, in the Home tab, select Format→Format Cells.  Choose Custom, and in the Type text box, enter: '@'.

![image](https://github.com/timiwashima/hostAndOU/assets/52045865/e85cf404-c4e4-4616-9512-426c8ba3d9a8)

![image](https://github.com/timiwashima/hostAndOU/assets/52045865/cb75d7cd-5112-4984-a029-0b04db32e433)

If the list of hosts you have are in a column instead of a row, select the individual cells in the column (not the column itself) and copy them, make a new Excel file, or a new sheet.  Click the paste icon, and choose Transpose Paste.

![image](https://github.com/timiwashima/hostAndOU/assets/52045865/e7409e8c-edc0-4097-b5cc-ae0cbb278377)

![image](https://github.com/timiwashima/hostAndOU/assets/52045865/9d879652-3140-4aab-a257-d9e77948560f)

Save the file and open it with a text editor.  The hostnames should now all have quotes around them, and comma-separated.  Copy the text.

Create a variable in Powershell (in this script, it's default computers) and make it equal to the pasted comma-separated, enclosed in single-quotes hostnames.
Run the script.  You will get a table output like below (results obfuscated):

![image](https://github.com/timiwashima/hostAndOU/assets/52045865/ba3ba3dd-be85-46dc-8c22-6dff7627636a)
