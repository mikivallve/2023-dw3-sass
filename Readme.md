## Instrucciones

### 1- inicializar npm con `npm init`
### 2- instalar dart-sass a nivel global `npm i -g sass`
### 3- escribir un script para "observar" el archivo controlador.scss y compilar los cambios en estilos.css 

La sintaxis básica es ```sass --watch origen:destino```  dónde origen es un archivo SCSS y destino es un archivo CSS
Se recomienda revisar la documentación oficial [https://sass-lang.com/documentation/cli/dart-sass]

### 4- modificar el script para que el `css` generado sea minificado
### 5- modificar el script para el `css` generado se llame `estilos.min.css`
### 6- modificar `index.html` para tomar este nuevo `css`
### 7- agregar todos los archivos `scss` a una carpeta llamada `scss`
### 8- modificar el script para que al cambiar cualquier archivo dentro de la carpeta `scss` se genere un `estilos.min.css`
### 9- enviar un zip al docente por slack

## Comandos de sass

`-w, --watch` 
Watch a directory or file\
`-r, --recursive`
Recursively watch directories or files\
`-o, --output`
Output directory\
`-x, --omit-source-map-url`
Omit source map URL comment from output\
`-i, --indented-syntax`
Treat data from stdin as sass code (versus scss)\
`-q, --quiet`
Suppress log output except on error\
`-v, --version`
Prints version info\
`--output-style`
 CSS output style (nested | expanded | compact | compressed)\
`--indent-type`
Indent type for output CSS (space | tab)\
`--indent-width`
 Indent width; number of spaces or tabs (maximum value: 10)\
`--linefeed`
Linefeed style (cr | crlf | lf | lfcr)\
`--source-comments`
Include debug info in output\
`--source-map`
 Emit source map\
`--source-map-contents`
Embed include contents in map\
`--source-map-embed Embed sourceMappingUrl as data URI\
`--source-map-root Base path, will be emitted in source-map as is\
`--include-path`
 Path to look for imported files\
`--follow`
Follow symlinked directories\
`--precision`
The amount of precision allowed in decimal numbers\
`--error-bell`
 Output a bell character on errors\
`--importer`
 Path to .js file containing custom importer\
`--functions`
Path to .js file containing custom functions\
`--help`
 Print usage info\
