# Comandos Importantes do Prisma

[Voltar para o README](../README.md)

## Índices

- [Migração do Banco de Dados](#migração-do-banco-de-dados)
- [Prisma Studio](#prisma-studio)
- [Seed do Banco de Dados](#seed-do-banco-de-dados)
- [Sincronização do Banco de Dados](#sincronização-do-banco-de-dados)

## Migração do Banco de Dados

Para realizar a migração no ambiente de desenvolvimento, use:

```sh
pnpm migration:dev
```

## Prisma Studio

Para abrir o Prisma Studio, use:

```sh
pnpm studio
```

## Seed do Banco de Dados

Para popular o banco de dados com dados iniciais, use:

```sh
pnpm seed
```

## Sincronização do Banco de Dados

Para sincronizar o banco de dados com o esquema Prisma, use:

```sh
pnpm push
```

Para puxar as alterações do banco de dados para o esquema Prisma, use:

```sh
pnpm pull
```
