# python--file-handling
##modes in files:
    𝐫--open an existing file for read operation. If the specified file does not exist, we will get 𝐅𝐢𝐥𝐞𝐍𝐨𝐭𝐅𝐨𝐮𝐧𝐝𝐄𝐫𝐫𝐨𝐫.
          𝐫𝐞𝐚𝐝(𝐧)-- to read 'n' characters from the line.
          𝐫𝐞𝐚𝐝𝐥𝐢𝐧𝐞()-- to read only one line.
          𝐫𝐞𝐚𝐝𝐥𝐢𝐧𝐞𝐬()-- to read all lines in a list.
    𝐰--open an existing file for write operation. If the file is having a data, then it will be overridden. If the file is not    existed,     then this mode will create the file.
    𝐚-open an existing file for append function. It wont override the existing the data. If the file does not existed, mode will create a     new file.
    𝐫+ -- to read and write the data in to the file. The previous file will not be deleted. The file pointer will start from the first         line.
    𝐰+ -- to write and read the data. It will override the existing the data.
    𝐚+ -- to append and read the data from the file. It wont override existing data.
    𝐱 -- To open a file in exclusive creation mode for write operation. If the file is already exists then will get 𝐅𝐢𝐥𝐞𝐄𝐱𝐢𝐬𝐭𝐬𝐄𝐫𝐫𝐨𝐫.
    *** If the modes are suffixed with "b" then it represents binary file.****
    ** Advantage of "with" statement is no need of closing the file after all the operations are done, will close it explicitly***
    **tell() is a method which can be used to tell the current point of the cursors position. position starts at 0 like string index.
    **seek() is a method to move cursors position to specified location.(f.seek(offset,fromwhere))
    **Os.path.isfile(fname)--(checks whethere the file contains in the directory or not)
    
