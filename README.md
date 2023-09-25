# Markdown_JGI 

## Este es un repositorio de prueba de [MarkDown][2]  
El texto de arriba saldra como un titulo "h2" 

## Esta es la prueba del emcabezado 2.

### Este es un encabezado con h3. 
Dependiendo de cuentos `#` pongamos, el titulo se hará mas pequeño.

## USO DE LETRAS.

*Este texto es en cursiva*

**Texto en negrita**

## COMANDOS 

`ls-la` o `sudo apt-get update`

## BLOQUES DE CODIGO

Reserva las palabras reservadas que se va encontrando. Como por ejemplo:

```bash
#!/bin/bash
echo "Hola mundo"
```

```python
celsius = float(input('Introduce una temperatura en grados Celsius: '))
farenheit = (1.8 * celsius) + 32
print(f'La temperatura en grados Farenheit es: {farenheit}')
```

## ENLACES o REFERECIAS

-[Aqui va el texto del enlace a la página de jose juan.](https://josejuansanchez.org/iaw/taller-markdown/index.html)

- [Ir a openWebinars](https://openwebinars.net/academia/)


### Referencia de otro enlace
 Este es el metodo 2, utilizando un valor que colocaremos a lado del otro titulo que queramos.

 Hay que poner doble corchete. **Ejemplo**: *[Texto][El número del URL]* 

 [2]: https://josejuansanchez.org/iaw/taller-markdown/index.html


## Insertar Imágenes en MarkDown.

Para insertar una imagen lo que tendremos que hacer es lo sigiente: Seleccionar la URL de la página o por ejemplo de la captura del ordenador. 

Se tiene que poner delante lo siguiente : **![](imagen remota)** esta sería la sintaxis.

***Ejemplo***: ![](https://static.motor.es/fotos-jato/bmw/uploads/bmw-serie-3-632a2d49f0e84.jpg)

*En la imagen anterior tenemos que copiar la URL de la imagen en google, si no, nos saldrá toda la página*

Asi se hace para añadir las otras imagenes desde una carpeta que tengamos guardada:

#### Direntes fotos desde mi carpeta personal de mi ordenador.
![](/imagenes/imagen1.jpg)
![](/imagenes/imagen2.jpg)
![](/imagenes/imagen3.jpg)


## LISTAS ORDENADAS.

*Asi saldría con listas desordenas que son las que empiezan por un ***puntito***

*Ejemplo:* 
* Item 1
* Item 2
* Item 3
* Item 4
- Si utilizamos el tabulador hace los siguiente.
    - Item 5
        - Item 6


*_DATO_*: Se puede poner tanto el `*` como el `-` para hacer la lista.

*Asi saldría una lista ordenada que son las que empiezan por un **número**.

*Ejemplo:* 
1. Item 1
2. Item 2
3. Item 3
4. Item 4

### Como poner todo junto.

Esto es un texto
  que sale todo junto.


### Comentarios

Se utilizan los caracteres `<!` y la linea del comentario terminando en `-->``