<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        .out {
            border: 1.5px solid black;
            width: 320px;
            height: 510px;
            position: relative;
            left: 550px;
            bottom: 5px;
            top: 52px;
            background-color: rgba(215, 213, 210, 0.934);
            border-radius: 20px;
            overflow: auto;
            box-shadow: 20px 18px 20px rgba(0, 0, 0, 0.91);

        }


        .imgg {
            border: 1.5px solid green;
            width: 280px;
            height: 237px;
            position: absolute;
            top: 75px;
            bottom: 1px;
            left: 579px;
            border-radius: 20px;
            overflow: hidden;
        }

        .imgg img {
            width: 100%;
            height: 100%;
            object-fit: cover;
        }

        div li {
            list-style: none;
            border: 1px solid black;
            padding: 5px;
            border-radius: 20px;
            font-size: 13px;
            background-color: aliceblue;
            box-shadow: 3px 3px 3px rgb(38, 63, 68);
            background-color: #ab93936b;


        }

        div ul {
            display: flex;
            padding: 10px;
            margin: 10px;
            gap: 20px;
            position: absolute;
            left: 566px;
            top: 320px;
        }

        h1 {
            position: absolute;
            left: 591px;
            top: 374px;
            font-size: 20px;
            text-decoration: underline;

        }

        p {
            position: absolute;
            left: 589px;
            top: 406px;
            width: 280px;
            height: auto;
            overflow: auto;
        }

        button {
            position: absolute;
            left: 677px;
            top: 534px;
            text-align: center;
            background-color: beige;
            border-radius: 20px;
            cursor: pointer;
            box-shadow: 3px 3px 3px rgb(38, 63, 68);
        }
    </style>
</head>

<body>
    <div>
        <p class="out card">
        <p class="imgg">
            <img
                src="https://images.unsplash.com/photo-1564507592333-c60657eea523?w=600&auto=format&fit=crop&q=60&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxzZWFyY2h8M3x8dGFqJTIwbWFoYWwlMjBhZ3JhJTIwaW5kaWF8ZW58MHx8MHx8fDA%3D">
        <ul>
            <li>Taj Mahal</li>
            <li>7th Wonder's of the world</li>
        </ul>
        <h1>TAJ MAHAL</h1>
        <p>The Taj Mahal, symbol of eternal love, stands majestically in Agra, inspiring millions with its beautiful
            white marble architecture.
        </p>

        <button onclick="window.open('https://en.wikipedia.org/wiki/Taj_Mahal', '_blank')">Click here!</button>


        </p>
        </p>
    </div>
</body>

</html>
