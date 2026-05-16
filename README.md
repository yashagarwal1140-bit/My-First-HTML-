<!DOCTYPE html>
<html lang="en">
<head>
    
    <title>Document</title>
    <style>body {
    font-family: Arial, sans-serif;
    background-color: #f2f2f2;
    margin: 0;
    padding: 20px;
}

h1 {
    text-align: center;
    color: #333;
    margin-bottom: 20px;
}

form {
    width: 500px;
    margin: auto;
    background-color: white;
    padding: 25px;
    border-radius: 10px;
    box-shadow: 0px 0px 10px rgba(0,0,0,0.2);
}

table {
    width: 100%;
}

td {
    padding: 10px;
    vertical-align: top;
}

input[type="text"],
input[type="email"],
input[type="date"],
input[type="file"],
select,
textarea {
    width: 100%;
    padding: 8px;
    border: 1px solid #ccc;
    border-radius: 5px;
    box-sizing: border-box;
}

textarea {
    height: 80px;
    resize: none;
}

input[type="radio"],
input[type="checkbox"] {
    margin-right: 5px;
}

input[type="submit"],
input[type="reset"] {
    background-color: #4CAF50;
    color: white;
    border: none;
    padding: 10px 18px;
    border-radius: 5px;
    cursor: pointer;
    margin-right: 10px;
    font-size: 14px;
}

input[type="submit"]:hover,
input[type="reset"]:hover {
    background-color: #45a049;
}</style>
</head>
<body>
<h1>Student registration form</h1>
<form name="myform" action="" method=""> 
<table>
  <tr><td>First Name:</td><td> <input type="text" name="fname" size=""></td>
</tr>
<tr><td>Last Name:</td><td> <input type="text" name="lname" size=""></td>
</tr>
<tr><td>Father's Name:</td><td> <input type="text" name="fathername" size=""></td>
</tr>
 <tr><td>Mother's Name:</td><td> <input type="text" name="mothername" size=""></td>
</tr>
 <tr><td>Date of birth:</td><td> <input type="date" name="date" size=""></td>
</tr>  
 <tr><td>EMail:</td><td> <input type="email" name="email" size=""></td>
</tr>
 <tr><td>Gender:</td><td> <input type="radio" name="gender" size=""> Male <input type="radio" name="gender" size=""> Female</td>
</tr>
 <tr><td>Choose Course:</td>
   <td> <select name="course">
                <option name="">---SELECT---</option>
                <option name="">HTML</option>
                <option name="">JAVA</option>
                <option name="">C++</option>
                <option name="">PYTHON</option>
                <option name="">CSS</option>
                </select></td>
<tr><td>Hobbies:</td><td> <input type="checkbox" name="hobbies" size=""> Reading book <input type="checkbox" name="hobbies" size=""> playing football<input type="checkbox" name="hobbies" size=""> Basket ball<input type="checkbox" name="hobbies" size=""> playing Cricket</td>
</tr>
<tr><td>Address:</td><td> <textarea name="address"></textarea></td>
</tr>
<tr><td>Photo:</td><td> <input type="file" name="photo" size=""></td>
</tr>
<tr><td><input type="submit" name="submit" size=""></td>
</tr>


</table>
</form>

</body>
</html>
