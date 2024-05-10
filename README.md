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
      display: flex; /* Use flexbox to align items */  
      justify-content: flex-end; /* Aligns the content to the right */  
      align-items: center; /* Vertically centers the content */  
      padding: 10px; /* Adds some padding around the content */  
      position: relative; /* Ensures header content is positioned correctly */  
      width: 100%;  
    }  
    #menu {  
      position: absolute; /* Adjusted for top-right positioning */  
      right: 10px; /* Aligns the menu to the right edge */  
      top: 10px; /* Aligns the menu to the top edge */  
    }  
    #menu button {  
      background-color: transparent; /* Makes the button background transparent */  
      color: red; /* Sets the button text color to red */  
      border: 2px solid red; /* Adds a red border to the buttons */  
      padding: 5px 10px; /* Adds some padding inside the buttons */  
      margin-left: 5px; /* Adds some space between the buttons */  
      cursor: pointer; /* Changes cursor to pointer when hovering over the buttons */  
    }  
    #menu button:hover {  
      background-color: red; /* Changes background to red on hover */  
      color: black; /* Changes text color to black on hover */  
    }  
    #websiteLogo {  
      position: absolute; /* Ensures the logo is positioned correctly */  
      left: 10px; /* Space from the left edge */  
      top: 10px; /* Space from the top edge */  
      max-width: 100px; /* Adjust logo size as needed */  
    }  
    .hidden {  
      display: none; /* Hides elements with class 'hidden' */  
    }  
  </style>  
</head>  
<body>  
  <header>  
    <img src="download(5).jpeg" alt="Website Logo" id="websiteLogo">  
    <div id="menu">  
      <button onclick="window.location.href='#game-section'">Games</button>  
      <button id="chatRoomBtn" onclick="window.open('https://discord.gg/yourInviteCode', '_blank')">Chat Room</button>  
      <button onclick="window.location.href='#link-room'">Link Room</button>  
    </div>  
  </header>  
  
  <div id="game-section">  
    <!-- Game content goes here -->  
  </div>  
  
  <div id="chat-room" class="hidden">  
  <script id="cid0020000376350379686" data-cfasync="false" async src="//st.chatango.com/js/gz/emb.js" style="width: 250px;height: 350px;">{"handle":"chats-menu","arch":"js","styles":{"a":"CC0000","b":100,"c":"FFFFFF","d":"FFFFFF","k":"CC0000","l":"CC0000","m":"CC0000","n":"FFFFFF","p":"10","q":"CC0000","r":100,"fwtickm":1}}</script>
    <p>Chat room content...</p>  
  </div>  
  
</body>  
</html>  
  
      var chatRoom = document.getElementById('chat-room');  
      chatRoom.classList.toggle('hidden');  
    });  
  </script>  
</body>  
</html>  
