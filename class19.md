## RegEx
- Regular Expressions is like the control f function but in python and it is way more powerful
- Regular expressions can contain both special and ordinary characters.
- Editing Code
- Verifying user input
- scraping the web

## shutil
- shutil helps in automating process of copying and removal of files and directories

### First you import shutil module 
- import shutil
   
### define the Source path
- source = "path/main.py"
   
### define the Destination path
- destination = "path/gfg/"
   
### Copy the content of the source to destination
- dest = shutil.copy(source, destination)
  
### Print path of the newly created file
print("Destination path:", dest)
