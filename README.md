# Drytech
📚 Sistema de Curadoria

Projeto acadêmico desenvolvido com foco em organização de dados, curadoria de conteúdos, ética digital, IA responsável e segurança da informação, utilizando tecnologias modernas da plataforma Java.

🚀 Sobre o Projeto

O Sistema de Curadoria é uma aplicação construída em Java 24, utilizando Java Swing para a interface gráfica. O objetivo é facilitar a análise, visualização e gerenciamento de registros de forma simples, rápida e segura.

O projeto segue uma estrutura modular sem uso de MVC, priorizando clareza, organização e manutenção direta do código.

🎯 Objetivo do Sistema

Otimizar e agilizar processos de curadoria

Registrar e consultar informações de forma prática

Filtrar e analisar dados com facilidade

Seguir princípios de ética digital e IA responsável

Garantir segurança e integridade dos dados

🛠️ Tecnologias Utilizadas

Java 24

Java Swing

Flyway (versionamento do banco de dados)

DAO Pattern

Banco de Dados Local MySQL

🧩 Funcionalidades Implementadas

Cadastro de informações

Listagem e consulta de registros

Filtros e buscas

Interface gráfica intuitiva

Validações básicas

Migrations automáticas com Flyway

Estrutura modular e organizada

🗺️ Roadmap (Futuras Implementações)

Autenticação de usuário

Exportação de dados em CSV

Dashboard analítico

Tema escuro

Curadoria automática com IA

Logs e auditoria

Mecanismos de segurança avançados

📦 Pré-requisitos

Antes de rodar o projeto, certifique-se de ter:

Java 24 instalado

MySQL ou SQLite

Maven ou Gradle (dependendo do seu projeto)

Flyway configurado

🗄️ Configurando o Banco + Flyway

Crie o banco de dados (ex: curadoria_db)

Configure a conexão no projeto

Coloque suas migrations neste caminho:

/resources └── db └── migration ├── V1__create_tables.sql ├── V2__insert_initial_data.sql └── ...

Flyway aplicará tudo automaticamente na inicialização.

📂 Estrutura do Projeto /src ├── Main/ ├── java/ ├── dao/ ├── dto/ ├── model ├── view/ ├── resources/ ├── test/

▶️ Como Executar o Projeto

Clone o repositório git clone (https://github.com/GabrielAlvesdata/Java) )

Abra a IDE

IntelliJ, VS Code, Eclipse ou NetBeans.

Certifique-se de ter Java 24 java --version

Execute a classe principal Main.java

🔐 Segurança & Ética Digital

O sistema segue diretrizes como:

Tratamento responsável de dados

Minimização de informações sensíveis

Estrutura preparada para logs e auditoria

Boas práticas de ética digital

Alinhamento com princípios de IA responsável

📸 Imagens do Sistema

Tela Principal Exemplo de Uso

👥 Equipe do Projeto

Desenvolvido por:

Felipe Muniz Felix da Costa Rodrigo Pousada Vieira Joao Ricardo Leoncio da Silva Gabriel Francisco Alves Gomes Mariana Garcia Augusto Jose Maxsuel Nogueira Felipe Francisco Lemos Sales

“Este projeto só foi possível graças ao esforço, dedicação e parceria de toda a equipe envolvida.”

🐛 Issues / Bugs

Encontrou algum problema? Abra uma issue descrevendo:

O que aconteceu

Passo a passo para reproduzir

Print ou mensagem de erro (se houver)
