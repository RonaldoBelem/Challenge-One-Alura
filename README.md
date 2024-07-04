> Table of Contents
>
> <ul>
>   <li><a href="#-funcionalidades">Funcionalidades</a></li>
>   <li><a href="#-screenshots">Screenshots</a></li>
>   <li><a href="#-tecnologias">Tecnologias</a></li>
>   <li><a href="#-rodando-localmente">Rodando localmente</a></li>
>   <li><a href="#-como-contribuir-para-o-projeto">Como contribuir para o projeto</a></li>
> </ul>

## 💻 Sobre o projeto

Decodificador de texto feito com javascript, html e css. Minha resolução do challenge da Alura

## ✨ Funcionalidades

<p>Oferece a possibilidade de codificar e decodificar um texto inserido e copiar o texto resultante.</p>
<ul><strong>As "chaves" de criptografia utilizadas são:</strong></ul>
<li>A letra "e" é convertida para "enter"</li>
<li>A letra "i" é convertida para "imes"</li>
<li>A letra "a" é convertida para "ai"</li>
<li>A letra "o" é convertida para "ober"</li>
<li>A letra "u" é convertida para "ufat"</li>

## 🎨 Screenshots

<details><summary>Desktop:</summary>
<img src="./print do sistema/1.png" width="900"></details>

<details><summary>Tablet:</summary>

<img src="./print do sistema/2.png" width="600"></details>

<details><summary>Mobile:</summary>

<img src="./print do sistema/3.png" height="1000" ></details>

## 🛠 Tecnologias

- Javascript
- CSS
- HTML

## 🚀 Rodando localmente

Caso queira fazer modificações no site, siga estes passos:

Clone o projeto

```bash
  git clone https://github.com/RonaldoBelem/Challenge-One-Alura.git
```

Entre no diretório do projeto

```bash
  cd decodificador
```

E abra o <code>index.html</code> no navegador ou, caso use o VScode, instale a extensão [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) e clique no botão <ins><strong>Go Live</strong></ins>, se não pode instalar o http-server para que suas modificações sejam recarregadas automaticamente em seu navegador

```bash
  npm install http-server
```

Abra o servidor

```bash
  http-server ./
```

Será mostrado os links do servidor, clique ou copie e abra no navegador.

<p>Após a instalação do http-server também adicione um <code>.gitignore</code> com a pasta node_modules.</p>

Utilize o comando abaixo para saber mais sobre o http-server:

```bash
  npm docs http-server
```

## 😯 Como contribuir para o projeto

1. Faça um **fork** do projeto.
2. Crie uma nova branch com as suas alterações: `git checkout -b my-feature`
3. Salve as alterações e crie uma mensagem de commit contando o que você fez: `git commit -m "feature: My new feature"`
4. Envie as suas alterações: `git push origin my-feature`
   > Caso tenha alguma dúvida confira este [guia de como contribuir no GitHub](https://github.com/firstcontributions/first-contributions)
