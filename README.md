# taller-markdown-pruebas-Andrei
Repositorio para hacer pruebas con Markdown

# Esto es un encabezado h1

Esto es un párrafo.

## Esto es un encabezado h2

Esto es un párrafo.

Y esto es otro párrafo.

**Esto es negrita\****

*Esto es cursiva\**

Ejecutamos el comando : `ls-la` Resaltamos con comillas \`\`

Si ponemos las 3 comillas podemos resaltar en bloque:
```javascript
Hola
```
Yaml:
```yaml
version: '3'

services: 
  apache:
    build: ./apache
    ports: 
      - 80:80
    volumes:
      - ./src:/var/www/html
```

Consola:
```bash
#!/bin/bash
echo "Hola mundo"
```

# Referencias

- [Texto del enlace](Enlace)
- [GitHub][1]
- Siqueremos usar muchas veces un vinculo, podemos añadirlo como referencia. 
```
[1]: https://github.com
```

## Imagenes

![](https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png)
```
![](https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png)
```

![](./imagenes/butterfly-8177808_1280.jpg)

```
![](ruta Relativa a la imagen)
```
## Listas

* Prueba1
* Prueba2
    * Prueba 3

1. Nombre
2. Apellido
3. [GitHub][1]







[1]: https://github.com
