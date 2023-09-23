### Solution:

### Purpose of comments in HTML : 
- The comment tag ( <!-- Comment--> ) is used to insert comments in the HTML code.
- It is a simple piece of code that is ignored by web browsers i.e., not displayed by the       browser. 
- It helps the coder and reader to understand the piece of code.
- It is useful to understand steps of the complex code.
- The comment tag is helpful while the debugging of codes.    

**Syntax:** <!--Write your Comments here -->

- Types of Comment:
    - Single-line comment
    - Multi-lines comment
    - Using <comment> tag

     **Single-line comment :**  Single line comment is given inside the ( <!–  comment –> ) tag. 
     **Multi-lines comment :**  Multiple lines can be given by the syntax (<!– –>), Basically it’s the same as we used in single line comment, difference is half part of the comment (” –> “), is appended where the intended comment line ends. 
     **Using <comment> tag :** There used to be an HTML <comment> tag, but currently it is not supported by any modern browser.

    ### Example :

          <!DOCTYPE html>
          <html lang="en">
          <head>
          <meta charset="UTF-8">
          <meta name="viewport" content="width=device-width, initial-scale=1.0">
          <title>Example of Comments</title>
          </head>
          <body>
          <!--This is single line comment -->
          <h1>This is single line comment</h1> 

          <!-- This is
            multi-line
           comment -->
     
          <h2>This is multi-line comment</h2>

          <comment>This is multi-line
                   comment
          </comment>

          <h2>This is a comment using comment tag.</h2>
          </body>
          </html>
        