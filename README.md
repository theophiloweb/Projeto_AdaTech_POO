# Sistema de Gestão Bancária

## 🏦 Projeto Painel Administrativo Bancário

Este projeto foi desenvolvido como trabalho final do módulo de Programação Orientada a Objetos em Python do curso de Engenharia de Dados da AdaTech.

### 👥 Autores
- Amanda de Sousa Almeida
- Francisco das Chagas Teófilo da Silva

## 📋 Descrição do Projeto

Este projeto implementa um sistema CRUD (Criar, Ler, Atualizar, Excluir) para um painel administrativo bancário. Ele permite aos usuários gerenciar informações de clientes e contas através de uma interface de linha de comando.

### 🔑 Funcionalidades Principais

- Criar novos perfis de clientes
- Ler informações de clientes
- Atualizar detalhes existentes de clientes
- Excluir registros de clientes
- Criar contas bancárias para clientes
- Exibir informações individuais de clientes
- Listar todos os clientes

## 🛠 Tecnologias Utilizadas

- Python
- Programação Orientada a Objetos (POO)
- Manipulação de arquivos CSV para persistência de dados

## 🚀 Como Executar

1. Certifique-se de ter o Python instalado em seu sistema.
2. Clone este repositório para sua máquina local.
3. Navegue até o diretório do projeto no seu terminal.
4. Execute o script principal:
   ```
   python main.py
   ```
5. Siga as instruções na tela para interagir com o sistema.

## 📊 Estrutura de Dados

O sistema usa um arquivo CSV (`tab_clientes.csv`) para armazenar informações dos clientes. Cada registro de cliente inclui:

- CPF
- Nome
- Data de Nascimento
- Idade
- Endereço
- Número de Telefone
- Nível de Escolaridade
- Estado Civil
- Email
- Número da Conta (se aplicável)
- Tipo de Conta (se aplicável)
- Saldo (se aplicável)
- Data de Cadastro

## 🔒 Validação de Dados

O sistema inclui validação básica de entrada para:
- Formato do CPF
- Formato do nome (não são permitidos números)
- Formato da data de nascimento
- Formato do email
- Estado civil
- Formato do número de telefone
- Seleção do nível de escolaridade

## 🎯 Melhorias Futuras

- Implementar validação de dados mais robusta
- Adicionar funcionalidade de transações para contas bancárias
- Desenvolver uma interface gráfica de usuário (GUI)
- Implementar criptografia de dados para informações sensíveis

---

📅 Data de Conclusão do Projeto: 9 de setembro de 2024

🎓 Este projeto é parte do currículo do curso de Engenharia de Dados da AdaTech.
