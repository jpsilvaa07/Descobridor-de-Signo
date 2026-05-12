Descobridor de Signo

Este e um projeto que eu fiz para faculdade que consiste em uma aplicação web simples desenvolvida em PHP, que permite ao usuário descobrir seu signo zodiacal a partir da data de nascimento.

📌 Funcionalidades
Formulário para inserção da data de nascimento
Processamento da data informada
Identificação automática do signo correspondente
Exibição de informações sobre o signo
Interface estilizada com Bootstrap e CSS personalizado

🛠️ Tecnologias Utilizadas
PHP → Lógica e processamento do formulário
HTML5 → Estrutura das páginas
CSS3 → Estilização personalizada
Bootstrap → Layout responsivo
XML → Armazenamento das informações dos signos

📁 Estrutura do Projeto
/projeto-signo
│
├── /css
│   └── style.css
│
├── /xml
│   └── signos.xml
│
├── header.php        # Topo das páginas (layout reutilizável)
├── index.php         # Página inicial com formulário
├── resultado.php     # Página de resultado do signo
│
└── README.md

🚀 Como Funciona
O usuário acessa a página inicial (index.php)
Insere sua data de nascimento no formulário
Ao clicar no botão, os dados são enviados para resultado.php
O sistema processa a data e identifica o signo
As informações do signo são carregadas a partir do arquivo XML (signos.xml)
O resultado é exibido na tela

📄 Estrutura do XML

O arquivo signos.xml contém os dados de cada signo, como:

Nome do signo
Período (datas)
Descrição
Características principais

Exemplo:

<signos>
  <signo>
    <nome>Áries</nome>
    <dataInicio>21-03</dataInicio>
    <dataFim>20-04</dataFim>
    <descricao>Determinado, impulsivo e cheio de energia.</descricao>
  </signo>
</signos>

🎨 Estilização
Utilização do Bootstrap para responsividade
Customizações adicionais com style.css
Layout simples, moderno e intuitivo

▶️ Como Executar
Instale um servidor local (ex: XAMPP, WAMP ou Laragon)
Coloque a pasta do projeto dentro do diretório do servidor (htdocs ou equivalente)
Inicie o servidor Apache
Acesse no navegador:
http://localhost/projeto-signo

📚 Objetivo do Projeto

Este projeto tem como objetivo:

Praticar conceitos de PHP com múltiplos arquivos
Trabalhar com formulários e envio de dados
Utilizar XML como fonte de dados
Aplicar Bootstrap + CSS na interface
Organizar um projeto web com boa estrutura
