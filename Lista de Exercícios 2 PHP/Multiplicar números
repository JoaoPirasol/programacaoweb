<!DOCTYPE html>
<html>
<head>
    <title>Multiplicar dois números</title>
</head>
<body>
    <form method="post" action="">
        Número 1: <input type="number" name="num1" required><br><br>
        Número 2: <input type="number" name="num2" required><br><br>
        <input type="submit" name="submit" value="Multiplicar">
    </form>

    <?php
    if (isset($_POST['submit'])) {
        $num1 = $_POST['num1'];
        $num2 = $_POST['num2'];
        $multiplicacao = $num1 * $num2;
        echo "A multiplicação de $num1 por $num2 é: $multiplicacao";
    }
    ?>
</body>
</html>
