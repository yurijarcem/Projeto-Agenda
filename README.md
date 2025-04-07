# Projeto-Agenda - Gerenciamento de Compromissos

**Projeto-Agenda** é uma aplicação simples para gerenciar compromissos e eventos. A ideia é permitir que os usuários adicionem, editem e visualizem compromissos de forma fácil e intuitiva. Este projeto utiliza **PHP** no backend e **MySQL** para armazenar os dados.

## Funcionalidades
- **Adicionar compromissos:** Permite ao usuário adicionar novos compromissos com título, descrição e data.
- **Listar compromissos:** Exibe todos os compromissos registrados em uma lista organizada.
- **Editar compromissos:** Possibilita a modificação de compromissos existentes, caso o usuário precise alterar detalhes como data ou descrição.

## Tecnologias Utilizadas
- **PHP**: Para implementar a lógica do backend.
- **MySQL**: Para o armazenamento de dados, como compromissos e eventos.
- **HTML5 e CSS3**: Para a estrutura e design da interface do usuário.
- **JavaScript**: Para validações no frontend e interação dinâmica com a interface.

## Como Executar

### Pré-requisitos
- PHP 7 ou superior.
- MySQL ou MariaDB.

### Passos
1. **Clone o repositório**:
   ```bash
   git clone https://github.com/yurijarcem/Projeto-Agenda.git

2. **Configuração do Banco de Dados**:

 - Importe o banco de dados do arquivo agenda.sql para o MySQL:
   ```bash
   CREATE DATABASE agenda;
   USE agenda;
   SOURCE agenda.sql;

3. **Configuração do Backend**:

 - Altere as credenciais de banco de dados no arquivo config.php (localizado na raiz do projeto) para corresponder ao seu ambiente.

4. **Rodando o servidor**:

- Inicie o servidor PHP:
   ```bash
   php -S localhost:8000

5. **Acesse o aplicativo no navegador em http://localhost:8000.**
