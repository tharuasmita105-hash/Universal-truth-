# Universal-truth-
<!DOCTYPE html>
<html>
<head>
    <title>Fun Page</title>
    <style>
        /* Rainbow Animated Background */
        body {
            margin: 0;
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            flex-direction: column;
            font-family: Arial, sans-serif;
            background: linear-gradient(45deg, red, orange, yellow, green, blue, indigo, violet);
            background-size: 400% 400%;
            animation: rainbow 8s ease infinite;
        }

        @keyframes rainbow {
            0% {background-position: 0% 50%;}
            50% {background-position: 100% 50%;}
            100% {background-position: 0% 50%;}
        }

        h1 {
            color: white;
            text-shadow: 2px 2px 5px black;
        }

        .btn {
            padding: 15px 30px;
            margin: 15px;
            font-size: 18px;
            border: none;
            border-radius: 30px;
            cursor: pointer;
            transition: 0.3s;
        }

        .btn:hover {
            transform: scale(1.1);
            box-shadow: 0 0 20px white;
        }

        .innocent {
            background-color: white;
            color: green;
        }

        .dirty {
            background-color: black;
            color: red;
        }
    </style>

    <script>
        function showInnocent() {
            alert("Pratik");
        }

        function showDirty() {
            alert("Reetu");
        }
    </script>
</head>

<body>

    <h1>Click Below</h1>

    <button class="btn innocent" onclick="showInnocent()">
        Most Innocent Person
    </button>

    <button class="btn dirty" onclick="showDirty()">
        Most Dirty Minded Person
    </button>

</body>
</html>
