# Esto es un resumen

## De lo que se puede

### Hacer con markdown

#### Estos encabezados se crean añadiendo # al principio de la línea. Corresponden a las etiquetas <h#> en html.


Simplemente al escribir se va a ir generando un texto. **El texto puede modificarse, puede tener el estilo negrita rodeando el texto con 2 pares de asteriscos o de guiones bajos** (\*\*por ejemplo**). _También se puede escribir en cursiva rodeando el texto de un par de asteriscos o guiones bajos igualmente_ (\_por ejemplo_). Y también rayado ~~como esto~~ rodeando el texto con 2 pares de ~ (\~~por ejemplo~~).

---

Puedes crear 2 tipos de listas.

### Listas desordenadas

* Puedes escribir los elementos
* De 3 maneras diferentes
* Escribiendo un guión -, un símbolo de más + o un asterisco *
* Pueden ir intercalados y el resultado será el mismo
* * Si haces "`* * Elemento`" entonces tendrás un punto anidado en el anterior
* * Y puedes tener otro
* Y reanudar los puntos principales

### Listas ordenadas

1. Este tipo de lista
2. Se crea usando la sintaxis <número.>
3. Por ejemplo "`1. Elemento1`"
4. Y así sucesivamente

---

Se puede crear un bloque de código simplemente con la siguiente sintaxis:


```
(```)
bloque

de

código

Puede contener...


... varias líneas, hasta que terminen las comillas.

(```)
```

Los paréntesis son con fines demostrativos.

~~~
(~~~)

O también con 3 ~ (~~~)

Es exactamente igual

(~~~)
~~~

También comenzando las líneas con 4 espacios o un TAB.

    Y con indentaciones
    también

    funciona

También se puede crear `una sección de código` en la misma línea. Por ejemplo para especificar una secuencia de teclas como `Ctrl+C`  y `Ctrl+V`. Se hace rodeando el contenido con un par de comillas invertidas `.

---

Se pueden insertar enlaces. Se pueden hacer de la siguiente manera:

[texto para hacer el enlace]\(link_al_cual_enlazar_el_texto)

[Este es un ejemplo de enlace a google.com](https://google.com)

Los enlaces se pueden hacer de la manera anterior, o por referencia. Por ejemplo, [texto para hacer el enlace]\[variable_hola]

Y en cualquier parte del documento puedes establecer el enlace que `variable_hola` será. Esto es principalmente para organizar el documento.

Por ejemplo en la siguiente línea se establecerá el enlace https://google.com (ten en cuenta que este mismo enlace funciona como enlace) a `variable_hola` pero no saldrá en el documento, igualmente debajo de la asignación, se escribirá lo mismo pero escapado con el símbolo \ para que se pueda ver:

[variable_hola]: https://google.com
\[variable_hola]: https://google.com

En la forma anterior, se escribe el texto y seguidamente entre corchetes se especifica algún tipo de variable a la cual en cualquier parte del documento se le puede asignar un enlace real. Pero también funciona asignandole el enlace a ese mismo texto de la siguiente forma:
[texto para usar como enlace]

[texto para usar como enlace]: https://google.com
\[texto para usar como enlace]: https://google.com

De igual forma, para que se pueda ver en el documento, se tuvo que escapar la línea con el símbolo \.

---

También se pueden insertar divisiones de 3 maneras. Con guiones -, guiones bajos _ y asteriscos *. Se deben escribir almenos 3 para que funcione como separador. El anterior se hizo con 3 guiones simples. El siguiente se hará con 3 guiones bajos:

___


Y el siguiente con 3 asteriscos:

***

En algunos lugares, el que se hace con asteriscos se ve como una línea discontinua.

---

Se pueden incluir citas escribiendo el símbolo mayor que > y a continuación la cita. Si se desea escribir en varias líneas, para que la cita no se rompa, se debe agregar > al principio de la línea, y simplemente no escribir nada en ella. De esta manera se especifica que todas esas líneas pertenecen a la cita. Luce de la siguiente manera:

> Esto es un ejemplo de una cita que hizo alguien. Buenas tardes.
>
> ```
> Código dentro de la cita.
> 
> continúa el código hasta que terminen las triples comillas (```) en la siguiente línea.
> ```
>
> 
> > Esto es una cita dentro de la cita.
> >
> > Funciona igual que la anterior y se crea de la misma manera.
> > > Se pueden crear tantas citas anidadas...
> > > > ... como se desee.
> > > > >  Solamente tienes que añadir otro signo de mayor que >.
>
> > Esta es la segunda cita. la línea anterior solamente tiene un >, por lo que la segunda cita se rompe en 2 partes, la anterior y esta.
>
> Esta es la cita principal.
>
> También se pueden hacer listas dentro de una cita:
>
> * Tanto ...
> * desordenadas.
>
> 1. Como ...
> 2. ordenadas.
> ***
> También se pueden crear separaciones y encabezados de la misma forma.
>
> ---
> Simplemente agregando un > delante de la separación.
>
> # Esto es un encabezado de tipo H1
>
> ## Y esto es otro de tipo H2
>
> ### Y así suscesivamente
>
> ---