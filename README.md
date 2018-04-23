# Instrucciones

### Instalar

1.  Instala [Hugo](https://gohugo.io/getting-started/quick-start/)

2.  en la carpeta raíz ejecuta `hugo -D` para construir el site

3.  Ya está

### Desarrollar

1.  en la raíz has `hugo server -D` y ve a [localhost:1313](http:localhost:1313)
2.  navega a la carpeta `themes/ghostwriter` y ejecuta `npm install && npm run watch`

**TEN EN CUENTA QUE LOS ARCHIVOS GENERADOS JAMÁS SE VERÁN BIEN EN LOCAL PORQUE BUSCA LOS ASSETS EN LA DIRECCIÓN WEB CONFIGURADA**

### Escribir

1.  `hugo new post/<nombre-del-url>.md`
2.  Entra a la carpeta `content/post` busca el archivo que has generado, y trabaja ahí
