css
Copiar código
/* Reset básico para garantir consistência */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

/* Estilo geral da página */
body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    background-color: #f4f4f4;
    color: #333;
}

/* Cabeçalho */
header {
    background: #333;
    color: #fff;
    padding: 10px 0;
    text-align: center;
}

header h1 {
    margin: 0;
    font-size: 2em;
}

nav ul {
    list-style: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin: 0 10px;
}

nav ul li a {
    color: #fff;
    text-decoration: none;
    font-weight: bold;
}

/* Seções */
section {
    padding: 20px;
    margin: 0 10px;
    background: #fff;
    border-radius: 5px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

h2 {
    margin-bottom: 10px;
}

/* Listas */
ul {
    list-style: disc;
    margin-left: 20px;
}

li {
    margin-bottom: 10px;
}

/* Rodapé */
footer {
    background: #333;
    color: #fff;
    text-align: center;
    padding: 10px 0;
    position: fixed;
    bottom: 0;
    width: 100%;
}
