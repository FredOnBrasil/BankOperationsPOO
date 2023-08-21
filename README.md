<!DOCTYPE html>
<html>
<head>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f3f4f6;
        }

        .header {
            background-color: #2980b9;
            color: #ffffff;
            text-align: center;
            padding: 2rem 0;
        }

        .container {
            max-width: 800px;
            margin: 0 auto;
            padding: 2rem;
            background-color: #ffffff;
            border-radius: 8px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }

        h1 {
            color: #333;
        }

        p {
            color: #555;
            line-height: 1.6;
        }

        .features {
            display: flex;
            justify-content: space-between;
            margin-top: 2rem;
        }

        .feature {
            flex-basis: calc(33.33% - 1rem);
            background-color: #2980b9;
            color: #ffffff;
            padding: 1.5rem;
            border-radius: 8px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }

        .feature h3 {
            margin-top: 0;
            color: #ffffff;
        }
    </style>
</head>
<body>
    <div class="header">
        <h1>BankOperationsPOO</h1>
        <p>Solução de Operações Bancárias usando Orientação a Objetos</p>
    </div>
    
    <div class="container">
        <h2>Recursos</h2>
        <p>Este repositório contém implementações das seguintes operações bancárias:</p>
        
        <div class="features">
            <div class="feature">
                <h3>Transferência</h3>
                <p>Realize transferências seguras entre contas bancárias.</p>
            </div>
            <div class="feature">
                <h3>Depósito</h3>
                <p>Faça depósitos em contas bancárias de forma conveniente.</p>
            </div>
            <div class="feature">
                <h3>Saque</h3>
                <p>Retire dinheiro de contas bancárias com facilidade.</p>
            </div>
            <div class="feature">
                <h3>Saldo</h3>
                <p>Verifique o saldo disponível em suas contas a qualquer momento.</p>
            </div>
        </div>
    </div>
</body>
</html>
