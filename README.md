# Ultrasom-app
<!--  --># Ultrassom – módulo de informações (React Native / Expo)

## Como rodar

O app já está configurado na pasta `ultrassom-app`. Com Node.js 22.13 ou
superior instalado, rode:

```bash
cd ultrassom-app
npm start
```

Escaneie o QR code com o app Expo Go. O celular e o computador devem estar na
mesma rede Wi-Fi.

Se o Node 22 ainda não estiver instalado, é possível usar temporariamente:
`npx --yes --package=node@22 --call 'cd ultrassom-app && npm start'`.

## Como editar o conteúdo

Todo o conteúdo do app fica em `ultrassom-app/src/data/content.ts`. Para criar
uma nova página, adicione um objeto em `topics` com `sections` contendo blocos
`text`, `list` ou `table`.
