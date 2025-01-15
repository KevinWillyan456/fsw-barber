# FSW Barber

Este sistema é um sistema de agendamentos para barbearias. Ele permite que os clientes agendem horários com seus barbeiros preferidos de forma fácil e rápida, garantindo um atendimento organizado e eficiente.

## Como iniciar

Para iniciar o projeto, siga os passos abaixo em ordem sequencial para não ter problemas:

1. Clone o repositório para sua máquina local:

    ```sh
    git clone https://github.com/KevinWillyan456/fsw-barber.git
    ```

2. Navegue até o diretório do projeto:

    ```sh
    cd fsw-barber
    ```

3. Certifique-se de ter o PNPM instalado. Se não tiver, instale-o globalmente usando o comando:

    ```sh
    npm install -g pnpm
    ```

4. Instale as dependências do projeto:

    ```sh
    pnpm install
    ```

5. Execute as migrações do banco de dados:

    ```sh
    pnpm db
    ```

6. Popule o banco de dados com dados iniciais:

    ```sh
    pnpm seed
    ```

7. Inicie o servidor de desenvolvimento:

    ```sh
    pnpm dev
    ```

Agora acesse `http://localhost:3000` no seu navegador para ver a aplicação rodando.

## Documentação

A documentação do projeto é dividida em várias partes, cada uma com um propósito específico. Confira abaixo a lista de documentos disponíveis:

- [Comandos Importantes do Prisma](docs/DATABASE.md): Documentação do banco de dados do projeto.
