## Ficha do Colaborador

Uma aplicação web interativa para gerenciar informações de colaboradores, desenvolvida com **HTML**, **CSS** e **JavaScript**. Permite adicionar, editar e salvar dados de colaboradores localmente, utilizando o `localStorage` do navegador. Ideal para empresas que desejam organizar as informações de seus colaboradores de forma simples e eficiente.

## Funcionalidades

- **Adicionar colaboradores**: Insira informações como nome, telefone, e-mail, matrícula, CPF e descrição do trabalho.
- **Chamado Aberto**: Marque se um chamado está aberto para o colaborador com um simples clique.
- **Modo Noturno**: Altere entre o modo claro e o modo escuro para melhor visualização.
- **Navegação entre colaboradores**: Navegue entre diferentes colaboradores na lista com botões de navegação.
- **Salvamento automático**: Os dados dos colaboradores são salvos no `localStorage`, permanecendo disponíveis mesmo após fechar o navegador.
- **Limpar tabela**: Remova todos os dados da tabela com confirmação do usuário.
- **Salvar em arquivo**: Exporte os dados dos colaboradores para um arquivo `.txt`.

## Como Usar

1. **Adicionar um colaborador**:
   - Preencha os campos de entrada com as informações do colaborador.
   - O colaborador será adicionado à lista automaticamente.

2. **Marcar chamado aberto**:
   - Clique no botão ao lado de "Chamado Aberto?" para alternar entre "Sim" e "Não".

3. **Navegar entre colaboradores**:
   - Use os botões **"Lista Anterior"** e **"Próxima Lista"** para navegar entre os colaboradores.

4. **Limpar tabela**:
   - Clique no botão **"Limpar Tabela"** para remover todos os dados. Uma confirmação será solicitada.

5. **Salvar em arquivo**:
   - Clique no botão **"Salvar em .txt"** para baixar um arquivo com as informações dos colaboradores.

## Tecnologias Utilizadas

- **HTML**: Estrutura da página.
- **CSS**: Estilização e design responsivo.
- **JavaScript**: Lógica de interação e manipulação do `localStorage`.

## Como Executar o Projeto

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/ficha-do-colaborador.git
   cd ficha-do-colaborador