# youtube-    <Html>
<head> 
<title>
Registration Page
</title>rrrrg
</head>DFG
<br>
<br>gf
<form>

<label> Firstname </label>       
<input type="text" name="firstname" size="15"/> <br> <br>
<label> Middlename: </label>   
<input type="text" name="middlename" size="15"/> <br> <br>
<label> Lastname: </label>       
<input type="text" name="lastname" size="15"/> <br> <br>

<label> 
Course :
</label> 
<select>
<option value="Course">Course</option>
<option value="BCA">BCA</option>
<option value="BBA">BBA</option>
<option value="B.Tech">B.Tech</option>
<option value="MBA">MBA</option>
<option value="MCA">MCA</option>
<option value="M.Tech">M.Tech</option>
</select>

<br>
<br>
<label for="start">Start date:</label>

<input type="date" id="start" name="trip-start"
       value="2018-07-22"
       min="2018-01-01" max="2023-05-16">

<label> 
Gender :
</label><br>
<input type="radio" name="male"/> Male <br>
<input type="radio" name="female"/> Female <br>
<input type="radio" name="other"/> Other
<br>
<br>

<label> 
Phone :
</label>
<input type="text" name="country code"  value="+91" size="2"/> 
<input type="text" name="phone" size="10"/> <br> <br>
Address:
<br>
<textarea cols="80" rows="5" value="address">  
body{  
  font-family: Calibri, Helvetica, sans-serif;  
  background-color: pink;  
}  
.container {  
    padding: 50px;  
  background-color: lightblue;  
}  
  
input[type=text], input[type=password], textarea {  
  width: 100%;  
  padding: 15px;  
  margin: 5px 0 22px 0;  
  display: inline-block;  
  border: none;  
  background: #f1f1f1;  
}  
input[type=text]:focus, input[type=password]:focus {  
  background-color: orange;  
  outline: none;  
}  
 div {  
            padding: 10px 0;  
         }  
hr {  
  border: 1px solid #f1f1f1;  
  margin-bottom: 25px;  
}  
.registerbtn {  
  background-color: #4CAF50;  
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
<br>
}  
</style>  
</head>  
<body>  
<form>  
  <div class="container">  
  <center>  <h1> Student Registeration Form</h1> </center>  
  <hr>  
  <label> Firstname </label>   
<input type="text" name="firstname" placeholder= "Firstname" size="15" required />   
<label> Middlename: </label>   
<input type="text" name="middlename" placeholder="Middlename" size="15" required />   
<label> Lastname: </label>    
<input type="text" name="lastname" placeholder="Lastname" size="15"required />   
<div>  
<label>   
Course :  
</label>   
  
<select>  
<option value="Course">Course</option>  
<option value="BCA">BCA</option>  
<option value="BBA">BBA</option>  
<option value="B.Tech">B.Tech</option>  
<option value="MBA">MBA</option>  
<option value="MCA">MCA</option>  
<option value="M.Tech">M.Tech</option>  
</select>  
</div>  
<div>  
<label>   
Gender :  
</label><br>  
<input type="radio" value="Male" name="gender" checked > Male   
<input type="radio" value="Female" name="gender"> Female   
<input type="radio" value="Other" name="gender"> Other  
  
</div>  
<label>   
Phone :  
</label>  
<input type="text" name="country code" placeholder="Country Code"  value="+7" size="2"/>   
<input type="text" name="phone" placeholder="phone no." size="10"/ required>   
Current Address :  
<textarea cols="80" rows="5" placeholder="Current Address" value="address" required>  
</textarea>  
 <label for="email"><b>Email</b></label>  
 <input type="text" placeholder="Enter Email" name="email" required>  
  
    <label for="psw"><b>Password</b></label>  
    <input type="password" placeholder="Enter Password" name="psw" required>  
  
    <label for="psw-repeat"><b>Re-type Password</b></label>  
    <input type="password" placeholder="Retype Password" name="psw-repeat" required>  
    <button type="submit" class="registerbtn">Register</button>    
</form>  
</body>  
</html>  
<html>  
<head>  
<title>  
Example of required attribute with input element   
</title>  
<style>  
div  
{  
padding: 10px 0;  
}  
</style>  
<head>  
<body>  
<form>  
<div>  
<label>Name</label>   
<input type="text" placeholder="Enter Name" name="name" required>   
</div>  
<div>   
<label> E-mail </label>   
<input type="email" placeholder="Enter email ID" name="email" required>   
  
</div>  
<div>  
 <label> Mobile No. </label>   
<input type="text" placeholder="Enter Your Mobile No." name="mobileno" required>  
</div>  
  
<div>  
<label>Password</label>   
<input type="password" placeholder="Enter Password" name="psw" required>   
<br>  
  </div>   
<button type="submit" VALUE="SUBMIT"> SUBMIT </button>  
</form>  
</body>  
</html> 
  
