<!DOCTYPE html>  
<html lang="en">  
<head>  
    <meta charset="UTF-8">  
    <meta name="viewport" content="width=device-width, initial-scale=1.0">  
    <title>Document Title</title>  
    <style>  
        body {  
            margin: 0;  
            padding: 0;  
            background-color: black; /* Sets the entire page background to black */  
            color: white; /* Default text color set to white for contrast */  
        }  
        #menu button {  
            background-color: transparent;  
            color: red; /* Button text color */  
            border: 2px solid red; /* Adds a red border to the buttons */  
            cursor: pointer;  
        }  
        #menu button:hover {  
            background-color: red; /* Button background color on hover */  
            color: black; /* Button text color on hover */  
        }  
        .hidden {  
            display: none; /* Initially hides elements with this class */  
        }  
    </style>  
</head>  
<body>  
    <header>  
        <img src="path/to/your/logo.jpeg" alt="Website Logo" style="width:100px;">  
        <div id="menu">  
            <button onclick="alert('Navigating to games section')">Games</button>  
            <button onclick="toggleChatRoom()">Chat Room</button>  
            <button onclick="alert('Navigating to link room')">Link Room</button>  
        </div>  
    </header>  
    <div id="chat-room" class="hidden">  
        <!-- Chat room content will be dynamically shown here -->  
        <p>Chat room content...</p>  
    </div>  
    <script>  
        function toggleChatRoom() {  
            var chatRoom = document.getElementById('chat-room');  
            chatRoom.classList.toggle('hidden');  
        }  
    </script>  
</body>  
</html>  
