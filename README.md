## Desarrollo con SASS

este proyecto se enfoca en crear un entorno basico para desarrollar con sass

utiliza el comando para descargar todas las dependencias

```
npm install
```

## scripts de desarrollo

durante el desarrollo del sitio lo conveniente es utilizar el comando

```
npm start
```

para que inicie simultaneamente el compilador de SASS y el servidor web automaticamente de esta forma el compilador estara al pendiente de todos los cambios que se hacen en el archivo main.scss y por ende lo transformara a css nativo en el archivo style.css

## scripts de produccion

```
npm run build
```

una vez terminadas todas las modificaciones a los archivos SASS es momento de dar prefijos a todas las propiedades de css que lo requieran segun el navegador que se utilice y comprimir el tamaño del archivo css que se genere esto con el fin de obtener una hoja de estilos estandarizada
