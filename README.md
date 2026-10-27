# College Web Cabrobó

Projeto acadêmico de desenvolvimento web dedicado à apresentação do município de Cabrobó, em Pernambuco, com informações sobre a cidade, eventos culturais e formulários de cadastro.

A aplicação foi desenvolvida para praticar conceitos fundamentais de frontend, construção de interfaces responsivas e introdução ao processamento de formulários com PHP.

## Sobre o projeto

O site apresenta conteúdos informativos sobre Cabrobó, incluindo aspectos históricos, culturais e eventos locais.

A proposta combina navegação entre páginas, apresentação de imagens, estilização personalizada e formulários HTML em uma aplicação web de estudo.

## Funcionalidades

- Página inicial com apresentação do município;
- Informações culturais e históricas;
- Página dedicada aos eventos locais;
- Formulário para cadastro de eventos;
- Formulário de registro de organizadores;
- Navegação entre páginas;
- Interface desenvolvida com Bootstrap e CSS personalizado;
- Exemplo básico de recebimento de dados via PHP.

**Observação:** os formulários são demonstrativos. Na implementação atual, o PHP apenas exibe os dados recebidos via POST, sem persistência em banco de dados ou sistema de autenticação.

## Tecnologias

- HTML5
- CSS3
- Bootstrap 5
- PHP básico

## Estrutura do projeto

```text
college-web-cabrobo/
├── css/
│   └── estilo.css
├── img/
├── index.html
├── eventos.html
├── cadastro.html
├── sessao.html
└── index.php
```

## Como executar

Para visualizar as páginas estáticas, abra `index.html` em um navegador.

Para testar o processamento dos formulários, utilize um servidor local com suporte a PHP, como o XAMPP, ou o servidor de desenvolvimento do PHP.

Com o PHP instalado, na raiz do projeto:

```bash
php -S localhost:8000
```

Acesse:

`http://localhost:8000/index.html`

**Importante:** utilize apenas dados fictícios nos formulários. O script PHP atual exibe os valores enviados, incluindo campos de senha, e não foi preparado para uso com informações reais.

## Conceitos trabalhados

- Estruturação de páginas HTML;
- Estilização com CSS;
- Layout e responsividade com Bootstrap;
- Navegação entre páginas;
- Formulários HTML;
- Métodos de requisição HTTP;
- Recebimento de dados com PHP;
- Organização de arquivos e recursos estáticos.

## Objetivo

Aplicar conhecimentos introdutórios de desenvolvimento web em um projeto acadêmico, explorando a criação de interfaces, a apresentação de informações e a comunicação básica entre formulários HTML e scripts PHP.

O repositório representa uma etapa de aprendizado e não corresponde a um portal oficial do município.

## Autores

Kadu Almeida e Fernando Almeida.

---

*Projeto acadêmico desenvolvido para fins educacionais.*
