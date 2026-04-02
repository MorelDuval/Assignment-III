<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Add Account</title>
    <link rel="stylesheet" href="style.css">
</head>

<body>
    <img src="p.jpg"  class="background-image">
    <div class="container">
    

 <h1>Add Account</h1>
  <strong>Account Information</strong>
  <br>
    <p class="subtitle">You can only select one account at a time.</p>

    <select name="Text" id="choice">
        <option value="Facebook">Facebook</option>
        <option value="Twitter">X</option>
        <option value="Instagram">Instagram</option>
        <option value="TikTok">TikTok</option>
        <option value="Snapchat">Snapchat</option>
    </select>


        <div class="name">
            <label for="text">Name</label>
            <input type="text" class="input-field" placeholder="Your Name">
            <p class="hint">For e.g. 4Years Facebook Account</p>

        <div class="name">
            <label for="Description">Description</label>
            <br>
            <textarea name="Description" class="description"></textarea>

            <div class="price">
            <br>
            <input type="number" class="price" placeholder="Enter your price">
            </div>
       
        </div>
        
        </div>
        <br><br>
         <button>Continue</button>
    </div>
   
   
    
</body>
</html>

body{
    display: flex;
    justify-content: center;
    align-items: center;
    padding: 0;
    margin: 0;
    height: 100vh;
    border-radius: 10px;
    font-weight: bold; 
}
.background-image{
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    object-fit: cover;
    z-index: -1;

}
h1{
   text-align: center;
}
.container{
    background-color: rgb(243, 243, 241);
    border: 1px solid #ccc;
    border-radius: 5px;
    padding: 50px;
    max-width: auto;
    margin: auto;
    box-shadow: 0 0 10px #4e4d4d;

}
label{
    display: block;
    font-weight: auto;
    font-size: 14px;
    margin-bottom: auto;
}
.name{
    margin-bottom: 20px;
    width: 100%;
}
#choice{
    align-items: auto;
    height: auto;
    width: 100%;
    border-radius: 3px;
}
.description{
    resize: none;
    height: 100px;
    width: 100%;
}
.input-field{
    padding: auto;
    border-radius: 5px;
    font-size: 16px;
    width: 100%;
    height: auto;
    box-sizing: border-box;
    font-size: auto;
}
.subtitle, .hint{
    font-size: auto;
    margin-bottom: auto;
    color: #888;
}
.price{
    margin-bottom: 20px;
    width: 100%;
    border-radius: 3px;
}


button{
    padding: 12px;
    font-weight: bold;
    font-size: 16px;
    background-color: orangered;
    border: none;
    border-radius:5px;
    color: white;
    font-weight: bold;
    width: 100%;
}
