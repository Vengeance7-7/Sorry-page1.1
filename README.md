# Sorry-page1.1
For her
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Apology & Love</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background: url('https://www.shutterstock.com/search/heart-background') no-repeat center center fixed;
            background-size: cover;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            overflow: hidden;
            color: white;
        }

        .container {
            text-align: center;
            padding: 40px;
            background-color: rgba(0, 0, 0, 0.7);
            border-radius: 10px;
            width: 90%;
            max-width: 500px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
            opacity: 0;
            animation: fadeIn 2s forwards;
        }

        h1 {
            font-size: 36px;
            color: #ffcccb;
            animation: bounce 2s infinite;
        }

        p {
            font-size: 18px;
            line-height: 1.5;
            margin-top: 20px;
            animation: fadeInText 2s 1s forwards;
        }

        button {
            margin-top: 20px;
            padding: 15px 25px;
            font-size: 18px;
            background-color: #ff6699;
            border: none;
            border-radius: 5px;
            color: white;
            cursor: pointer;
            opacity: 0;
            animation: fadeInButton 2s 1.5s forwards;
            transition: transform 0.3s ease-in-out;
        }

        button:hover {
            transform: scale(1.1);
        }

        .toggle-container {
            margin-top: 20px;
        }

        .toggle-container label {
            font-size: 20px;
            font-weight: bold;
        }

        .toggle-buttons {
            display: flex;
            justify-content: center;
            margin-top: 10px;
        }

        .toggle-buttons input {
            margin: 0 15px;
        }

        @keyframes fadeIn {
            from {
                opacity: 0;
            }
            to {
                opacity: 1;
            }
        }

        @keyframes fadeInText {
            from {
                opacity: 0;
            }
            to {
                opacity: 1;
            }
        }

        @keyframes fadeInButton {
            from {
                opacity: 0;
            }
            to {
                opacity: 1;
            }
        }

        @keyframes bounce {
            0% {
                transform: translateY(0);
            }
            50% {
                transform: translateY(-10px);
            }
            100% {
                transform: translateY(0);
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>I'm Sorry... Can We Talk?</h1>
        <p>I've been thinking about this for a while, and I need to express how much I care. My actions might've hurt you, and that wasn't my intention. Please know how deeply I regret it, and I hope we can make things better.</p>
        
        <button onclick="showMessage()">I’m Listening...</button>

        <div class="toggle-container">
            <label>Do you love the person who sent this to you?</label>
            <div class="toggle-buttons">
                <input type="radio" id="yes1" name="love" value="yes">
                <label for="yes1">Yes, I do</label>
                <input type="radio" id="yes2" name="love" value="yes">
                <label for="yes2">Yes, I do</label>
            </div>
        </div>
    </div>

    <!-- Embed song and autoplay -->
    <iframe allow="autoplay *; encrypted-media *; fullscreen *; clipboard-write" frameborder="0" height="450" style="width:100%;max-width:660px;overflow:hidden;border-radius:10px;" sandbox="allow-forms allow-popups allow-same-origin allow-scripts allow-storage-access-by-user-activation allow-top-navigation-by-user-activation" src="https://embed.music.apple.com/us/album/die-with-a-smile-single/1762656724?app=music&at=10lw9d&ct=top5&itscg=30200&itsct=music_link"></iframe>

    <script>
        function showMessage() {
            const p = document.querySelector('p');
            p.innerHTML = 'I want to hear what’s on your heart, no matter what. I care deeply and I want to make it right.';
            p.style.color = '#ffcccb';
            p.style.fontWeight = 'bold';
        }
    </script>
</body>
</html>
