# Index:
1) [**Introduction to JavaScript**](#Introduction-to-JavaScript)
   * [**JS With HTML**](#JS-With-HTML)
   * [**Where can I use JavaScript?**](#Where-can-I-use-JavaScript)      
   * [**JS Functions and Events**](#JS-Functions-and-Events)
   * [**External JavaScript**](#External-JavaScript)      
   * [**External JS Advantages**](#External-JS-Advantages)      
      
      
      
      

# JS_Tutorial_Example
## Introduction to JavaScript <img src="http://innovativeteams.net/wp-content/uploads/2017/01/jsLogo.png" alt="JavaSript" width="30" height="30"/> 
<!-- <img src="http://innovativeteams.net/wp-content/uploads/2017/01/jsLogo.png" alt="JavaSript" width="30" height="30"/> -->
### JS With HTML:
* Can be find **HTML** element in **JavaScript** by **ID_Name** of element.
    - **Ex:**
        ```html 
        <!DOCTYPE html>   
          <html>
            <head>
            </head>
            <body>
                <button onclick="document.getElementById(ID_Name)";></button>
            </body>
          </html>
      ```        
* Can be change **HTML** Element content by **innerHTML**.  
    - **Ex:**
        ```html 
        <!DOCTYPE html>   
          <html>
            <head>
            </head>
            <body>
                <button onclick="document.getElementById(ID_Name).innerHTML = "Value Changed";></button>
            </body>
          </html>
      ```        
*	Can be use **JavaScript** in **HTML** element by **onclick = "document.getElementById()"**
    - **Ex:**
        ```html 
        <!DOCTYPE html>   
          <html>
            <head>
            </head>
            <body>
                <button onclick="document.getElementById()";></button>
            </body>
          </html>
      ```    
*	Can be change **CSS** Style of **HTML** Element in **JavaScript** by **.style.ElementNameOfCSS="value"**.
    - **Ex:**
        ```html 
        <!DOCTYPE html>   
          <html>
            <head>
            </head>
            <body>
                <button onclick="document.getElementById(“Id_Name”).style.element_of_CSS = "value";></button>
            </body>
          </html>
      ```    
*	Can be set Image source in **HTML** Element by **.src="imageSource"**.
    - **Ex:** ***<HTMLElement onclick=></HTMLElement>***.
        ```html 
        <!DOCTYPE html>   
          <html>
            <head>
            </head>
            <body>
                <button onclick="document.getElementById("Id_Name").src="pathOfIMG";></button>
            </body>
          </html>
      ```        
## Where can I use JavaScript?

* In **HTML** Element by **onclick** attribute.
    - **Ex:**
        ```html 
        <!DOCTYPE html>   
          <html>
            <head>
            </head>
            <body>
                <button onclick="document.getElementById(ID_Name).innerHTML = "Value";></button>
            </body>
          </html>
      ```     
*	OR by define **Script** Tag in **Body** or **Head** Elements of **HTML** or in **Both**.
    - **Ex: Using in body tag:**
        ```html 
        <!DOCTYPE html>   
          <html>
            <head>
            </head>
            <body>
                <script>
                    document.getElementById(Id_Name).innerHTML=”value”;
                </script>
            </body>
          </html>
      ``` 
   - **Ex: using in head tag:**
       ```html 
        <!DOCTYPE html>   
          <html>
            <head>
                <script>
                    document.getElementById(Id_Name).innerHTML=”value”;
                </script>            
            </head>
            <body>
            </body>
          </html>
     ```       
*	Can be use **Script** Tag in External file which have extension **.js**. 

      ***Note: 1) Placing scripts at the bottom of the body element improves the display speed, because script interpretation slows down the display.*** <br/>
            ***2) Can be place more than one of script tag in a HTML doc.***

## JS Functions and Events:
  *	**Function:**
    -	Is block of **JavaScript** Code, execute when called.
     - **Ex:**
         ```html 
          <!DOCTYPE html>   
            <html>
              <head>
                  <script>
                          function myFun(){
                              document.getElementById(Id_Name).innerHTML = “value”;
                          }
                  </script>            
              </head>
              <body>
              </body>
            </html>
       ```             
       
## External JavaScript

*	To use **Script** from an external file, put the name of the **Script** file in ***src*** attribute of a **Script** tag.
*	Can be use money of external **Script**  in **HTML** Doc by ***src*** attribute of **Script** tag, but should be different name of external **Script**.
  -	**Ex:** 
       ```html 
        <!DOCTYPE html>   
          <html>
            <head>         
            </head>
            <body>
              <script src=”script1.js”></script>
              <script src=”script2.js”><script>                
            </body>
          </html>
     ```  


***Note: External script cannot use script tags***.

### External JS Advantages:
* **Placing scripts in external files has some advantages:**
  - ***It separates HTML and JS code.***
  - ***It make HTML and JS code easier to read and maintain.***
  - ***Cached JS files can speed up page load.***

