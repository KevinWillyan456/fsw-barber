# Comandos Importantes do Prisma

## Índice

1. [Erro de Conexão com o Banco de Dados](#erro-de-conexão-com-o-banco-de-dados)
2. [Instalação](#instalação)
3. [Inicialização](#inicialização)
4. [Migração do Banco de Dados](#migração-do-banco-de-dados)
5. [Prisma Studio](#prisma-studio)
6. [Seed do Banco de Dados](#seed-do-banco-de-dados)
7. [Sincronização do Banco de Dados](#sincronização-do-banco-de-dados)

## Erro de Conexão com o Banco de Dados

Se você encontrar um erro de conexão com o banco de dados, verifique se as credenciais no arquivo `.env` estão corretas e se o banco de dados está em execução.

## Instalação

```sh
npm install -g pnpm
pnpm add prisma @prisma.client
```

## Inicialização

```sh
pnpm prisma init
```

## Migração do Banco de Dados

```sh
pnpm prisma migrate dev --name init
```

## Prisma Studio

Para abrir o Prisma Studio, use o seguinte comando:

```sh
pnpm prisma studio
```

## Seed do Banco de Dados

Para popular o banco de dados com dados iniciais, use o seguinte comando:

```sh
pnpm prisma db seed
```

## Sincronização do Banco de Dados

Para sincronizar seu banco de dados com o esquema Prisma, use o seguinte comando:

```sh
pnpm prisma db push
```
