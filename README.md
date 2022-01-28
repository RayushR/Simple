# Simple_Calculater

<!DOCTYPE html>
<html lang="en">
  <head>
    <title>JavaScript Calculator</title>

    <style>
      h1 {
        text-align: center;
        padding: 23px;
        background-color: skyblue;
        color: rgb(7, 7, 7);
      }

      #clear {
        width: 270px;
        border: 3px solid rgb(5, 5, 5);
        border-radius: 3px;
        padding: 20px;
        background-color: red;
      }

      .formstyle {
        width: 300px;
        height: 530px;
        margin: auto;
        background-color: black;
        border: 3px solid rgb(17, 17, 17);
        border-radius: 5px;
        padding: 20px;
      }

      input {
        width: 20px;
        background-color: rgb(68, 68, 68);
        color: rgb(124, 123, 123);
        border: 3px solid rgb(10, 10, 10);
        border-radius: 5px;
        padding: 26px;
        margin: 5px;
        font-size: 15px;
      }

      #calc {
        width: 250px;
        border: 5px solid black;
        border-radius: 3px;
        padding: 20px;
        margin: auto;
      }
    </style>
  </head>
  <body>
    <h1>Calculator Program in JavaScript</h1>
    <div class="formstyle">
      <form name="form1">
        <input id="calc" type="text" name="answer" /> <br />
        <br />
