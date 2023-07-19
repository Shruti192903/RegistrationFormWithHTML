# RegistrationFormWithHTML
Creation of a structure registration form website using the basic concepts of HTML 

# HTML #
     <!doctype html>

<html>
    <head>
        <meta charset="utf-8">

        <title>CSS01</title>

        <!-- Load external CSS styles -->
        <link rel="stylesheet" href="styles.css">

    </head>

    <body>

        <h1>Registration form</h1>
        <body style="background-color:rgb(211, 211, 211);">
        <!-- Load external JavaScript -->
        <script src="scripts.js"></script> 
            
            <h4>Full Name</h4>
            <input type="" placeholder="Full Name">            
            <h4>Parent Name</h4>
            <input type="" placeholder="Parent Name">
            <h4>Gender</h4>
            <input type="radio" name="button" id="rad1">
            <label for="rad1">Male</label>
            <input type="radio" name="button" id="rad2"> 
            <label for="rad2">Female</label> 
            <h4>Email</h4>
            <input type="" placeholder="sample@gmail.com">
            <h4>Password</h4>
            <input type="" placeholder="Pass@1234">
            <h4>Confirm Password</h4>
            <input type="" placeholder="Pass@1234">
            <h4>States</h4>
            <select name="states" id="states>"
                <option value="Maharashtra">MH</option>
                <option value="Maharashtra">MH</option>
                <option value="Madhya Pradesh">MP</option>
                <option value="Uttar Pradesh">UP</option>
                <option value="Others">Others</option>
            </select>
            <h4>Address</h4>
            <input type="textarea" name="" id="">
            <h4>Languages</h4>
                <input type="checkbox" name="Hindi" id="">Hindi
                <br></br>
                <input type="checkbox" name="English" id="">English
                <br></br>
                <input type="checkbox" name="Marathi" id="">Marathi
             <br></br>  
             <button type="button">Submit</button>
          
    </body>

</html>

# CSS #

h1 { 
    text-align:center;
    border: 3px;
    font-family: "Source Sans Pro", sans-serif;
    font-weight:bolder;
    background-attachment: fixed;
    background-color:rgb(243, 225, 63);   
}
h4{
    background-color:lightgray
    font-family: 'Times New Roman', Times, serif;
    font-style: normal;
    margin-bottom:5px;
    margin-right:50%;
    font-size:20px;
}
button{
padding:8px;
    border-color: darkslategrey;
    margin-left:20px 20px 20px 30px;
    border-radius:5px ;
   
   } 
rad1{
    padding-left:2px;
}
rad2{
    padding-left:2px;
}
Language{
    padding-bottom:2px;
    
}
