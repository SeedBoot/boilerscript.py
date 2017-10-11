# boilerscript.py
An interactive python script that allows you to create a front end work space comprising of HTML/ PHP &amp; CSS/SCSS

It first generates style and script directories, and a JS file. The script will prompt you to choose between HTML or PHP. It will then prompt you to choose between CSS or SCSS. If you've chosen SCSS, it will ask whether you want it to run SASS to listen to the import:export folders generated. 

Now you can get :fire: even quicker! :metal:

## File Hierarchy

~~ = possible path

```
.
|
|--index.php / index.html
|
|~~includes
|  |--head.php
|  |--foot.php
|
|--script
|  |--script.js
|
|~~style
   |--style.css
|
|~~style
   |--export
   |
   |--import
      |--_var.scss
      |--style.scss
```

## Instructions
- Ensure you have SCSS/ SASS installed
- Ensure you have the latest version of Python installed.
- Place this script and the 'asset' folder in `C:/script` or similar, and add this directory to the PATH.
  - Point your terminal to the desired directory
  - Type `boilerscript.py` into the terminal, kick back and relax for those five minutes you just saved... :sunglasses:
- Or, if you're feeling 'lazy': place this script and the folder into the root of your project.
  - Open your IDE of choice, comment out the instances of ROOT variable and "ROOT + ".
  - Double click on `boilerscript.py`, kick back and relax for those five minutes you just saved... :boom:
