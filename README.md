# Desafio: Merge com Conflito

Este repositório contém o desafio de realizar um merge com conflito utilizando Git. Desafio proposto pela Devsuperior no módulo de Git e Github como exercício para treinar a criação de branches, trabalho em equipe e solução de conflitos no momento de fazer o merge na 
branch principal.Abaixo estão as instruções detalhadas para reproduzir o processo.

## Instruções

1. (branch main) Crie um arquivo "index.html" contendo o código a seguir:

```
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Document</title>
  </head>
  <body>
    <h1>Página inicial</h1>
    <p>Sejam bem-vindos ao nosso website</p>
  </body>
</html>
```


2. (branch main) salve um commit: "Projeto criado"
3. (branch main) crie um novo arquivo "catalogo.html" com um código HTML básico.
4. (branch main) acrescente também no código do arquivo "index.html" uma tag <a> com link para a página
"catalogo.html", similar ao código abaixo:

```bash
<a href="catalogo.html">Ir para a página de catálogo</a>
```

5. (branch main) salve um novo commit: "Página catálogo"
6. (branch main) modifique o arquivo "catalogo.html" como você desejar, daí salve um novo commit:
"Catálogo update"
7. Envie o projeto para o Github
8. (branch main) A partir do commit "Catálogo update", crie um novo branch "ft-sobre"
9. (branch main) A partir do commit "Catálogo update", crie um novo branch "ft-blog"
10. (branch ft-sobre) Crie um novo arquivo "sobre.html" com um código HTML básico.
11. (branch ft-sobre) Acrescente também no código do arquivo "index.html" uma tag <a> com link para a
página "sobre.html", similar ao código abaixo:

```bash
<a href="sobre.html">Sobre nós</a>
```


12. (branch ft-sobre) Salve um novo commit "Página sobre"
13. Envie o branch ft-sobre para o Github, crie um pull request, aceite o pull request, e NÃO apague o branch.

14. (branch ft-blog) Crie um novo arquivo "blog.html" com um código HTML básico.
15. (branch ft-blog) Acrescente também no código do arquivo "index.html" uma tag <a> com link para a
página "blog.html". Além disso, MUDE O TEXTO do link para a página "sobre.html". Deve ficar similar
ao código abaixo:

```bash
<a href="sobre.html">Conheça a empresa</a>
<a href="blog.html">Acesse o blog</a>
```

16. (branch ft-blog) Salve um novo commit "Página blog"

![Captura de tela de 2024-09-03 11-34-43](https://github.com/user-attachments/assets/55503d15-759a-4dc1-b9ab-16f933c10af9)


17. (branch ft-blog) Agora faça o merge do branch main para o branch ft-blog, resolva os conflitos, envie e
aprove um pull request do branch ft-blog no seu repositório remoto. NÃO apague o branch ft-blog. O
resultado final deve ficar como mostrado abaixo.

![Captura de tela de 2024-09-03 11-33-42](https://github.com/user-attachments/assets/986cd2e3-73af-4a56-bf29-850f93c4321c)

