<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="200" alt="Nest Logo" /></a>
</p>

[circleci-image]: https://img.shields.io/circleci/build/github/nestjs/nest/master?token=abc123def456
[circleci-url]: https://circleci.com/gh/nestjs/nest

<p align="center"></p>

## Descripción

Proyecto para pruebas con integración a GBP utilizando NestJS.

## Instalación

```bash
# Clonar el repositorio.
git clone https://github.com/MatiasValenzisi/integration-gbp

# Navegar al directorio del proyecto.
cd integration-gbp

# Copiar y renombrar el archivo .env.example por .env
Configurar puerto a utilizar y credenciales.

# Instalar dependencias
npm install
```

## Iniciar el servidor en desarrollo

```bash
# Development
$ npm run start:dev
```

## Estructura del proyecto

```sh
src/
├── app.module.ts          
├── gbp/
│   └── nucleo/
│       ├── dto/
│       │   └── brand-response.dto.ts
│       │   └── image-response.dto.ts
│       │   └── login-response.dto.ts
│       │   └── product-response.dto.ts
│       │   └── sku-response.dto.ts
│       ├── interfaces/
│       │   └── brand-response.interface.ts
│       │   └── images-response.interface.ts
│       │   └── product-storage-group-response.interface.ts
│       │   └── product-base-response.interface.ts
│       ├── services/
│       │   └── axios.service.ts
│       │   └── brand-response.service.ts
│       │   └── credential.service.ts
│       │   └── login-response.service.ts
│       │   └── nucleo.service.ts
│       │   └── product-response.service.ts
│       │   └── xml2js.service.ts
│       ├── nucleo.controller.ts
│       └── nucleo.module.ts
├── app.module.ts
├── logger.module.ts
└── main.ts
```

## Tecnologia

- NestJS 10
- TypeScript: ^5.1.3
- Node.js: >= 14.x

## Dependencias

- @nestjs/common: Utilidades comunes de NestJS. Versión ^10.0.0
- @nestjs/core: Núcleo de NestJS. Versión ^10.0.0
- @nestjs/platform-express: Plataforma Express para NestJS. Versión ^10.0.0
- axios: Cliente HTTP para hacer solicitudes. Versión ^1.7.2
- dotenv: Carga variables de entorno desde un archivo .env. Versión ^16.4.5
- reflect-metadata: Añade soporte de metadatos de decoración a TypeScript. Versión ^0.2.0
- rxjs: Librería para programación reactiva. Versión ^7.8.1
- uuid-validate: Valida si un dato es un uuid. Versión ^0.0.3
- xml2js: Convertidor de XML a JavaScript. Versión ^0.6.2
- nestjs-pino: Módulo de logging para aplicaciones NestJS que integra el logger pino. Versión ^4.1.0"

## Documentación

- Nomenclatura - https://gist.github.com/WanerValencia/64bed91c288153b4aef10b57e98785e3
- npmjs: Axios - https://www.npmjs.com/package/axios
- Doc: Axios - https://axios-http.com/es/docs/res_schema
- npmjs: xml2js - https://www.npmjs.com/package/xml2js



