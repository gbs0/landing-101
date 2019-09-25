## Landing 101 Workshop - Fazendo sua Landing Page em 2 horas!
### 1º - Começamos criando nossa pasta e os arquivos que iremos utilizar:
> **Se preferir, faça o download do template por aqui! [HTML Boilerplate](https://github.com/gbs0/landing-101/tree/boilerplate)**

```
📂seu_projeto
 ┣ 📂components
 ┃ ┗ 📜banner.css
 ┃ ┗ 📜card.css
 ┃ ┗ 📜dashboard.css
 ┃ ┗ 📜footer.css
 ┃ ┗ 📜navbar.css
 ┣ 📂images
 ┃ ┗ 🖼briefcase.png
 ┃ ┗ 🖼diamond.png
 ┃ ┗ 🖼heart.png
 ┃ ┗ 🖼laptop.png
 ┣ 📜index.html
 ┗ 📜style.css
```

### 2º - No arquivo `index.html`, adicionaremos a estrutura da página HTML:

```
<!DOCTYPE html>
<html lang="pt-BR">
  <head>
    
  </head>
  <body>
    
    
  </body>
</html>

```

### 3º - Dentro da tag `<head>` do nosso HTML, iremos importar os meta dados de estilo:
> **Definindo conjuntos de acentos e nome na aba do navegador:**

```
  <head>
    <meta charset="utf-8">
    <title>Landing 101</title>
  </head>
``` 

> **Importando o documento de estilo:**

```
  <link rel="stylesheet" href="style.css">  
```

> **Configurando escala do ViewPort e compatibilidade com IE:**

```
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1">
```

> **Importando biblioteca do [Bootstrap](https://bootstrap.com):**

```
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/css/bootstrap.min.css" integrity="sha384-Gn5384xqQ1aoWXA+058RXPxPg6fy4IWvTNh0E263XmFcJlSAwiGgFAW/dAiS6JXm" crossorigin="anonymous">
```

> **Importando biblioteca de ícones do [FontAwesome](https://fontawesome.com):**

```
  <link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.4.1/css/all.css" integrity="sha384-5sAR7xN1Nv6T6+dT2mhtzEpVJvfS3NScPQTrOxhwjIuvcA67KV2R5Jz6kr4abQsz" crossorigin="anonymous">
 
```

### 4º - No arquivo  `style.css` iremos fazer os seguintes `imports`:

> **Import das Fontes (Source Sans e Montserrat):**

```
@import url("http://fonts.googleapis.com/css?family=Source+Sans+Pro|Montserrat:400,700");
```

> **Import da estilização dos componentes:**

```
@import url("components/banner.css");
@import url("components/card.css");
@import url("components/dashboard.css");
@import url("components/footer.css");
@import url("components/navbar.css");

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

