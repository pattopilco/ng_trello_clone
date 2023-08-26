# Trello Clone

Es un proyecto basado en los cursos Platzi.

1. Maquetación con Angular CDK y Tailwind CSS


# 1. Maquetación con Angular CDK y Tailwind CSS

https://platzi.com/cursos/angular-tailwind/

## ANGULAR CDK
CDK no tiene un de diseño definido, está conformado de componentes para ser personalizados con estilos.

## Requerimientos
```
node -v
npm -v
npm install -g @angular/cli
ng version
```
## Tailwincss
Tailwincss es un moderno framework de CSS, especialmente por los utility-first.

https://tailwindcss.com

## Crear proyecto Angular
```
ng new my-project --routing --style=scss
cd my-project
```
## Instalar Tailwind CSS with Angular
https://tailwindcss.com/docs/guides/angular

```
npm install -D tailwindcss postcss autoprefixer
npx tailwindcss init
```

## Configurar
### Archivo **tailwind.css.js**
El arhicho tailwind es creado despues de ejecutar el comando (npx tailwindcss init)

```
module.exports = {
  content: [
    "./src/**/*.{html,ts}",
  ],
  theme: {
    extend: {},
  },
  plugins: [
    require('@tailwindcss/forms'),
  ],
}
```
### Archivo **styles.scss**
Añadir las siguientes configuraciones iniciales:

```
@tailwind base;
@tailwind components;
@tailwind utilities;
```

 ## Instalaciones

1. Extensión de tailwindcss en visual studio code **Tailwind Css IntelliSens**
 
2. Instalar angular CDK
```
 ng add @angular/cdk
```
 
 # 1.1 MAQUETANDO EL LOGIN PAGE 

 Crear componente sin estilos y sin test

 ```
 ng g c page/login --style=none --skype-tests
 ```

 1. Recursos Atlassian

 https://atlassian.design/resources/logo-library/
 
