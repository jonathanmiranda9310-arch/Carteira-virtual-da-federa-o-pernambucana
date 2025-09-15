# Carteira-virtual-da-federa-o-pernambucana
O projeto consiste no desenvolvimento de uma Carteira Digital de Atleta, uma plataforma online inovadora para a Federação Pernambucana de Futsal (FPFS) e a Confederação Brasileira de Futsal (CBFS). O objetivo principal é modernizar e digitalizar o processo de registro e inscrição de atletas, substituindo a tradicional carteirinha fisica.
Linguagens  CSS e HTML
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Carteira de atleta da federação pernambucana</title>
    <style>
        body {
            background: #e9ecef;
            font-family: Arial, sans-serif;
            min-height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
        }
        .carteirinha {
            background: #fff;
            border-radius: 24px;
            box-shadow: 0 2px 8px rgba(0,0,0,0.10);
            width: 600px;
            padding: 18px 24px;
            border: 10px solid #3a3fb0;
            position: relative;
        }
        .topo {
            display: flex;
            align-items: flex-start;
            justify-content: space-between;
            margin-bottom: 12px;
        }
        .escudo {
            width: 120px;
            height: 120px;
            background: none;
            display: flex;
            align-items: center;
            justify-content: center;
        }
        .escudo img {
            max-width: 110px;
            max-height: 110px;
        }
        .dados-topo {
            flex: 1;
            margin-left: 12px;
            margin-right: 12px;
        }
        .dados-topo h1 {
            font-size: 2.8em;
            margin: 0 0 8px 0;
            text-align: left;
            color: #3a3fb0;
            font-weight: bold;
            letter-spacing: 2px;
        }
        .dados-topo .info {
            font-size: 1.3em;
            color: #3a3fb0;
            font-weight: bold;
            margin-bottom: 2px;
        }
        .dados-topo .info span {
            font-weight: normal;
        }
        .foto {
            width: 110px;
            height: 110px;
            border: 5px solid #3a3fb0;
            border-radius: 10px;
            background: #e9ecef;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 1em;
            color: #3a3fb0;
        }
        table {
            width: 100%;
            border-collapse: separate;
            border-spacing: 0;
            margin-top: 10px;
            margin-bottom: 10px;
        }
        th, td {
            padding: 10px 12px;
            font-size: 1.2em;
            text-align: left;
        }
        th {
            background: #3a3fb0;
            color: #fff;
            font-weight: bold;
            width: 140px;
            border-radius: 8px 0 0 8px;
            border : 1px solid #000000;
        }
        td {
            background: #3a3fb0;
            color: #fff;
            border-radius: 0 8px 8px 0;
            border : 1px solid #000000;
        }
        .assinatura {
            text-align: left;
            margin-top: 12px;
            font-size: 1.2em;
            color: #3a3fb0;
            font-weight: bold;
        }
        .assinatura .presidente {
            font-size: 1em;
            font-weight: normal;
        }
        .validade {
            position: absolute;
            right: 32px;
            bottom: 32px;
            text-align: right;
            color: #3a3fb0;
            font-size: 1.3em;
            font-weight: bold;
        }
        .validade .data {
            font-size: 1.6em;
        }
    </style>
</head>
<body>
    <div class="carteirinha">
        <div class="topo">
            <div class="escudo">
                <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQP2EeTBQKHps7hTpzcJGgkln4NmqWU3OUQWw&s" alt="FPFS">
            </div>
            <div class="dados-topo">
                <h1>ATLETA</h1>
                <div class="info">CBFS: <span><input type="text" value="215198" style="width:80px;"></span></div>
                <div class="info">CATEGORIA: <span><input type="text" value="Veterano" style="width:110px;"></span></div>
                <div class="info"><input type="text" value="30/10/1984" style="width:110px;"> - <input type="text" value="40 anos" style="width:70px;"></div>
            </div>
            <div class="foto">
                Foto 3x4 <!-- adicione a foto do atleta aqui-->

            </div>
        </div>
        <table>
            <tr>
                <th>NOME:</th>
                <td><input type="text" value="NOME SOBRENOME" style="width:100%;background:transparent;border:none;color:#fff;font-weight:bold;"></td>
            </tr>
            <tr>
                <th>CLUBE:</th>
                <td><input type="text" value="SPORT CLUBE DE RECIFE" style="width:100%;background:transparent;border:none;color:#fff;font-weight:bold;"></td>
            </tr>
            <tr>
                <th>CPF:</th>
                <td><input type="text" value="169-222-333-94" style="width:100%;background:transparent;border:none;color:#fff;font-weight:bold;"></td>
            </tr>
        </table>
        <div class="assinatura">
            LUIZ CLAUDIO DE CARVALHO<br>
            <span class="presidente">PRESIDENTE</span>
        </div>
        <div class="validade">
           <label for="validade">VALIDADE:</label>
            <span class="data">
                <input type="text" value="31 / 12 / 2024" style="width:120px;background:transparent;border:none;color:#3a3fb0;font-size:0.5em;font-weight:bold;text-align:right;"></span>
        </div>
    </div>
</body>
</html>
