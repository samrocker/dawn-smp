<html>
  <head>
    <style>
      body {
        font-family: Arial, sans-serif;
        background-color: #F0F0F0;
        display: flex;
        align-items: center;
        justify-content: center;
        height: 100
vh;
      }

      form {
        background-color: white;
        border-radius: 10px;
        box-shadow: 2px 2px 10px rgba(0, 0, 0, 0.1);
        padding: 40px;
        width: 500px;
      }

      h2 {
        text-align: center;
        margin-bottom: 30px;
      }

      label, input[type="submit"] {
        display: block;
        margin-top: 20px;
        margin-bottom: 10px;
      }

      input[type="text"], select, input[type="url"] {
        padding: 10px;
        font-size: 16px;
        width: 100%;
        box-sizing: border-box;
        border: 1px solid gray;
        border-radius: 5px;
      }

      input[type="submit"] {
        padding: 10px 20px;
        background-color: blue;
        color: white;
        border: none;
        border-radius: 4px;
        cursor: pointer;
        margin-top: 20px;
      }
    </style>
  </head>
  <body>
    <form>
      <h2>DAWN SMP FORM</h2>
      <label for="name">Name:</label>
      <input type="text" id="name" name="name">

      <label for="age">Age:</label>
      <input type="text" id="age" name="age">

      <label for="gender">Gender:</label>
      <select id="gender" name="gender">
        <option value="Male">Male</option>
        <option value="Female">Female</option>
        <option value="Other">Other</option>
      </select>

      <label for="youtube">Youtube Channel Link:</label>
      <input type="url" id="youtube" name="youtube">

      <label for="discord">Discord ID:</label>
      <input type="text" id="discord" name="discord">

      <label for="software">Editing Software Name:</label>
      <input type="text" id="software" name="software">

      <label for="joined">When did you join Minecraft?:</label>
      <input type="text" id="joined" name="joined">

      <input type="submit" value="Submit">
    </form>
  </body>
</html>

