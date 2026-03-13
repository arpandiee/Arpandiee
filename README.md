<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Special Surprise</title>
    <style>
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background-color: #fae1dd;
            margin: 0;
            font-family: 'Arial', sans-serif;
        }

        .container {
            cursor: pointer;
            position: relative;
        }

        .envelope {
            position: relative;
            width: 300px;
            height: 200px;
            background-color: #f08080;
            border-bottom-left-radius: 10px;
            border-bottom-right-radius: 10px;
            box-shadow: 0 10px 20px rgba(0,0,0,0.1);
        }

        .envelope::before {
            content: "";
            position: absolute;
            top: 0;
            z-index: 2;
            border-left: 150px solid transparent;
            border-right: 150px solid transparent;
            border-top: 100px solid #f4978e;
            transition: transform 0.5s;
            transform-origin: top;
        }

        .letter {
        

<!--
**arpandiee/Arpandiee** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
