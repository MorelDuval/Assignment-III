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
