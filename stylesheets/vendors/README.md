# Vendors

Most projects will have a `vendors/` folder containing all the CSS files from external libraries and frameworks – Normalize, Bootstrap, jQueryUI, FancyCarouselSliderjQueryPowered, and so on. Putting those aside in the same folder is a good way to say “Hey, this is not from me, not my code, not my responsibility”.

If you have to override a section of any vendor, I recommend you have an 8th folder called `vendors-extensions/` in which you may have files named exactly after the vendors they overwrite. For instance, `vendors-extensions/_bootstrap.scss` is a file containing all CSS rules intended to re-declare some of Bootstrap’s default CSS. This is to avoid editing the vendor files themselves, which is generally not a good idea.

Reference: [Sass Guidelines](https://sass-guidelin.es/) > [Architecture](https://sass-guidelin.es/#architecture) > [Vendors folder](https://sass-guidelin.es/#vendors-folder)


La mayoría de los proyectos tendrán una carpeta vendors/ que contendrá todos los archivos CSS de bibliotecas y frameworks externos, como Normalize, Bootstrap, jQueryUI, FancyCarouselSliderjQueryPowered, entre otros. Separarlos en la misma carpeta es una buena manera de decir "Hey, esto no es mío, no es mi código, no es mi responsabilidad".

Si tiene que anular una sección de cualquier proveedor, le recomiendo que tenga una octava carpeta llamada vendors-extensions/ en la que puede tener archivos con el mismo nombre que los proveedores que sobrescriben. Por ejemplo, vendors-extensions/_bootstrap.scss es un archivo que contiene todas las reglas CSS destinadas a volver a declarar algunos de los CSS predeterminados de Bootstrap. Esto es para evitar editar los archivos del proveedor en sí, lo cual generalmente no es una buena idea.

Referencia: Sass Guidelines > Architecture > Carpeta de proveedores
