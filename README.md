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
      width: 100%;  
    }  
    #menu {  
      position: absolute; /* Changed to absolute for top-right positioning */  
      right: 0; /* Aligns the menu to the right */  
      top: 0; /* Aligns the menu to the top */  
      margin: 10px; /* Adds some space from the top and right edges */  
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
      max-width: 100px; /* Adjust logo size as needed */  
      display: block; /* Ensures the logo is block-level for proper spacing */  
      position: absolute; /* Added to ensure logo stays at the top left */  
      left: 10px; /* Space from the left edge */  
      top: 10px; /* Space from the top edge */  
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
    <!-- Chatango Chat Box Embed Code -->  
    <script id="cid0020000376351096633" data-cfasync="false" async src="//st.chatango.com/js/gz/emb.js" style="width: 250px;height: 350px;">  
        {"handle":"message-menu","arch":"js","styles":{"a":"CC0000","b":100,"c":"FFFFFF","d":"FFFFFF","k":"CC0000","l":"CC0000","m":"CC0000","n":"FFFFFF","p":"10","q":"CC0000","r":100,"fwtickm":1}}  
    </script>  
    <!-- End of Chatango Chat Box Embed Code -->  
  </div>    
    
  <script>    
    document.getElementById('chatRoomBtn').addEventListener('click', function() {  
      document.getElementById('chat-room').classList.toggle('hidden');  
    });  
  </script>  
    
</body>  
</html>  

