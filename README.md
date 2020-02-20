### uni-vendas-docker-compose

### Estrutura dos microserviços do uni-vendas

```shell
uni-vendas
   |_ msv-pedidos
   |_ msv-....
```

### Descrição

Projeto de treinamento, de docker que visa criar containers através do docker compose, e dividido entre duas partes

- Geração das imagens dos containeir de microserviços do projeto baseados em spring boot.
- É este projeto que visa instalar todos os as imagens, via docker compose, para ambiente de testes.

### Imagens / projetos

- [msv-pedidos](https://github.com/Uniliva/msv-pedidos)

Com o tempo será adicionados mais projetos

### Gera ambiente de teste

- Necessário ter apenas o docker e o docker-compose instaladao na maquina.

Para gera o ambiente de teste rapidamente:

- Baixe o projeto e acesse a pasta
- Execute

```shell
docker-compose up -d
```




