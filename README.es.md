<p align="center">
  <img width="320" src="https://wpimg.wallstcn.com/ecc53a42-d79b-42e2-8852-5126b810a4c8.svg">
</p>

Español | [English](./README.md) | [한국어](./README.kr.md) | [日本語](./README.ja.md)

## Introducción

[vue-element-admin](https://panjiachen.github.io/vue-element-admin) es una interfáz de administración preparada para producción. Está basada en [vue](https://github.com/vuejs/vue) y usa [element-ui](https://github.com/ElemeFE/element) como conjunto de herramientas de interfáz de usuario.

Vue Element Admin es una solución práctica basada en la nueva plataforma de desarrollo de vue, construida con soporte a i18 para el manejo de múltiples lenguajes, plantillas estándares para aplicaciones de negocio y un conjunto de asombrosas características. Esta herramienta ayuda a construir largas y complejas Aplicacones de una sola página (SPA). Creo que lo que necesites hacer, este proyecto te ayudará.

- [Vista Prévia de la Aplicación](https://panjiachen.github.io/vue-element-admin)

- [Documentación](https://panjiachen.github.io/vue-element-admin-site/)

- [Canal de Gitter](https://gitter.im/vue-element-admin/discuss)

- [Enlace de Wiki](https://github.com/PanJiaChen/vue-element-admin/wiki)

- [Canal de Gitee](https://panjiachen.gitee.io/vue-element-admin/)

- Plantilla base recomendada para usar: [vue-admin-template](https://github.com/PanJiaChen/vue-admin-template)
- Aplicación de Escritorio: [electron-vue-admin](https://github.com/PanJiaChen/electron-vue-admin)
- Plantilla de Typescript: [vue-typescript-admin-template](https://github.com/Armour/vue-typescript-admin-template) (Créditos: [@Armour](https://github.com/Armour))
- [awesome-project](https://github.com/PanJiaChen/vue-element-admin/issues/2312)

**Después de la versión `v4.1.0+`, la rama por defecto master no tendrá soporte para i18n. Por favor utilice la rama [i18n](https://github.com/PanJiaChen/vue-element-admin/tree/i18n), los cambios serán incluidos en la rama master**

**la versión actual es `v4.0+` construida con `vue-cli`. Si encuentra algún problema, por favor coloque un [issue](https://github.com/PanJiaChen/vue-element-admin/issues/new). Si desea usar la versión anterior, puede cambiar de rama a [tag/3.11.0](https://github.com/PanJiaChen/vue-element-admin/tree/tag/3.11.0), no relacionado con `vue-cli`**

**Este proyecto no está soportado para versiones antigüas de navegadores (ej. IE).**

## Preparación

Necesita instalar [node](https://nodejs.org/) y [git](https://git-scm.com/) localmente. El proyecto es basado en [ES2015+](https://es6.ruanyifeng.com/), [vue](https://cn.vuejs.org/index.html), [vuex](https://vuex.vuejs.org/zh-cn/), [vue-router](https://router.vuejs.org/zh-cn/), [vue-cli](https://github.com/vuejs/vue-cli) , [axios](https://github.com/axios/axios) and [element-ui](https://github.com/ElemeFE/element), toda la solicitud de datos simulada se realiza a través de [Mock.js](https://github.com/nuysoft/Mock).
Entendiendo y aprendiendo esto pudiera ayudarle con su proyecto.

[![Edit on CodeSandbox](https://codesandbox.io/static/img/play-codesandbox.svg)](https://codesandbox.io/s/github/PanJiaChen/vue-element-admin/tree/CodeSandbox)

<p align="center">
  <img width="900" src="https://wpimg.wallstcn.com/a5894c1b-f6af-456e-82df-1151da0839bf.png">
</p>

## Características

```
- Iniciar / Cerrar Sesión

- Permisos de Autenticación
  - Página de Permisos
  - Directivas de permisos
  - Página de configuración de permisos
  - Autenticación por dos pasos

- Construcción Multi-entorno
  - Desarrollo (dev)
  - sit
  - Escenario de pruebas (stage),
  - Producción (prod)

- Características Globales
  - I18n
  - Temas dinámicos
  - Menu lateral dinámico (soporte a rutas multi-nivel)
  - Barra de rutas dinámica
  - Tags-view (Pestañas de página, Soporta operación de clic derecho)
  - Svg Sprite
  - Datos de simulación con Mock
  - Pantalla completa
  - Menu lateral responsivo

- Editor
  - Editor de Texto Enriquecido
  - Editor Markdown
  - Editor JSON

- Excel
  - Exportación a Excel
  - Carga de Excel
  - Visualización de Excel
  - Exportación como ZIP

- Tabla
  - Tabla Dinámica
  - Tabla con Arrastrar y Soltar
  - Tabla de edición en línea

- Páginas de Error
  - 401
  - 404

- Componentes
  - Carga de Avatar
  - Botón para subir al inicio
  - Arrastrar y Soltar (Diaglogo)
  - Arrastrar y Soltar (Seleccionar)
  - Arrastrar y Soltar (Kanban)
  - Arrastrar y Soltar (Lista)
  - Panel de división
  - Componente para soltar archivos
  - Adhesión de objetos
  - Contador hasta

- Ejemplo Avanzado
- Registro de Errores
- Tablero de indicadores
- Página de Guías
- ECharts (Gráficos)
- Portapapeles
- Convertidor de Markdown a HTML
```

## Iniciando

```bash
# clone el proyecto
git clone https://github.com/PanJiaChen/vue-element-admin.git

# vaya al directorio clonado
cd vue-element-admin

# instale las dependencias
npm install

# corra el proyecto como desarrollador
npm run dev
```

Automáticamente se abrirá el siguiente enlace en su navegador http://localhost:9527

## Construcción

```bash
# Construcción para entornos de prueba
npm run build:stage

# Construcción para entornos de producción
npm run build:prod
```

## Avanzado

```bash
# Vista previa con efectos de entorno
npm run preview

# Vista previa  con efectos + análisis de recursos estáticos
npm run preview -- --report

# Chequeo de formato de código
npm run lint

# Chequeo de formato de código y auto-corrección
npm run lint -- --fix
```

## Registro de Cambios

Los cambios detallados por cada liberación se encuentran en [notas de liberación](https://github.com/PanJiaChen/vue-element-admin/releases).

## Navegadores Soportados

Navegadores modernos e Internet Explorer 10+.

| [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/edge/edge_48x48.png" alt="IE / Edge" width="24px" height="24px" />](https://godban.github.io/browsers-support-badges/)</br>IE / Edge | [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/firefox/firefox_48x48.png" alt="Firefox" width="24px" height="24px" />](https://godban.github.io/browsers-support-badges/)</br>Firefox | [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/chrome/chrome_48x48.png" alt="Chrome" width="24px" height="24px" />](https://godban.github.io/browsers-support-badges/)</br>Chrome | [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/safari/safari_48x48.png" alt="Safari" width="24px" height="24px" />](https://godban.github.io/browsers-support-badges/)</br>Safari |
| --------- | --------- | --------- | --------- |
| IE10, IE11, Edge | últimas 2 versiones | últimas 2 versiones | últimas 2 versiones |

## Licencia

[MIT](https://github.com/PanJiaChen/vue-element-admin/blob/master/LICENSE)

Copyright (c) 2017-presente PanJiaChen
