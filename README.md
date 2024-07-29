# Agrinho
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #8BC34A; /* Fundo verde */
}

header {
    background-color: #3E8E41; /* Verde mais escuro para o cabeçalho */
    color: #fff;
    padding: 1em;
    text-align: center;
}

header nav ul {
    list-style: none;
    margin: 0;
    padding: 0;
    display: flex;
    justify-content: space-between;
}

header nav ul li {
    margin-right: 20px;
}

header nav a {
    color: #fff;
    text-decoration: none;
}

.hero {
    background-image: url('![imagem_2024-07-29_145208356](https://github.com/user-attachments/assets/3a33f73e-c94b-4c68-829c-c6efde2e3578)');
    background-size: cover;
    background-position: center;
    height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
    color: #fff;
}

.hero h1 {
    font-size: 48px;
}

.hero p {
    font-size: 18px;
}

button {
    background-color: #3E8E41; /* Verde mais escuro para os botões */
    color: #fff;
    border: none;
    padding: 10px 20px;
    font-size: 18px;
    cursor: pointer;
}

button:hover {
    background-color: #4CAF50; /* Verde mais claro para o hover */
}

.sobre {
    padding: 2em;
}

.servicos {
    padding: 2em;
}

.servicos ul {
    list-style: none;
    margin: 0;
    padding: 0;
}

.servicos li {
    margin-bottom: 10px;
}

.servicos i {
    margin-right: 10px;
}

.contato {
    padding: 2em;
}

.contato form {
    display: flex;
    flex-direction: column;
    align-items: center;
}

.contato input, .contato textarea {
    width: 100%;
    padding: 10px;
    margin-bottom: 10px;
    border: none;
    border: radius 4px;}
