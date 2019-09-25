## Landing 101 Workshop | 
### 1º - Começamos criando nossa pasta e os arquivos que iremos utilizar:
> **Se preferir, faça o download do template por aqui! [HTML Boilerplate](https://github.com/gbs0/landing-sprint)**

```
📂seu_projeto
 ┣ 📂components
 ┃ ┗ 📜banner.css
 ┃ ┗ 📜card.css
 ┃ ┗ 📜dashboard.css
 ┃ ┗ 📜footer.css
 ┃ ┗ 📜navbar.css
 ┣ 📂images
 ┃ ┗ 📜briefcase.png
 ┃ ┗ 📜card.png
 ┃ ┗ 📜dashboard.png
 ┃ ┗ 📜footer.png
 ┃ ┗ 📜navbar.png
 ┣ 📜index.html
 ┗ 📜style.css
```

### 2º - No arquivo `index.html`, adicionaremos a estrutura da página HTML:
```
<!DOCTYPE html>
  <html>
    <head>
		

    </head>
    <body>
	
    </body>
</html>
```

### 3º - Dentro da tag `<head>` do nosso HTML, iremos importar os meta dados de estilo:
> **Definindo conjuntos de acentos e nome na aba:**


```
<head>
    <meta charset="utf-8">
    <title>CSS Components Sprint</title>
 </head>
``` 

> **Importando documento de estilo:**

```
  <link rel="stylesheet" href="style.css">  
```

> **Configurando escala do ViewPort:**

```
 <meta name="viewport" content="width=device-width, initial-scale=1">
```

> **Importando biblioteca do [Bootstrap](https://bootstrap.com) em `JS` e `CSS`:**

```
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.2.0/css/bootstrap.min.css">
  <script defer src="https://maxcdn.bootstrapcdn.com/bootstrap/3.2.0/js/bootstrap.min.js"></script>
```

> **Importando biblioteca de ícones do [FontAwesome](https://fontawesome.com):**

```
 <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/font-awesome/4.1.0/css/font-awesome.min.css">
 
```

> **Importando biblioteca JQuery:**

```
  <script defer src="https://ajax.googleapis.com/ajax/libs/jquery/1.11.1/jquery.min.js"></script>
```
### 4º - Na tag `<body>`, iremos organizar o resto de nosso conteúdo:
```
<body>

    <div class="container">
      <h1 class="text-center">CSS Components Sprint</h1>

      <h2>Avatar design</h2>
      
      
      <h2>Image Desing</h2>
      

      <h2>Button design</h2>
      

      <h2>Badge design</h2>
      

      <h2>Dropdown design</h2>
        

      <h2>Form Desing</h2>
      

      <h2>Card design</h2>
      

      <h2>Banner design</h2>
      

      <h2>List design</h2>
      

      <h2>Pagination Design</h2>
      
    </div>
  </body>
```
****
### 5º - No arquivo  `style.css` iremos fazer os seguintes `imports`:

> **Import das Fontes (Source Sans e Montserrat):**

```
@import url("http://fonts.googleapis.com/css?family=Source+Sans+Pro|Montserrat:400,700");
```

> **Import da estilização dos componentes:**

```
@import url("components/avatar.css");
@import url("components/button.css");
@import url("components/badge.css");
@import url("components/dropdown.css");
@import url("components/card.css");
@import url("components/banner.css");
@import url("components/list.css");

```

> **Estilização do corpo da página do projeto:**

```
body {
  font-family: 'Source Sans Pro', sans-serif;
  padding-bottom: 200px;
  padding-left: 100px;
}
```

> **Tipografia dos headers e titulos da página:**

```
h1, h2, h3 {
  font-family: "Montserrat", "sans-serif";
}
```

