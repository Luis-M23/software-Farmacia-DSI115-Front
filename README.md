# vue

This template should help get you started developing with Vue 3 in Vite.

## Recommended IDE Setup

[VS Code](https://code.visualstudio.com/) + [Volar](https://marketplace.visualstudio.com/items?itemName=johnsoncodehk.volar) (and disable Vetur).

## Type Support for `.vue` Imports in TS

Since TypeScript cannot handle type information for `.vue` imports, they are shimmed to be a generic Vue component type by default. In most cases this is fine if you don't really care about component prop types outside of templates.

However, if you wish to get actual prop types in `.vue` imports (for example to get props validation when using manual `h(...)` calls), you can run `Volar: Switch TS Plugin on/off` from VS Code command palette.

## Customize configuration

See [Vite Configuration Reference](https://vitejs.dev/config/).

## Instala las librerias en la ruta de proyecto

```sh
pnpm install
```

### Compilar y recargar en caliente para el desarrollo

```sh
pnpm run dev
```

### Crear un .env dentro de la ruta del proyecto y agregale 

```sh
VITE_API_BASE_URL=http://localhost:8000/api
```

### Compilar y recargar en caliente para producción

```sh
pnpm run build
```
