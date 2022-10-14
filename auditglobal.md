REMOVE THIS FILE AFTER YOU APPLY CHANGES


1. add please .gitignore files and add css directory there you shouldn't have css files in repository if you work on scss cause it is an output
to do it first delte css directory add commit to register your deletion and then add .gitingore file with css/* path rule to stop observe this directory and commit it

2. img/svg/icons etc should be moved in public directory not in the root of the project
3. JS directory -> first should be lowercases, sec rename it to scripts
4. i left you a comments in some files some of them are global like rem/em how to use it fixed dimensions min/max- height/width etc.
5. you dont understand fully responsive structure




Remember!!!!
1. section/article some big wrapper containers element 
2. container element if it is need it but is is not called .container it's more like div class="trade_container" trade_wrapper trade_block it can have different names but it just close some .rows togheter in this same order/direction flex-direction: column/row ;)
3. .row -> never use any class name here -> it's defined in grid.scss and never should be overwritten NEVER! it's important!
4. col -> -> never use any class name here or use very cerfully -> it's defined in grid.scss  and never should be overwritten NEVER! it's important!
------------------
5. content here you can add style whatever you want

so you seperate structure from content, in the content you have whole staff like p/h1/h2/buttons/forms etc. from the other hand
structure defines you the grid/responsive behaviour how elements inside of columns are going to move diffreintly according to device width/type.

so media queries @media in scss are applied only to content! Remember!


            
      