<!DOCTYPE html>  
<html>  
<head>  
  <title>Project Ruin</title>  
  <style>  
    body {  
      margin: 0;  
      padding: 0;  
      background-color: black; /* Sets the background color of the website to black */  
      color: white; /* Sets the text color to white for better contrast */  
    }  
    header {  
      position: relative;  
      width: 100%;  
    }  
    #menu {  
      position: absolute;  
      top: 0;  
      right: 0;  
      padding: 10px;  
    }  
    #menu button {  
      background-color: transparent; /* Makes the button background transparent */  
      color: red; /* Sets the button text color to red */  
      border: 2px solid red; /* Optional: adds a red border to the buttons */  
      padding: 5px 10px; /* Adds some padding inside the buttons */  
      margin-right: 5px; /* Adds some space between the buttons */  
      cursor: pointer; /* Changes cursor to pointer when hovering over the buttons */  
    }  
    #menu button:hover {  
      background-color: red; /* Changes background to red on hover */  
      color: black; /* Changes text color to black on hover */  
    }  
    #websiteLogo {  
      max-width: 100px; /* Adjust logo size as needed */  
      display: block; /* Makes sure the logo is block-level for proper spacing */  
    }  
    .hidden {  
      display: none;  
    }  
  </style>  
</head>  
<body>  
  <header>  
    <img src="download(5).jpeg" alt="Website Logo" id="websiteLogo">  
    <div id="menu">  
      <button onclick="window.location.href='#game-section'">Games</button>  
      <button id="chatRoomBtn">Chat Room</button>  
      <button onclick="window.location.href='#link-room'">Link Room</button>  
    </div>  
  </header>  
  
  <div id="game-section">  
    <!-- Game content goes here -->  
  </div>  
  
  <div id="chat-room" class="hidden">  
    <!-- Chat room content will be shown here after clicking the Chat Room button -->  
    <p>Chat room content...</p>  
  </div>  
  
  <script>  
    document.getElementById('chatRoomBtn').addEventListener('click', function() {  
      var chatRoom = document.getElementById('chat-room');  
      chatRoom.classList.toggle('hidden');  
    });  
  </script>  
</body>  
</html>  
