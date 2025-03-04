# GitFind

GitFind é uma aplicação web que permite aos usuários buscar informações sobre perfis do GitHub e visualizar seus repositórios. A aplicação foi desenvolvida utilizando React e faz uso da API do GitHub para obter os dados dos usuários e seus repositórios.

## Funcionalidades

- Buscar perfis de usuários do GitHub pelo nome de usuário.
- Exibir informações do perfil, como avatar, nome, login e biografia.
- Listar os repositórios públicos do usuário.

## Tecnologias Utilizadas

- **React**: Biblioteca JavaScript para construção de interfaces de usuário.
- **API do GitHub**: Utilizada para obter dados dos usuários e seus repositórios.
- **CSS**: Estilização da aplicação.

## Estrutura do Projeto

- `src/components/Header`: Componente de cabeçalho da aplicação.
- `src/components/ItemList`: Componente para exibir os repositórios do usuário.
- `src/pages/Home`: Página principal da aplicação onde ocorre a busca e exibição dos dados.
- `src/assets`: Diretório contendo os arquivos de mídia, como imagens.
- `public`: Diretório contendo o arquivo HTML principal.

## Como Executar o Projeto

1. Clone o repositório:
    ```sh
    git clone https://github.com/seu-usuario/gitfind.git
    ```

2. Navegue até o diretório do projeto:
    ```sh
    cd gitfind
    ```

3. Instale as dependências:
    ```sh
    npm install
    ```

4. Inicie a aplicação:
    ```sh
    npm start
    ```

5. Abra o navegador e acesse:
    ```
    http://localhost:3000
    ```

## Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues e pull requests.

## Licença

Este projeto está licenciado sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.