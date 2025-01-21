# Expenses App

Expenses App é uma aplicação desenvolvida em Flutter para gerenciamento de despesas pessoais. A interface permite registrar transações com valores e títulos personalizados, proporcionando uma visão organizada e prática das finanças pessoais.

## Funcionalidades

- **Registro de Transações:** Permite adicionar novas transações com título, valor e data.
- **Visualização em Lista:** Exibe todas as transações registradas em um formato de lista organizado.
- **Modal Interativo:** Inclusão de transações através de um modal acessível.

## Estrutura do Projeto

O projeto está dividido nos seguintes componentes principais:

1. **Modelos:**
   - `Transaction`: Representa uma transação com atributos de ID, título, valor e data.

2. **Componentes:**
   - `TransactionForm`: Formulário para adicionar novas transações.
   - `TransactionList`: Lista de transações renderizadas dinamicamente.
   - `TransactionUser`: Componente que gerencia o estado das transações.

3. **Principal:**
   - `main.dart`: Configura o aplicativo, inicializando a estrutura e o layout principal.

## Tecnologias Utilizadas

- **Linguagem:** Dart
- **Framework:** Flutter
- **Bibliotecas Adicionais:**
  - `intl` para formatação de datas

## Como Executar o Projeto

1. Certifique-se de ter o Flutter instalado em sua máquina.
2. Clone este repositório.
3. No terminal, acesse o diretório do projeto e execute:
   ```bash
   flutter pub get
   flutter run
   ```

## Layout e Experiência do Usuário

O design foca na simplicidade e funcionalidade. A aplicação utiliza `Material Design`, com ênfase em elementos visuais como botões interativos e cores consistentes para diferenciação de valores e informações.

## Futuras Implementações

- Adicionar gráficos para visualização das despesas.
- Implementar persistência de dados local.
- Suporte para múltiplos idiomas.

## Contribuições

Contribuições são bem-vindas! Para contribuir:
1. Faça um fork do repositório.
2. Crie uma branch com a sua feature ou correção.
3. Envie um pull request.

## Licença

Este projeto está licenciado sob a licença MIT. Consulte o arquivo LICENSE para mais informações.
