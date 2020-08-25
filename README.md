# tasks
# 2020-aug-24.html
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta name="theme-color" content="#000000" />
    <style>body {
      font-family: Arial, Helvetica, sans-serif;
      background-color: black;
    }
    
    * {
      box-sizing: border-box;
    }
    .container {
      padding: 16px;
      background-color: white;
    }
    
    
    input[type=text], input[type=password] {
      width: 100%;
      padding: 15px;
      margin: 5px 0 22px 0;
      display: inline-block;
      border: none;
      background: #f1f1f1;
    }
    
    input[type=text]:focus, input[type=password]:focus {
      background-color: #ddd;
      outline: none;
    }
    
  
    hr {
      border: 1px solid #f1f1f1;
      margin-bottom: 25px;
    }
    
   
    .registerbtn {
      background-color: rgb(12, 12, 24);
      color: white;
      padding: 16px 20px;
      margin: 8px 0;
      border: none;
      cursor: pointer;
      width: 100%;
      opacity: 0.9;
    }
    
    .registerbtn:hover {
      opacity: 1;
    }
    
    
    a {
      color: dodgerblue;
    }
    
    .signin {
      background-color: #f1f1f1;
      text-align: center;
    }</style>
    <link rel="shortcut icon" href="./assets/img/favicon.ico" />
  
    <link
      rel="stylesheet"
      href="./assets/vendor/@fortawesome/fontawesome-free/css/all.min.css"
    />
    <link
      rel="stylesheet"
      href="https://cdn.jsdelivr.net/gh/creativetimofficial/tailwind-starter-kit/compiled-tailwind.min.css"
    />
    <title>first Task</title>
  </head>
  <body class="text-gray-800 antialiased">
   
    <div class="container mx-auto" style="background-image: image();">
  
      <div class="flex justify-between items-center py-4 bg-black">
        <div class="flex-shrink-0 ml-10 cursor-pointer">
          
          <span class="ml-1 text-3xl text-white font-semibold">OXO IT SOLUTIONS</span>
        </div>
       
        <ul class="hidden md:flex overflow-x-hidden mr-10 font-semibold">
          <li class="mr-6 p-1">
            <a class="text-white " href="#">Home</a>
          </li>
          <li class="mr-6 p-1">
            <a class="text-white hover:text-blue-300" href="#">Services</a>
          </li>
          <li class="mr-6 p-1">
            <a class="text-white hover:text-blue-300" href="#">Projects</a>
          </li>
          <li class="mr-6 p-1">
            <a class="text-white hover:text-blue-300" href="#">Team</a>
          </li>
          <li class="mr-6 p-1">
            <a class="text-white hover:text-pink" href="#">About</a>
          </li>
          <li class="mr-6 p-1">
            <a class="text-white hover:text-blue-300" href="#">Contacts</a>
          </li>
        </ul>
      </div>
      <div >
       

        <h1><b>Please fill in this form to create an account.</b></h1>
        <br>
        <hr>
    
        <label for="email">
          <b>Email</b
            ></label>
        <input type="text" placeholder="Enter Email" name="email" id="email" required>
    <hr>
        <label for="psw"><b>Password</b></label>
        <input type="password" placeholder="Enter Password" name="psw" id="psw" required>
    
        <label for="psw-repeat"><b>Repeat Password</b></label>
        <input type="password" placeholder="Repeat Password" name="psw-repeat" id="psw-repeat" required>
        <hr>
        <p>By creating an account you agree to our <a href="#">Terms & Privacy</a>.</p>
    
        <button type="submit" class="registerbtn">Register</button>
      </div>
      
      <div class="container signin">
        <p>Already have an account? <a href="#">Sign in</a>.</p>
      </div>
    </div>
  </body>
 
</html>
