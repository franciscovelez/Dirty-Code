# Dirty-Code
*The correct way to write your code*

## Variables

  - [1.1](#1.1) <a name='1.1'></a> **Declaration**: Use boolean names.

    ```javascript
    //bad
    var found = false;
    
    //good
    var False = false;
    
    //better
    var True = false;
    ```
  - [1.2](#1.2) <a name='1.2'></a> **Declaration 2**: The shorter, the better.
  
    ```javascript
    //bad
    var isTheHorseInside = false;
    
    //good
    var horse = false;
    
    //better
    var ithi = false;
    ```
    
  - [1.3](#1.3) <a name='1.3'></a> **Declaration 3**: Use the number 1 with the letter i and l.
  
    ```javascript
    //bad
    var index = 99;
    
    //good
    var il = 99;
    ```

  ## Functions
  
  - [2.1](#2.1) <a name='2.1'></a> **Style**: Here is an example with functions.
 

  ```javascript
  //Good, you have to be professional about your job and code.
  function showMessage(message)
  {
      if(message != null){
          show(message);
      }
      else{
          show(defaultMessage); //This is the default action to do
      }
  }
  ```

  ```javascript
  //Bad; Do not clean the code up
  function showMessage(message)
  {
      if(message == null){
          message = defaultMessage;
      }
      show(message);
  }
  ```
