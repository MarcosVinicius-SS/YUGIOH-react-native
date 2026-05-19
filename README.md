# Meu Baralho Yu-Gi-Oh

App mobile feito em React Native que puxa cartas aleatórias do Yu-Gi-Oh usando a API pública do YGOProDeck.

## O que o app faz

- Puxa uma carta aleatória a cada clique
- Mostra a imagem, nome, tipo, atributo, nível, ATK e DEF da carta

## Tecnologias

- React Native
- Expo
- YGOProDeck API (https://ygoprodeck.com/api-guide)
- AllOrigins (proxy para contornar CORS no ambiente web)

## Como rodar

1. Instala as dependências:
   npm install

2. Roda o projeto:
   npx expo start

3. Escaneia o QR code com o app Expo Go no celular, ou abre no emulador.

## Observacao

A imagem das cartas usa um proxy (allorigins.win) para funcionar no browser via Expo Web.
Se rodar direto no celular com Expo Go, pode remover o proxy e usar a URL da imagem diretamente.
