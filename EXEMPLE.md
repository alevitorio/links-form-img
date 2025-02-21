
### 🏗️ **Projeto Prático: Página de Cadastro**
Eles vão criar uma página HTML onde um usuário pode cadastrar seu nome, e-mail e idade. A página terá um título, uma imagem ilustrativa, uma tabela com dados cadastrados e um formulário para adicionar novos usuários.

---

### **Código do Exemplo**
```html
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cadastro de Usuários</title>
</head>
<body>

    <!-- Título -->
    <h1>Cadastro de Usuários</h1>
    
    <!-- Imagem ilustrativa -->
    <img src="https://via.placeholder.com/300" alt="Imagem ilustrativa do cadastro">

    <!-- Tabela com usuários -->
    <h2>Usuários Cadastrados</h2>
    <table border="1">
        <tr>
            <th>Nome</th>
            <th>E-mail</th>
            <th>Idade</th>
        </tr>
        <tr>
            <td>Ana Souza</td>
            <td>ana@email.com</td>
            <td>25</td>
        </tr>
        <tr>
            <td>João Silva</td>
            <td>joao@email.com</td>
            <td>30</td>
        </tr>
    </table>

    <!-- Formulário para cadastrar usuários -->
    <h2>Preencha seus dados</h2>
    <form action="#" method="post">
        <fieldset>
            <legend>Dados Pessoais</legend>
            
            <label for="nome">Nome:</label>
            <input type="text" id="nome" name="nome" placeholder="Digite seu nome">
            <br><br>

            <label for="email">E-mail:</label>
            <input type="email" id="email" name="email" placeholder="Digite seu e-mail">
            <br><br>

            <label for="idade">Idade:</label>
            <input type="number" id="idade" name="idade" placeholder="Digite sua idade">
            <br><br>

            <button type="submit">Cadastrar</button>
        </fieldset>
    </form>

</body>
</html>
```

---

### **Atividades para os alunos** 🏆
1. **Testar o código**: Pedir para eles copiarem e rodarem no navegador.
2. **Modificar os dados da tabela**: Alterar ou adicionar mais usuários.
3. **Explorar atributos**: Testar atributos como `placeholder`, `required` e `maxlength` no formulário.
4. **Adicionar um novo campo**: Exemplo: "Telefone".
5. **Personalizar a página**: Inserir outra imagem ou mudar os títulos.

Esse exercício vai ajudar os alunos a consolidarem os conceitos aprendidos na teoria de maneira prática! 🚀