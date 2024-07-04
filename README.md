# Soccer-test1
Encuesta futbol
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Encuesta sobre campeonatos de fútbol 2024</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="survey-container">
        <h1>Encuesta sobre campeonatos de fútbol 2024</h1>
        <form id="surveyForm">
            <div class="question">
                <p>¿Cree que Alemania será el campeón de la Eurocopa 2024?</p>
                <label>
                    <input type="radio" name="eurocopa" value="sí">
                    Sí
                </label><br>
                <label>
                    <input type="radio" name="eurocopa" value="no">
                    No
                </label>
            </div>
            <div class="question">
                <p>¿Quién cree que será el campeón de la Copa América 2024?</p>
                <label>
                    <input type="radio" name="copa_america" value="colombia">
                    Colombia
                </label><br>
                <label>
                    <input type="radio" name="copa_america" value="argentina">
                    Argentina
                </label><br>
                <label>
                    <input type="radio" name="copa_america" value="costa_rica">
                    Costa Rica
                </label>
            </div>
            <button type="submit">Votar</button>
        </form>
        <p id="message"></p>
    </div>
    <script src="scripts.js"></script>
</body>
</html>
