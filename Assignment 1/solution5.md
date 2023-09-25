# Solution

## DOCTYPE declaration in HTML
-  The Document Type Declaration (DTD) in HTML is used to specify the version of HTML being used in a web document. 
- It serves as an instruction to the web browser regarding how to interpret and render the HTML content. 
- All HTML documents must start with a `<!DOCTYPE>` declaration.
- In HTML 5, the declaration is simple:
         
         <!DOCTYPE html>

   - In this declaration:
      - **<!DOCTYPE> :** This is the document type declaration tag.
      - **html :** It specifies the version of HTML being used. In this case, html represents HTML5, which is the latest and most widely used version of HTML.


- In older documents (HTML 4 or XHTML), the declaration is more complicated because the declaration must refer to a DTD (Document Type Definition).

   - HTML 4.01:

         <!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01 Transitional//EN" "http://www.w3.org/TR/html4/loose.dtd">

      - In this declaration:DTD declaration specific to HTML 4.01 Transitional. It provides information about the document's version and type.     

   - XHTML 1.1:

         <!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.1//EN" "http://www.w3.org/TR/xhtml11/DTD/xhtml11.dtd">
