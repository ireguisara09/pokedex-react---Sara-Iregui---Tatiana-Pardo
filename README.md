# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some Oxlint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Oxc](https://oxc.rs)
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/)

## React Compiler

The React Compiler is not enabled on this template because of its impact on dev & build performances. To add it, see [this documentation](https://react.dev/learn/react-compiler/installation).

## Expanding the Oxlint configuration

If you are developing a production application, we recommend using TypeScript with type-aware lint rules enabled. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) for information on how to integrate TypeScript and Oxlint's TypeScript related rules in your project.

Pokédex React
Objetivo del proyecto

Crear una aplicación en React que consulte Pokémon mediante PokéAPI y permita administrar un equipo Pokémon usando un CRUD con JSON Server.

Tecnologías utilizadas
React
Vite
JavaScript
PokéAPI
JSON Server
Git y GitHub
PokéAPI

PokéAPI es una API externa utilizada para consultar información de Pokémon mediante solicitudes GET.

En este proyecto permite buscar Pokémon por nombre o número, por ejemplo: pikachu, charizard o 25.

JSON Server

JSON Server se utiliza para crear una API local donde se guarda nuestro equipo Pokémon.

Los datos se almacenan en el archivo db.json.

Métodos CRUD utilizados
GET: consultar y mostrar los Pokémon del equipo.
POST: agregar un Pokémon al equipo.
PATCH: modificar el nivel o el estado de favorito.
DELETE: eliminar o liberar un Pokémon del equipo.
Instalación y ejecución

Instalar las dependencias:

npm install


Ejecutar React:

npm run dev


Ejecutar JSON Server en otra terminal:

npm run api


React funciona normalmente en localhost:5173 y JSON Server en localhost:3001.

