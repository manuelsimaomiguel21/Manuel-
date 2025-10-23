


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



TABELA de Dados

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
    <title>Formulário de Candidatura Curto</title>
</head>
<body>

    <form action="/submissao-candidato-curto" method="POST" enctype="multipart/form-data">
        <h2>Formulário de Candidatura Profissional - CURTO</h2>

        <fieldset>
            <legend>Dados Pessoais Chave</legend>
            
            <label for="nome">Nome Completo:</label>
            <input type="text" id="nome" name="nome" value="Manuel Simão Miguel" required><br><br>

            <label for="documento">N.º do Bilhete de Identidade:</label>
            <input type="text" id="documento" name="bilhete" pattern="[A-Z0-9]{14}" title="Formato: 14 caracteres alfanuméricos" value="023078113LA052" required><br><br>

            <label for="nascimento">Data de Nascimento:</label>
            <input type="date" id="nascimento" name="data_nascimento" value="2004-01-15" required><br><br>
            
            <label for="contacto">Contacto Principal:</label>
            <input type="tel" id="contacto" name="contacto" value="942522308" required><br><br>

            <label for="email">E-mail:</label>
            <input type="email" id="email" name="email" value="manuelsimaomiguel21@gmail.com" required><br>
        </fieldset>

        <fieldset>
            <legend>Dados Académicos (Última Habilitação)</legend>
            
            <label for="nivel">Nível Académico:</label>
            <select id="nivel" name="nivel" required>
                <option value="">Selecione</option>
                <option value="basico">Ensino Básico</option>
                <option value="medio">Ensino Médio</option>
                <option value="licenciatura" selected>Licenciatura</option>
                <option value="mestrado">Mestrado</option>
            </select><br><br>
            
            <label for="curso">Designação do Curso:</label>
            <input type="text" id="curso" name="curso" value="Engenharia Informática" required><br><br>
            
            <label for="instituicao">Instituição:</label>
            <input type="text" id="instituicao" name="instituicao" value="Instituto Médio Comercial de Luanda" required><br>
        </fieldset>
</body>
</html>









