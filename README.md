Plantilla base de Sass
Este es un proyecto de muestra que utiliza el patrón de arquitectura 7-1 y sigue las convenciones de escritura de Sass Guidelines.

Cada carpeta de este proyecto tiene su propio archivo README.md para explicar el propósito y agregar información adicional. Asegúrate de explorar el repositorio para ver cómo funciona.

Usando la sintaxis anidada
Conversión a Sass
Esta plantilla no proporciona una versión en .sass ya que sería difícil mantener ambas versiones sin un proceso de construcción adecuado. Sin embargo, es muy fácil convertir esta plantilla a la sintaxis anidada de Sass.

Clónalo, entra al proyecto y luego ejecuta:

```
sass-convert -F scss -T sass -i -R ./  && find . -iname “*.scss” -exec bash -c 'mv "$0" “${0%\.scss}.sass"' {} \;
```

Uso con Sass
Cuando se usa sass para construir esta plantilla, es necesario:

instalar sass si aún no está instalado:

```bash
npm install -g sass
```

ejecutar el comando de construcción desde la línea de comandos:

```bash
sass stylesheets/main.scss dist/main.css
```
