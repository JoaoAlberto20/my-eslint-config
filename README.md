# ESLint Config 

## Oque está incluso?

- Airbnb config base;
- React plugin;
- React Hooks plugin;
- JSX a11y plugin;
- Prettier;

## Instalação

Basta instalar através do npm (ou gerenciador favorito):

```shell
npm i -D @joaoalbertosv/eslint-config 
```

## Uso

Basta adicionar no seu `.eslintrc.json`:

```javascript
{
  "extends": "@joaoalbertosv/eslint-config/react"
  // "extends": "@joaoalbertosv/eslint-config/node"
}
```
> Você também pode usar um .eslintrc.js em vez de JSON, se preferir.

## Possíveis problemas

Eventualmente pode ser necessário que você instale manualmente as `peerDependencies`.
Se esse for o caso, basta rodar o comando:

```shell
npx install-peerdeps --dev @joaoalbertosv/eslint-config
```

Isso deverá resolver o problema. Qualquer coisa, abra uma issue que ficaremos felizes em resolver :
