# Site Apresentação Halloween

Um projeto prototipado para uma avaliação de HTML e CSS utilizando Bootstrap, com foco em uma landing page temática de Halloween. A interface reúne informações sobre a origem da festa, ideias de fantasias, receitas e curiosidades, apresentando um visual moderno e responsivo.

## Visão Geral e Contexto

Este repositório foi criado para demonstrar como construir uma página estática atrativa e funcional usando tecnologias web básicas, sem a necessidade de backend ou banco de dados. O projeto resolve a necessidade de apresentar informações sobre o Halloween de forma visual, organizada e acessível, utilizando seções com cards, carousel, modais e elementos interativos do Bootstrap.

A aplicação funciona como uma "página de apresentação" ou "landpage" com conteúdo informativo e amigável, ideal para fins didáticos, prototipagem ou avaliação acadêmica.

## Tecnologias Utilizadas

- HTML5
- CSS3
- JavaScript
- Bootstrap 5
- Font Awesome
- Imagens locais em JPG/PNG

## Estrutura do Projeto

- `index.html` — estrutura principal da página
- `css/` — arquivos de estilo e Bootstrap
- `js/` — scripts do Bootstrap
- `fontawesome/` — ícones da biblioteca Font Awesome
- `img/` — imagens da interface e da temática do Halloween

## Instruções de Execução

Como o projeto é uma página estática, não há dependências de instalação via `npm` ou `pip`.

### 1. Clone o repositório

```bash
git clone https://github.com/GuilhermeGPF0601/site-apresentacao-halloween.git
cd site-apresentacao-halloween
```

### 2. Abra a página localmente

Você pode abrir diretamente o arquivo `index.html` no navegador ou iniciar um servidor local:

```bash
python -m http.server 8000
```

Em seguida, acesse:

```text
http://localhost:8000
```

> Como se trata de um projeto estático, não é necessário instalar pacotes nem executar build tools.

## Demonstração Visual

Abaixo estão algumas imagens da interface do projeto para visualizar o resultado final:

![Página inicial do site](img/1.jpg)

![Seção de destaque do tema](img/2.jpg)

![Receitas e apresentação visual](img/3.jpg)

Essas imagens representam a aparência principal da página, incluindo o banner, os cards temáticos e a identidade visual da campanha de Halloween.

## Licença

Este projeto está licenciado sob a licença MIT. Consulte o arquivo [LICENSE](LICENSE) para mais detalhes.

## Por que não foi necessário um arquivo `.gitignore`?

Neste caso, não foi necessário criar um `.gitignore` porque o projeto é uma aplicação estática simples, sem:

- `node_modules`
- ambiente virtual (`.venv`)
- arquivos de build gerados automaticamente
- dependências instaladas localmente
- credenciais ou segredos sensíveis

Todos os recursos necessários já estão incluídos no próprio repositório (`css/`, `js/`, `fontawesome/` e `img/`), então não existe uma pasta temporária ou artefato de compilação para ser ignorada.

Mesmo assim, como boa prática, em projetos maiores ou em versões que passem a usar Node, React, Vite, TypeScript ou outras ferramentas, o uso de um `.gitignore` passa a ser recomendado para evitar o envio de arquivos como:

- `node_modules/`
- `dist/`
- `.env`
- `.DS_Store`
- logs temporários

Em resumo: para este projeto estático e simples, a ausência de um `.gitignore` não trouxe problema prático, mas ele continua sendo uma boa prática em projetos com dependências e arquivos de ambiente.
