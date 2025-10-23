

# Manuel-
Dalinha 


<table border="1">
  <tr>
    <th>Produto</th>
    <th>Descrição</th>
    <th>Preço</th>
  </tr>
  <tr>
    <td>Vitrum Homem</td>
    <td>Suplemento multivitamínico para homens</td>
    <td> 20,000Kz</td>
  </tr>
  <tr>
    <td>Cetrum</td>
    <td>Suplemento mulivitamínico</td>
    <td>15,000Kz</td>
  </tr>
  <tr>
    <td>Creatina</td>
    <td>Suplemento</td>
    <td>10,000Kz</td>
  </tr>
</table>


TABELA DE DADOS PESSOAIS 

<table border="1" 
    <td>
        Tabela
    </caption>
    <thead>
        <tr>
            <th>Categoria</th>
            <th>Campo</th>
            <th>Dados</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td rowspan="10" style="font-weight: bold; border-right: 2px solid #ccc; padding: 8px;">Dados Pessoais</td>
            <td>Nome Completo</td>
            <td>Manuel Simão Miguel</td>
        </tr>
        <tr>
            <td style="padding: 8px;">N.º do Bilhete de Identidade</td>
            <td style="padding: 8px;">AO001234567890</td>
        </tr>
        <tr>
            <td style="padding: 8px;">Data de Emissão do BI</td>
            <td style="padding: 8px;">2022-02-2</td>
        </tr>
        <tr>
            <td style="padding: 8px;">Data de Nascimento</td>
            <td style="padding: 8px;">2004-01-15</td>
        </tr>
        <tr>
            <td style="padding: 8px;">Naturalidade (Município/Província)</td>
            <td style= <td>Cazenga/Luanda</td>
        </tr>
        <tr>
            <td>Nome Completo da Mãe</td>
            <td>Felismina César</td>
        </tr>
        <tr>
            <td>Nome Completo do Pai</td>
            <td> Felipe Manuel</td>
        </tr>
        <tr>
            <td>Estado Civil</td>
            <td>Solteiro</td>
        </tr>
        <tr>
            <td>Contacto Principal (Telefone)</td>
            <td>942522308</td>
        </tr>
        <tr>
            <td>E-mail</td>
            <td>manuelsimaomigue21@gmail.com</td>
        </tr>

        <tr style="background-color: #f9f9f9;">
            <td rowspan="4" style="font-weight: bold; border-right: 2px solid #ccc; padding: 8px;">Endereço de Residência</td>
            <td style="padding: 8px;">Província</td>
            <td style="padding: 8px;">Luanda</td>
        </tr>
        <tr style="background-color: #f9f9f9;">
            <td style="padding: 8px;">Município</td>
            <td style="padding: 8px;">Cazenga</td>
        </tr>
        <tr style="background-color: #f9f9f9;">
            <td style="padding: 8px;">Bairro</td>
            <td style="padding: 8px;">SINEK</td>
        </tr>
        <tr style="background-color: #f9f9f9;">
            <td>Rua/Casa N.º</td>
            <td>Rua 1, Casa N.º 45</td>
        </tr>

        <tr>
            <td rowspan="4" style="font-weight: bold; border-right: 2px solid #ccc; padding: 8px;">Dados Académicos</td>
            <td>Nível Académico</td>
            <td>Médio</td>
        </tr>
        <tr>
            <td>Instituição de Ensino</td>
            <td>Instituto Médio Comrcial De Luanda</td>
        </tr>
        <tr>
            <td>Designação do Curso</td>
            <td>Engenharia Informática</td>
        </tr>
        <tr>
            <td>Ano de Conclusão</td>
            <td>2027</td>
        </tr>
    </tbody>
</table>



Formulário 
<!DOCTYPE html>
<html lang="pt">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Formulário de Candidatura Completo</title>
    <style>
        /* CSS simples para melhor visualização, você pode remover ou expandir isso */
        body { font-family: Arial, sans-serif; margin: 20px; }
        fieldset { border: 1px solid #ccc; padding: 15px; margin-bottom: 20px; border-radius: 5px; }
        legend { font-weight: bold; padding: 0 10px; color: #333; }
        label { display: inline-block; width: 150px; margin-bottom: 5px; }
        input[type="text"], input[type="tel"], input[type="date"], input[type="number"], select, input[type="file"] {
            width: 300px;
            padding: 8px;
            margin-bottom: 10px;
            border: 1px solid #ddd;
            border-radius: 4px;
            box-sizing: border-box; /* Inclui padding e borda na largura total */
        }
        input[type="submit"] {
            background-color: #4CAF50;
            color: white;
            padding: 10px 15px;
            border: none;
            border-radius: 4px;
            cursor: pointer;
            font-size: 16px;
        }
        input[type="submit"]:hover {
            background-color: #45a049;
        }
    </style>
</head>
<body>

    <form action="/submissao-candidato" method="POST" enctype="multipart/form-data">
        <h2>Formulário de Candidatura Profissional</h2>

        <fieldset>
            <legend>Dados Pessoais (Conforme o Bilhete de Identidade)</legend>
            
            <label for="nome">Nome Completo:</label>
            <input type="text" id="nome" name="nome" value=" Manuel Simão Miguel" required><br>

            <label for="documento">N.º do Bilhete de Identidade:</label>
            
            <input type="text" id="documento" name="bilhete" pattern="[A-Z0-9]{14}" title="Formato: 14 caracteres alfanuméricos" value="023078113LA052" required><br>

            <label for="data_emissao">Data de Emissão do BI:</label>
            <input type="date" id="data_emissao" name="data_emissao" value="2022-02-02" required><br>

            <label for="nascimento">Data de Nascimento:</label>
            <input type="date" id="nascimento" name="data_nascimento" value="2004-01-15" required><br>
            
            <label for="naturalidade">Naturalidade (Município/Província):</label>
            <input type="text" id="naturalidade" name="naturalidade" value="Viana/Luanda" required><br>
            
            <label for="mae">Nome Completo da Mãe:</label>
            <input type="text" id="mae" name="mae" value="Felismia Tchimbapo César" required><br>

            <label for="pai">Nome Completo do Pai:</label>
            <input type="text" id="pai" name="pai" value="Filipe Diogo Manuel " required><br>

            <label for="estado_civil">Estado Civil:</label>
            <select id="estado_civil" name="estado_civil" required>
                <option value="">Selecione</option>
                <option value="solteiro" selected>Solteiro(a)</option>
                <option value="casado">Casado(a)</option>
                <option value="divorciado">Divorciado(a)</option>
                <option value="viuvo">Viúvo(a)</option>
            </select><br>
            
            <label for="contacto">Contacto Principal (Telefone):</label>
            <input type="tel" id="contacto" name="contacto" value="942522308" required><br>

            <label for="email">E-mail:</label>
            <input type="email" id="email" name="email" value="manuelsimaomiguel21@gmail.com" required><br>
        </fieldset>

        <fieldset>
            <legend>Endereço de Residência</legend>
            <label for="provincia">Província:</label>
            <input type="text" id="provincia" name="provincia" value="Luanda" required><br>

            <label for="municipio">Município:</label>
            <input type="text" id="municipio" name="municipio" value="Cazenga" required><br>

            <label for="bairro">Bairro:</label>
            <input type="text" id="bairro" name="bairro" value="Simeke" required><br>

            <label for="rua">Rua/Casa N.º:</label>
            <input type="text" id="rua" name="rua" value="Rua G, Casa N.º 23"><br>
        </fieldset>

        <fieldset>
            <legend>Dados Académicos (Última Habilitação)</legend>
            <label for="nivel">Nível Académico:</label>
            <select id="nivel" name="nivel" required>
                <option value="">Selecione</option>
                <option value="basico">Ensino Básico (9ª Classe)</option>
                <option value="medio">Ensino Médio (12ª ou 13ª Classe)</option>
                <option value="bacharelato">Bacharelato</option>
                <option value="licenciatura" selected>Licenciatura</option>
                <option value="mestrado">Mestrado</option>
                <option value="doutoramento">Doutoramento</option>
            </select><br>
            
            <label for="instituicao">Instituição de Ensino:</label>
            <input type="text" id="instituicao" name="instituicao" value="Universidade Exemplo de Luanda (UEL)" required><br>

            <label for="curso">Designação do Curso:</label>
            <input type="text" id="curso" name="curso" value="Engenharia Informática" required><br>
            
            <label for="ano_conclusao">Ano de Conclusão:</label>
            <input type="number" id="ano_conclusao" name="ano_conclusao" min="1950" max="2025" value="2016" required><br>
           
        <input type="submit" value="Enviar Candidatura">
    </form>

</body>
</html>
