# Carteira-virtual-da-federa-o-pernambucana
O projeto consiste no desenvolvimento de uma Carteira Digital de Atleta, uma plataforma online inovadora para a Federação Pernambucana de Futsal (FPFS) e a Confederação Brasileira de Futsal (CBFS). O objetivo principal é modernizar e digitalizar o processo de registro e inscrição de atletas, substituindo a tradicional carteirinha fisica.
Linguagens  CSS e HTML

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
                Foto 3x4 
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
