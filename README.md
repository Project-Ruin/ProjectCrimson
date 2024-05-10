<!DOCTYPE html>  
<html>  
<head>  
  <title>Project Ruin</title>  
  <style>  
    /* Inline CSS for simplicity */  
    #menu {  
      position: fixed;  
      top: 0;  
      right: 0;  
      padding: 10px;  
    }  
  
    #websiteLogo {  
      max-width: 100px; /* Adjust logo size as needed */  
    }  
  
    .hidden {  
      display: none;  
    }  
  </style>  
</head>  
<body>  
  <header>  
    <div id="menu">  
      <button onclick="window.location.href='#game-section'">Games</button>  
      <button id="chatRoomBtn">Chat Room</button>  
      <button onclick="window.location.href='#link-room'">Link Room</button>  
    </div>  
    <img src="download(5).jpeg" alt="Website Logo" id="websiteLogo">  
  </header>  
  
  <div id="game-section">  
    <!-- Game content goes here -->  
  </div>  
  
  <div id="chat-room" class="hidden">  
    <script id="cid0020000376261958556" data-cfasync="false" async src="//st.chatango.com/js/gz/emb.js" style="width: 250px;height: 350px;">{"handle":"message-menu","arch":"js","styles":{"a":"CC0000","b":100,"c":"FFFFFF","d":"FFFFFF","k":"CC0000","l":"CC0000","m":"CC0000","n":"FFFFFF","p":"10","q":"CC0000","r":100,"fwtickm":1}}</script>  
  </div>  
  
  <script>  
    // Inline JavaScript for simplicity  
    document.getElementById('chatRoomBtn').addEventListener('click', function() {  
      var chatRoom = document.getElementById('chat-room');  
      if (chatRoom.classList.contains('hidden')) {  
        chatRoom.classList.remove('hidden');  
      } else {  
        chatRoom.classList.add('hidden');  
      }  
    });  
  </script>  
</body>  
</html>  

</body>  
</html> 
