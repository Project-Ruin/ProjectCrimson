<!DOCTYPE html>  
<html>  
<head>  
  <title>Project Ruin</title>  
  <style>  
    html, body {  
      margin: 0;  
      padding: 0;  
      width: 100%;  
      height: 100%;  
      background-color: black; /* Ensures the entire page is black */  
      color: white; /* Ensures text is white for contrast */  
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
      background-color: transparent;  
      color: red; /* Button text color */  
      border: 2px solid red;  
      padding: 5px 10px;  
      margin-right: 5px;  
      cursor: pointer;  
    }  
    #menu button:hover {  
      background-color: red;  
      color: black;  
    }  
    #websiteLogo {  
      max-width: 100px;  
      display: block;  
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
