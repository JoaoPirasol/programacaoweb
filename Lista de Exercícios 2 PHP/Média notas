<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Calcular Média das Notas</title>
</head>
<body>
    <h2>Insira as três notas para calcular a média:</h2>
    <form method="post" action="">
        Nota 1: <input type="number" step="0.01" name="nota1" required><br><br>
        Nota 2: <input type="number" step="0.01" name="nota2" required><br><br>
        Nota 3: <input type="number" step="0.01" name="nota3" required><br><br>
        <input type="submit" name="calcular" value="Calcular Média">
    </form>

    <?php
    if (isset($_POST['calcular'])) {
        $nota1 = $_POST['nota1'];
        $nota2 = $_POST['nota2'];
        $nota3 = $_POST['nota3'];

        // Calcula a média
        $media = ($nota1 + $nota2 + $nota3) / 3;

        // Exibe o resultado
        echo "<h3>A média das notas é: " . number_format($media, 2) . "</h3>";
    }
    ?>
</body>
</html>
