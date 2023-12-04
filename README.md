<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Weather App</title>
    <h1>Currently 21&#8451 in Tokyo</h1>
    <style>
        h1 {
            color: blue;
            text-align: center;
            font-size: 25px;
        }

        h2 {
            text-align: center;
            font-size: 20px;
        }

        .message {
            text-align: center;
            color: black;
            font-size: 15px;
            padding: 15px 20px;
        }

        .tomorrow {
            text-align: center;
            color: black;
            font-size: 10px;
        }

        ul {
            padding: 0;
        }

        li {
            list-style: none;
            text-align: center;
            padding: 10px 0;
            border-radius: 10px;
            transition: all 200ms ease-in-out;
            max-width: 400px;
            margin: 0 auto;
        }

        button {
            color: white;
            background: blue;
            padding: 15px 20px;
            display: block;
            margin: 0 auto;
            border: 1px solid blue;
            border-radius: 30px;
            transition: all 200ms ease-in-out;
            box-shadow: rgba(37, 39, 89, 0.08) 0px 8px 8px 0;
        }

        button-hover {
            background: white;
            color: blue;
            cursor: pointer;
        }
    </style>
    <h2>13&#8451 / 23&#8451</h2>

</head>

<body>
    <div class="message">
        <strong>
            <div>Tomorrow</div>
        </strong>
        10&#8451 / 22&#8451
        <ul>
            <li>
                <strong>
                    Saturday
                </strong>
            </li>
            <li>
                15&#8451 / 27&#8451
            </li>
            <li>
                <strong>
                    Sunday
                </strong>
            </li>
            <li>
                25&#8451 / 28&#8451
            </li>
        </ul>
        <button>
            Change city
        </button>
</body>

</html>
