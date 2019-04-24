# Markdown-Template

Templates for writing Markdown-Files for Product documentation.
<!-- 
#### THE FOLLOWING POINTS MUST BE NOTED WHILE USING THIS TEMPLATE

1. FOR BETTER UNDERSTANDING ON WRITING MARKDOWN FILES SUITED FOR PRODUCT DOCUMENTATION, READ THE `Guidelines.md` FILE.

2. FOLLOW THE TEMPLATES STRICTLY.

3. NAMING CONVENTIONS USED IN THIS TEMPLATES FOR `FILES`, `FOLDERS` AND `HEADERS` MUST BE FOLLOWED.

4. ASIDE MODIFYING THE TEMPLATES TO SUIT YOUR DOCUMENATION AND ADDING NECESSARY INFORMATION, DO NOT REMOVE SYMBOLS FROM THE MARKDOWN TEMPLATES WHILE MAKING CHANGES AS THESE SYMBOLS ARE NECESSARY FOR PROPER RENDERING. -->

### Editing the templates

After successfully setting up and running the documentation server locally, you can now edit the Markdown files (templates) to suit your documentation.

***All product documentation must follow the following format:***

1. Create a folder named after the product to be documented in the docs folder which is located in the source folder.
2. Create an `index.html.md` file following the template provided inside the folder created which will serve as the base file for the product documentation.
3. All other Markdown files created such as the API documenation, notes should be stored in the `includes` folder following the naming convention used in this template.`

***Note the following***.

1. The templates are located in the `docs` and `includes` folders which could be found in the `source` folder.
2. This documentation server allows you to optionally separate out your docs into many files...just save them to the includes folder and add them to the top of your index.html.md's frontmatter. Files are included in the order listed. For this template, we have the following files `_productName-API documentation.md`,`_productName-codes.md`,`_productName-errors.md`,`_productName-notes.md` stored in the includes folder, which are then referenced in the `includes` section of the `index.html.md`(the base file for the product documentation) file for `productName`(the base folder for the product documentation) documentation folder.
3. Follow the templates strictly.
4. Naming conventions used in this template for files, folders and headers must be followed.
5. Aside modifying the templates to suit your documentation and adding necessary information, do not remove symbols from the markdown templates while making changes as these symbols are necessary for proper rendering.
6. Language name must be specified at the head of each code block.
7. While writing the Markdown files, do not use `html tags` for headers.
8. visit https://blog.ghost.org/markdown/ for more information on writing markdown files.