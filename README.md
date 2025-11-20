# Atlantis - MVP

## Implementação do padrão Protótipo

Para permitir que os dependentes tenham os mesmos dados de endereço e telefone do cliente, aplicamos o padrão de projeto **Protótipo**:

- A classe `Endereco` já implementava o método `clonar()`.
- A classe `Telefone` também foi adaptada para implementar `clonar()`, garantindo que cada dependente tenha sua própria cópia dos telefones do cliente.

## Como rodar o projeto

1. Instale as dependências:

```bash
npm install
````

2. Entre na pasta de teste:

```bash
cd teste
```

3. Execute o arquivo principal:

```bash
npx ts-node index.ts
```
