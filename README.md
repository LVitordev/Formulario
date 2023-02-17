# Formulario
Aula JS Udemy 

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        body {
            font-family: sans-serif;
        }

        table {
            border-collapse: collapse ;
            width: 800%;
        }

        table td, table th{
            border: 1px solid #ccc;
            padding: 5px;
            text-align: left;
        }
        
        table caption {
            caption-side: bottom;
            text-align:  center;
            font-style: italic;
            font-size: 14px;
            margin: 8px 0;
        }

        tfoot td, table th {
            background-color: #ddd;
        }

        tfoot td {
            font-style: italic;
        }

        .responsive-table {
          max-width: 100%;
          overflow-x: auto;
        }

        label {
            cursor: pointer;
            display: block;
        }

    </style>
</head>
<body>
    <form action="#" method="get" 
    target="_blank" autocomplete="off">
    <p>O meu formulário</p>
    <p>
        <label for="Nome:"></label>
      <input type="text" id="nome"
      nome="nome" placeholder="Seu nome" required> 
    </p>

    <p>
      Genero:<br>
      <label for="Masculino">Masculino</label>
      <input type="radio" id="Masculino" name="genero" value="Masculino"><br>

        <label for="Feminino">Feminino</label>
        <input type="radio" id="Feminino" name="genero" value="Feminino"><br>
     
       <label for="Outro">Outro</label>
       <input type="radio" id="Outro" name="genero" value="Outro"><br>
    </p>

      <p>
        <label for="nome">Date:</label>
        <input type="date" id="date" name="date" value="2023-02-09">
      </p>

      <p>
        <label for="datetime">Date:</label>
        <input type="datetime-local" id="datetime" name="datetime" value="2023-02-09T10:20">
      </p>

      <p>
        <label for="time">Date:</label>
        <input type="time" id="time" name="time" value="10:20">
      </p>

      <p>
        <label for="cor">Cor preferida:</label>
        <input type="color" id= "cor" name="cor" value="#32CD32">
      </p>

      <p>
        <label for="email">Seu e-mail:</label>
        <input type="email" id= "email" name="email" placeholder="ex.:email@email.com">
      </p>

      <p>
        <label for="file">Sua foto:</label>
        <input type="file" id= "file" name="file" accept=".png,.svg,image/*" multiple>
      </p>

      <p>
        <label for="number">Número:</label>
        <input type="number" id= "number" name="number"
         placeholder="Digite um número" min="10" max="50" step="5">
      </p>

    <p>
        <button type="reset">Reset</button>
        <button type="submit">Enviar</button>
    </p>

    <p>
      <label for="password">Sua senha:</label>
      <input type="password" id= "password" name="password" placeholder="Digite sua senha">
    </p>

    <p>
      <label for="url">Sua url:</label>
      <input type="search" id= "search" name="search">
    </p>

    <p>
      <label for="select">Selecione alguma opção:</label>
    <select name="select" id="select">
      <optgroup>
      <option value="qualquer 1" label="label 1">
      <option value="qualquer 1" label="label 2"
      disabled>
      <option value="qualquer 1" label="label 3"
      selected>
      <option value="qualquer 1" label="label 4">
    </optgroup>
    </select>
    </p>

    <p>
      <label for="textarea">textarea:</label>
      <textarea name="textarea" id="textarea" rows="8" cols="9">
           
      </textarea> 
    </p>

</form>
</body>
</html>
