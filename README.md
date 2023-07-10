<!DOCTYPE html>
<html>
<head>
  <title>homepage</title>
  <style>
    /* CSS for the header container */
    .header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 10px;
      background-color: #f2f2f2;
    }

    /* CSS for the logo */
    .logo {
      width: 100px;
      height: 50px;
    }

    /* CSS for the buttons */
    .buttons {
      display: flex;
    }

    .button {
      margin-left: 10px;
      padding: 5px 10px;
      background-color: #4CAF50;
      color: white;
      border: none;
      border-radius: 3px;
      cursor: pointer;
    }
    .imgcnt {
      display: flex;
      align-items: center;
      justify-content: center;
      height: 100vh;
      background-color: #ADD8E6;
    }

    /* CSS for the image container */
    .image-container {
      flex: 1;
      padding: 20px;
      text-align: center;
    }

    /* CSS for the image */
    .image {
      max-width: 100%;
      height: auto;
    }

    /* CSS for the content container */
    .content-container {
      flex: 1;
      padding: 20px;
      font-size: 18px;
    }
  </style>
</head>
<body>
  <header class="header">
    <img src="https://img.freepik.com/premium-photo/young-man-holding-phone-with-insurance-icon_218381-5216.jpg" alt="Logo" class="logo">
    <h2>Insurance Company</h2>
    <div class="buttons">
      <button class="button" onclick="gohome()">Home</button>
      <button class="button" onclick="gosignup()">SignUp</button>
      <button class="button" onclick="gologin()">Login</button>

      <script>
        function gohome() {
          window.location.href = "homepage.html"; // Replace with the desired URL
        }
        function gologin() {
          window.location.href = "login.html"; // Replace with the desired URL
        }
        function gosignup() {
          window.location.href = "register.html"; // Replace with the desired URL
        }
      </script>
    </div>
  </header>
  <span class="imgcnt">
  <div class="image-container">
    <img src="https://img.freepik.com/premium-photo/young-man-holding-phone-with-insurance-icon_218381-5216.jpg" alt="Image" class="image">
  </div>
  <div class="content-container">
    <h1>Welcome to My Website</h1>
    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed consequat lacus mauris, non feugiat turpis cursus at. Quisque id velit id lacus pulvinar auctor. Fusce vulputate sem et eros consectetur aliquet. Curabitur nec libero vitae nunc pellentesque congue id et metus. Mauris vel luctus lorem, in volutpat ipsum. Sed id finibus tortor, vel bibendum mauris. Phasellus eget augue quis nunc tincidunt fringilla. Nullam tincidunt metus a libero pharetra, ac placerat ligula fermentum. Nulla facilisi.</p>
  </div>
  </span>
</body>
</html>

------------------------------------------------------------------------------------------

<!DOCTYPE html>
<html>
<head>
  <title>Page with Information and Image</title>
  <style>
          .header {
        display: flex;
        justify-content: space-between;
        align-items: center;
        padding: 10px;
        background-color: #f2f2f2;
      }
  
      /* CSS for the logo */
      .logo {
        width: 100px;
        height: 50px;
      }
  
      /* CSS for the buttons */
      .buttons {
        display: flex;
      }
  
      .button {
        margin-left: 10px;
        padding: 5px 10px;
        background-color: #4CAF50;
        color: white;
        border: none;
        border-radius: 3px;
        cursor: pointer;
      }
      .imgcnt {
        display: flex;
        align-items: center;
        justify-content: center;
        height: 100vh;
        background-color: #ADD8E6;
      }
  
      /* CSS for the image container */
      .image-container {
        flex: 1;
        padding: 20px;
        text-align: center;
      }
  
      /* CSS for the image */
      .image {
        max-width: 100%;
        height: auto;
      }
  
      /* CSS for the content container */
      .content-container {
        flex: 1;
        padding: 20px;
        font-size: 18px;
      }
    /* CSS for the page layout */
    .container {
      display: flex;
      align-items: flex-start;
      justify-content: center;
      max-width: 800px;
      margin: 0 auto;
      padding: 20px;
    }

    /* CSS for the left side */
    .left-side {
      flex: 1;
    }

    /* CSS for the information section */
    .info-section {
      margin-bottom: 20px;
    }

    /* CSS for the buttons */
    .button {
      display: inline-block;
      padding: 10px 20px;
      background-color: #4CAF50;
      color: white;
      text-decoration: none;
      border-radius: 4px;
      margin-bottom: 10px;
    }

    /* CSS for the right side */
    .right-side {
      flex: 1;
      text-align: center;
    }

    /* CSS for the image */
    .image {
      max-width: 100%;
      height: auto;
    }

  </style>
</head>
<body>

    <header class="header">
        <img src="https://img.freepik.com/premium-photo/young-man-holding-phone-with-insurance-icon_218381-5216.jpg" alt="Logo" class="logo">
        <h2>Insurance Company</h2>
        <div class="buttons">
          <button class="button" onclick="gohome()">Logout</button>
    
          <script>
            function gohome() {
              window.location.href = "homepage.html"; // Replace with the desired URL
            }
            function viewpolicy() {
              window.location.href = "viewpolicy.html"; // Replace with the desired URL
            }
            function selectPolicy(){
                window.location.href = "selectpolicy.html"; 
            }
            
          </script>
        </div>
      </header>
  <div class="container">
    <div class="left-side">
      <div class="info-section">
        <h2>Welcome!!</h2>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed vitae velit eu lorem rutrum interdum. Sed ac risus id dolor interdum tempus vel non ligula.</p>
      </div>
      <a href="#" class="button" onclick="selectPolicy()">Select Policy</a>
      <a href="#" class="button" onclick="viewpolicy()">View Policy</a>

    </div>
    <div class="right-side">
      <img src="https://htmlcolorcodes.com/assets/images/colors/light-blue-color-solid-background-1920x1080.png" alt="Image" class="image">
    </div>
  </div>
</body>
</html>

------------------------------------------------------------------------------------------

<!DOCTYPE html>
<html>
<head>
<title>Page Title</title>

<style>
    /* CSS for the header container */
    .header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 10px;
      background-color: #f2f2f2;
    }

    /* CSS for the logo */
    .logo {
      width: 100px;
      height: 50px;
    }

    /* CSS for the buttons */
    .buttons {
      display: flex;
    }

    .button {
      margin-left: 10px;
      padding: 5px 10px;
      background-color: #4CAF50;
      color: white;
      border: none;
      border-radius: 3px;
      cursor: pointer;
    }
        body {
          background: white;
          color: white;
          font: 87.5%/1.5em 'Open Sans', sans-serif;
          margin: 0;
        }

        p {
          line-height: 1.5em;
        }

        after { clear: both; }

        .login {
          margin: 50px auto;
          width: 520px;
          
        }

        .login form {
          margin: auto;
          padding: 22px 22px 22px 22px;
          width: 100%;
          border-radius: 5px;
          background: #282e33;
          border-top: 3px solid #434a52;
          border-bottom: 3px solid #434a52;
        }

        .login form span {
          background-color: #363b41;
          border-radius: 3px 0px 0px 3px;
          border-right: 3px solid #434a52;
          color: #606468;
          display: block;
          float: left;
          line-height: 50px;
          text-align: center;
          width: 50px;
          height: 50px;
        }

        .login form input[type="email"] {
          background-color: #3b4148;
          border-radius: 0px 3px 3px 0px;
          color: #a9a9a9;
          margin-bottom: 1em;
          padding: 0 16px;
          width: 90%;
          height: 50px;
        }

        .login form input[type="password"], .login form input[type="text"],.login form input[type="tel"] {
          background-color: #3b4148;
          border-radius: 0px 3px 3px 0px;
          color: #a9a9a9;
          margin-bottom: 1em;
          padding: 0 16px;
          width: 90%;
          height: 50px;
        }

        .login form input[type="submit"] {
          background: #b5cd60;
          border: 0;
          width: 100%;
          height: 40px;
          border-radius: 3px;
          color: white;
          cursor: pointer;
          transition: background 0.3s ease-in-out;
        }
        #login form input[type="submit"]:hover {
          background: #16aa56;
        }

</style>

</head>

<script>

function generateUniqueId() {
      // Generate a random number as the unique ID
      return Math.floor(Math.random() * 100000);
    }

function store(){
  event.preventDefault();

    var name = document.getElementById('name');
    var pw = document.getElementById('pw');
    var email = document.getElementById('email');
    var customerId = generateUniqueId();
    var lowerCaseLetters = /[a-z]/g;
    var upperCaseLetters = /[A-Z]/g;
    var numbers = /[0-9]/g;

    if(name.value.length == 0){
        alert('Please fill in name');

    }else if(pw.value.length == 0){
        alert('Please fill in password');

    }else if(name.value.length == 0 && pw.value.length == 0){
        alert('Please fill in email and password');

    }else if(pw.value.length > 8){
        alert('Max of 8');

    }else if(!pw.value.match(numbers)){
        alert('please add 1 number');

    }else if(!pw.value.match(upperCaseLetters)){
        alert('please add 1 uppercase letter');

    }else if(!pw.value.match(lowerCaseLetters)){
        alert('please add 1 lovercase letter');

    }else{
        localStorage.setItem('name', name.value);
        localStorage.setItem('pw', pw.value);
        localStorage.setItem('customerId',customerId);
        localStorage.setItem('email',email.value);
        alert('Your account has been created');
        window.location.href = "registrationsuccesful.html";
    }
}

//checking


</script>





<body style="background-color: #F0FFFF;">
  <header class="header">
    <img src="https://img.freepik.com/premium-photo/young-man-holding-phone-with-insurance-icon_218381-5216.jpg" alt="Logo" class="logo">
    <h2>Insurance Company</h2>
    <div class="buttons">
      <button class="button" onclick="gohome()">Home</button>
      <button class="button" onclick="gosignup()">SignUp</button>
      <button class="button" onclick="gologin()">Login</button>

      <script>
        function gohome() {
          window.location.href = "homepage.html"; // Replace with the desired URL
        }
        function gologin() {
          window.location.href = "login.html"; // Replace with the desired URL
        }
        function gosignup() {
          window.location.href = "register.html"; // Replace with the desired URL
        }
      </script>
    </div>
  </header>
<script>
  function moveToPage() {
    window.location.href = "login.html"; // Replace with the desired URL
  }
</script>

<div class="login", id="login">
    <form name='form-login'>

        <h1>REGISTER</h1>

        <label for="name">Full Name</label>
        <input type="text" id="name" placeholder="Your Name..." required>
        <label for="name">Email</label>
        <input type="email" id="email" placeholder="Username" required>
        <label for="name">Address</label>
        <input type="text" id="address" placeholder="Address" required>
        <label for="name">Nominee Name</label>
        <input type="text" id="nominee" placeholder="Nomimee Name..." required>
        <label for="name">Realtionship</label>
        <input type="text" id="relation" placeholder="Relationship..." required>
        <label for="name">Contact Number</label>
        <input type="tel" id="contact" name="contact" pattern="[0-9]{10}" placeholder="Phone number..." required>
        

        <label for="pw">Password</label>
        <input type="password"
               id= "pw"
               placeholder="Password" required>
               <input type="checkbox" onclick="showpassword()">Show Password

               <script>
               function showpassword() {
                 var x = document.getElementById("pw");
                 if (x.type === "password") {
                   x.type = "text";
                 } else {
                   x.type = "password";
                 }
               }
               </script>
               
        <ul class="helper-text">
            <li class="length">Must be at least 8 characters long.</li>
            <li class="lowercase">Must contain a lowercase letter.</li>
            <li class="uppercase">Must contain an uppercase letter.</li>
            <li class="special">Must contain a number or special character.</li>
        </ul>
        <input id="rgstr_btn" type="submit" value="Register" onclick="store()">

    </form>
</div>



</body>
</html>

---------------------------------------------------------------------------------------
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Registration sucessful</title>
    
    <style>
      /* CSS for the header container */
      .header {
        display: flex;
        justify-content: space-between;
        align-items: center;
        padding: 10px;
        background-color: #f2f2f2;
      }
  
      /* CSS for the logo */
      .logo {
        width: 100px;
        height: 50px;
      }
  
      /* CSS for the buttons */
      .buttons {
        display: flex;
      }
  
      .button {
        margin-left: 10px;
        padding: 5px 10px;
        background-color: #4CAF50;
        color: white;
        border: none;
        border-radius: 3px;
        cursor: pointer;
      }
      .imgcnt {
        display: flex;
        align-items: center;
        justify-content: center;
        height: 100vh;
        background-color: #ADD8E6;
      }
  
      /* CSS for the image container */
      .image-container {
        flex: 1;
        padding: 20px;
        text-align: center;
      }
  
      /* CSS for the image */
      .image {
        max-width: 100%;
        height: auto;
      }
  
      /* CSS for the content container */
      .content-container {
        flex: 1;
        padding: 20px;
        font-size: 18px;
      }
    </style>
</head>
<body>

    <script>
        
        document.addEventListener('DOMContentLoaded', function() {
  // Retrieve the stored values from local storage
  var name = localStorage.getItem('name');
  var pw = localStorage.getItem('pw');
  var customerId2 = localStorage.getItem('customerId');
  var email = localStorage.getItem('email');

  // Display the values on the web page
  document.getElementById('nameValue').innerText = name;
  document.getElementById('email').innerText = email;
  document.getElementById('customerIdValue').innerText = customerId2;
});
    
    </script>


<header class="header">
    <img src="https://img.freepik.com/premium-photo/young-man-holding-phone-with-insurance-icon_218381-5216.jpg" alt="Logo" class="logo">
    <h2>Insurance Company</h2>
    <div class="buttons">
      <button class="button" onclick="gohome()">Home</button>
      <button class="button" onclick="gosignup()">SignUp</button>
      <button class="button" onclick="gologin()">Login</button>

      <script>
        function gohome() {
          window.location.href = "homepage.html"; // Replace with the desired URL
        }
        function gologin() {
          window.location.href = "login.html"; // Replace with the desired URL
        }
        function gosignup() {
          window.location.href = "register.html"; // Replace with the desired URL
        }
      </script>
    </div>
  </header>
  <span class="imgcnt">
  <div class="image-container">
    <img src="https://img.freepik.com/premium-photo/young-man-holding-phone-with-insurance-icon_218381-5216.jpg" alt="Image" class="image">
  </div>
  <div class="content-container">
    <div style="color: green; font-weight: bold; font-size: 30px;">Customer Registration sucessful</div>
    
    <p style="color: black; font-weight: bold; ">Name: <span id="nameValue"></span></p>
    <p style="color: black; font-weight: bold; ">Email: <span id="email"></span></p>
    <p style="color: black; font-weight: bold; ">Customer ID: <span id="customerIdValue"></span></p>  
    <button class="button" onclick="gohome()">Home</button>
    <button class="button" onclick="gologin()">Login</button>
    
</div>
  </span>
</body>
</html>
-------------------------------------------------------------------------------------------

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>

    <style>
            .header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 10px;
      background-color: #f2f2f2;
    }

    /* CSS for the logo */
    .logo {
      width: 100px;
      height: 50px;
    }

    /* CSS for the buttons */
    .buttons {
      display: flex;
    }

    .button {
      margin-left: 10px;
      padding: 5px 10px;
      background-color: #4CAF50;
      color: white;
      border: none;
      border-radius: 3px;
      cursor: pointer;
    }

    body {
           background: white;
            color: white;
            font: 87.5%/1.5em 'Open Sans', sans-serif;
            margin: 0;
                }
        
                p {
                  line-height: 1.5em;
                }
        
        
      .login {
                  margin: 50px auto;
                  width: 521px;
 
      }
        
      .login form {
                  margin: auto;
                  padding: 22px 22px 22px 22px;
                  width: 100%;
                  border-radius: 5px;
                  background: #282e33;
                  border-top: 3px solid #434a52;
                  border-bottom: 3px solid #434a52;
       }
        
        .login form span {
                  background-color: #363b41;
                  border-radius: 3px 0px 0px 3px;
                  border-right: 3px solid #434a52;
                  color: #606468;
                  display: block;
                  float: left;
                  line-height: 50px;
                  text-align: center;
                  width: 50px;
                  height: 50px;
       }
        
        .login form input[type="text"] {
                  background-color: #3b4148;
                  border-radius: 0px 3px 3px 0px;
                  color: #a9a9a9;
                  margin-bottom: 1em;
                  padding: 0 16px;
                  width: 90%;
                  height: 50px;
        }
        
        .login form input[type="password"] {
                  background-color: #3b4148;
                  border-radius: 0px 3px 3px 0px;
                  color: #a9a9a9;
                  margin-bottom: 1em;
                  padding: 0 16px;
                  width: 90%;
                  height: 50px;
        }
        
        .login form input[type="submit"] {
                  background: #b5cd60;
                  border: 0;
                  width: 100%;
                  height: 40px;
                  border-radius: 3px;
                  color: white;
                  cursor: pointer;
                  transition: background 0.3s ease-in-out;
        }
        #login form input[type="submit"]:hover {
                  background: #16aa56;
        }
        
        </style>

</head>
<body>
    <script>
    function check(){
      event.preventDefault();
    var storedName = localStorage.getItem('name');
    var storedPw = localStorage.getItem('pw');
    var customerId2 = localStorage.getItem('customerId');

    var usernum = document.getElementById('usernum');
    var userPw = document.getElementById('userPw');
 

    if(usernum.value == customerId2 && userPw.value == storedPw){
        alert('You are logged in.');
        window.location.href = "home2.html";
    }else{
        alert('Error on login');
        
    }
}

</script>
<header class="header">
  <img src="https://img.freepik.com/premium-photo/young-man-holding-phone-with-insurance-icon_218381-5216.jpg" alt="Logo" class="logo">
  <h2>Insurance Company</h2>
  <div class="buttons">
    <button class="button" onclick="gohome()">Home</button>
    <button class="button" onclick="gosignup()">SignUp</button>
    <button class="button" onclick="gologin()">Login</button>

    <script>
      function gohome() {
        window.location.href = "homepage.html"; // Replace with the desired URL
      }
      function gologin() {
        window.location.href = "login.html"; // Replace with the desired URL
      }
      function gosignup() {
        window.location.href = "register.html"; // Replace with the desired URL
      }
    </script>
  </div>
</header>


  
  <div class="login", id="signup">
      <form name='form-login'>
  
          <h1>Log IN</h1>
  
          <label for="userNum">Registered Number</label>
          <input type="text" id="usernum" placeholder="Registration ID...." required>
  
          <label for="userPw">Password</label>
          <input type="password" id= "userPw" placeholder="Password" required>
  
  
          <input id= "login_btn" type="submit" value="Login" onclick="check()">
  
      </form>
  </div>
  
</body>
</html>
------------------------------------------------------------------------------------------------
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Registration sucessful</title>
    
    <style>
      /* CSS for the header container */
      .header {
        display: flex;
        justify-content: space-between;
        align-items: center;
        padding: 10px;
        background-color: #f2f2f2;
      }
  
      /* CSS for the logo */
      .logo {
        width: 100px;
        height: 50px;
      }
  
      /* CSS for the buttons */
      .buttons {
        display: flex;
      }
  
      .button {
        margin-left: 10px;
        padding: 5px 10px;
        background-color: #4CAF50;
        color: white;
        border: none;
        border-radius: 3px;
        cursor: pointer;
      }
      .imgcnt {
        display: flex;
        align-items: center;
        justify-content: center;
        height: 100vh;
        background-color: #ADD8E6;
      }
  
      /* CSS for the image container */
      .image-container {
        flex: 1;
        padding: 20px;
        text-align: center;
      }
  
      /* CSS for the image */
      .image {
        max-width: 100%;
        height: auto;
      }
  
      /* CSS for the content container */
      .content-container {
        flex: 1;
        padding: 20px;
        font-size: 18px;
      }
      table {
      border-collapse: collapse;
    }

    /* CSS for the table cells */
    td {
      padding: 8px;
    }

    /* CSS to hide the table borders */
    table, th, td {
      border: none;
    }
    </style>
</head>
<body>

    <script>
        
        document.addEventListener('DOMContentLoaded', function() {
  // Retrieve the stored values from local storage
  var a1 = localStorage.getItem('a1');
  var a2 = localStorage.getItem('a2');
  var a3 = localStorage.getItem('a3');
  var a4 = localStorage.getItem('a4');
  var a5 = localStorage.getItem('a5');
  
  

  // Display the values on the web page
  document.getElementById('a1').innerText = a1;
  document.getElementById('a2').innerText = a2;
  document.getElementById('a3').innerText = a3;
  document.getElementById('a4').innerText = a4;
  document.getElementById('a5').innerText = a5;
});
    
    </script>


<header class="header">
    <img src="https://img.freepik.com/premium-photo/young-man-holding-phone-with-insurance-icon_218381-5216.jpg" alt="Logo" class="logo">
    <h2>Insurance Company</h2>
    <div class="buttons">
      <button class="button" onclick="gohome2()">Back</button>
      <button class="button" onclick="gohome()">Logout</button>

      <script>
        function gohome() {
          window.location.href = "homepage.html"; // Replace with the desired URL
        }
        function gohome2() {
          window.location.href = "home2.html"; // Replace with the desired URL
        }
        function selectPolicy(){
            window.location.href = "selectpolicy.html"; 
        }
        
      </script>
    </div>
  </header>
  <span class="imgcnt">
  <div class="image-container">
    <img src="https://img.freepik.com/premium-photo/young-man-holding-phone-with-insurance-icon_218381-5216.jpg" alt="Image" class="image">
  </div>
  <div class="content-container">
    <div style="color: green; font-weight: bold; font-size: 30px;">Customer Registration sucessful</div>
    
    <table>
        <tr>
          <td>Policy Type</td>
          <td><span id="a1"></span></td>
        </tr>
        <tr>
          <td>Policy Name</td>
          <td><span id="a2"></span></td>
        </tr>
        <tr>
          <td>Sum Assumed</td>
          <td><span id="a3"></span></td>
        </tr>
        <tr>
          <td>Premium Amount</td>
          <td><span id="a4"></span></td>
        </tr>
        <tr>
          <td>Policy Term</td>
          <td><span id="a5"></span></td>
        </tr>
        <tr>
          <td><button class="button" onclick="gohome2()">Back</button></td>
          <td><button class="button" onclick="selectPolicy()">Select More</button></td>
        </tr>
      </table>
    
</div>
  </span>
</body>
</html>

-------------------------------------------------------------------------------------

<!DOCTYPE html>
<html>
<head>
  <title>Policy Listing</title>
  <style>

.header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 10px;
      background-color: #f2f2f2;
    }

    .logo {
      width: 100px;
      height: 50px;
    }

    .buttons {
      display: flex;
    }

    .button {
      margin-left: 10px;
      padding: 5px 10px;
      background-color: #4CAF50;
      color: white;
      border: none;
      border-radius: 3px;
      cursor: pointer;
    }

    /* CSS for the table container */
    .table-container {
      max-width: 800px;
      margin: 0 auto;
      padding: 20px;
    }

    /* CSS for the table */
    table {
      width: 100%;
      border-collapse: collapse;
      margin-bottom: 20px;
    }

    /* CSS for the table header */
    th {
      background-color: #f2f2f2;
      padding: 8px;
      text-align: left;
      border: 1px solid #ccc;
    }

    /* CSS for the table rows */
    td {
      padding: 8px;
      border: 1px solid #ccc;
    }

    /* CSS for the pagination container */
    .pagination-container {
      text-align: center;
      margin-top: 20px;
    }

    /* CSS for the pagination links */
    .pagination-link {
      display: inline-block;
      margin: 0 5px;
      padding: 5px 10px;
      background-color: #4CAF50;
      color: white;
      text-decoration: none;
      border-radius: 3px;
    }
  </style>
</head>
<body style="background-color: #F0FFFF;">
    <header class="header">
        <img src="https://img.freepik.com/premium-photo/young-man-holding-phone-with-insurance-icon_218381-5216.jpg" alt="Logo" class="logo">
        <h2>Insurance Company</h2>
        <div class="buttons">
          <button class="button" onclick="gohome2()">Back</button>
          <button class="button" onclick="gohome()">Logout</button>
    
          <script>
            function gohome() {
              window.location.href = "homepage.html"; // Replace with the desired URL
            }
            function gohome2() {
              window.location.href = "home2.html"; // Replace with the desired URL
            }
          </script>
        </div>
      </header>
      
  <div class="table-container">
    <table >
      <thead>
        <tr>
          <th>Policy NO</th>
          <th>Commence Date</th>
          <th>Status</th>
          <th>Policy Title</th>
          <th>Premium Amount</th>
          <th>Next Due Date</th>
          <th>Sum Assured</th>
          <th>Nominee Registered</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>Policy001</td>
          <td>2022-01-01</td>
          <td>Active</td>
          <td>General Policy</td>
          <td>$500</td>
          <td>2023-01-01</td>
          <td>$100,000</td>
          <td>Yes</td>
        </tr>
        <tr>
          <td>Policy002</td>
          <td>2022-02-01</td>
          <td>Active</td>
          <td>Health Policy</td>
          <td>$200</td>
          <td>2023-02-01</td>
          <td>$50,000</td>
          <td>No</td>
        </tr>
        <tr>
          <td>Policy003</td>
          <td>2022-03-01</td>
          <td>Matured</td>
          <td>Motor Policy</td>
          <td>$300</td>
          <td>2023-03-01</td>
          <td>$75,000</td>
          <td>Yes</td>
        </tr>
        <tr>
          <td>Policy004</td>
          <td>2022-04-01</td>
          <td>Active</td>
          <td>General Policy</td>
          <td>$400</td>
          <td>2023-04-01</td>
          <td>$90,000</td>
          <td>Yes</td>
        </tr>
        <tr>
          <td>Policy005</td>
          <td>2022-05-01</td>
          <td>Active</td>
          <td>Health Policy</td>
          <td>$250</td>
          <td>2023-05-01</td>
          <td>$60,000</td>
          <td>No</td>
        </tr>

      </tbody>
    </table>
    <div class="pagination-container">

      <a href="viewpolicy2.html" class="pagination-link">Next >></a>
    </div>
  </div>
</body>
</html>
-----------------------------------------------------------------------------------------
