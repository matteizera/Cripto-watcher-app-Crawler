# Cripto Watcher APP - Crawler
## Projeto que fica lendo as informações do preço do bitcoin utilizando a [api](https://api.coingecko.com/api/v3/simple/price?ids=bitcoin&vs_currencies=usd) da coingecko gera as informações para serem utilizadas pela api e faz a comunicação com a api via RabbitMQ.

### Projeto seguindo o curso do Sidney Souza que pode ser encontrado [aqui](https://www.youtube.com/playlist?list=PL370TvW48yBupAwG99DiAjLSLDwCoPb07)
### Repositorio do app pode ser encontrado [aqui](https://github.com/matteizera/Cripto-watcher-app-vue)
### Repositorio da api pode ser encontrado [aqui](https://github.com/matteizera/Cripto-watcher-app-api)

### Trilha & Melhorias

- [x] Crawler do preco do bitcoin
- [x] Geração dos dados para candle
- [x] Dados do Bitcoin
- [x] Envio das informações via RabbitMQ
- [ ] Adicionar mais opções de criptomoedas
- [ ] Adaptar o RabbitMQ para mais opcões de criptomoedas

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run start
```

### Compiles and minifies for production
```
npm run build
```
