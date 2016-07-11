# Markdown
---
**Que es Mark down?**   
>Markdown es un lenguaje de marcado ligero, emplea texto plano, procurando que sea legible pero consiguiendo que se convierta en XHTML correctamente formateado.

---
**Donde se utiliza?**   
>Empieza a ser muy popular y utilizado entre los programadores, funciona para agregar formato a textos web e igual podemos usarlo hasta para realizar lista de tareas pendiente.

>En editores visuales de blogs,ya que generar HTML puede resultar engorroso y espantoso, markdown nos permite escribr en cualquier lado y en cualquier formato y asi no preocuparse por equivocarnos en el codigo, HTML puede convivir con algunos errores mínimos, pero no es la idea. Markdown soluciona todo esto.

---

**Cuales son las palabras claves mas utilizadas en Markdown?**    

> **Cabeceras**
 >> ```# Esto es un H1, ## Esto es un H2, ### Esto es un H3```
 >>> # Esto es un H1
 ## Esto es un H2
 ### Esto es un H3

> **Párrafos**
>>      Para crear párrafos se deja una línea en blanco.
>>
      Este es el primer párrafo.
>>      
      Este es el segundo párrafo.
>>> Este es el primer párrafo.
>>>
Este es el segundo párrafo.


> **Enlaces con titulo**
>>``` [Con titulo](https://www.facebook.com/hipatiadevhouse "titulo")  ```
>>> [Con titulo](https://www.facebook.com/hipatiadevhouse "titulo")

> **Enlaces sin titulo**
>>``` [Sin titulo](https://www.facebook.com/hipatiadevhouse ```
>>>[Sin titulo](https://www.facebook.com/hipatiadevhouse)

> **Formato negritas**
>> ``` **Esto es negrita** | __Esto es negrita__ ```
>>>**Esto es negrita**

> **Formato cursiva**
>>```  *Esto es cursiva* | _Esto es cursiva_  ```
>>>*Esto es cursiva*

>**Formato negrita y cursiva**
>>```***Esto es negrita y cursiva*** | ___Esto es negrita y cursiva___```
>>>***Esto es negrita y cursiva***

>**Cita**
>> ```> ```
>>> > Esto es parte de un bloque de cita.   
> Esto es parte del mismo bloque de cita.
>>>

>**Listas**
>>    
    Lista numerada (ordenada)
    1. Este es el primer elemento
    2. Este es el segundo elemento
    3. Este es el tercer elemento
>>      
    Lista de puntos (desordenada)
      * Un elemento de la lista
      * Otro elemento de la lista
      * El tercer elemento de la lista
>>      
    Se pueden emplear también + y - en vez de *
      * Un elemento de la lista
      + Otro elemento de la lista
      - El tercer elemento de la lista
>>      
    Se pueden mezclar distintos tipos de listas
    y anidar unas dentro de otras.
      1. Esto es una lista ordenada
      2. Segundo elemento de la lista ordenada
          1. Esta es una lista ordenada anidada dentro de otra
              * Lista desordenada anidada a tercer nivel
              * Segundo elemento de esta lista
          2. Este es el segundo elemento de la lista ordenada anidada



>>> Lista numerada (ordenada)
1. Este es el primer elemento   
2. Este es el segundo elemento
3. Este es el tercer elemento

>>> Lista de puntos (desordenada)
* Un elemento de la lista
* Otro elemento de la lista
* El tercer elemento de la lista

>>> Se pueden emplear también + y - en vez de *
* Un elemento de la lista
+ Otro elemento de la lista
- El tercer elemento de la lista

>>> Se pueden mezclar distintos tipos de listas y anidar unas dentro de otras.
1. Esto es una lista ordenada
2. Segundo elemento de la lista ordenada
  1. Esta es una lista ordenada anidada dentro de otra
    * Lista desordenada anidada a tercer nivel
    * Segundo elemento de esta lista
  2. Este es el segundo elemento de la lista ordenada anidada

>**Imagenes**
>>
~~~
![Con titulo](imgtuto/hipatia.png
      "titulo")
~~~

   >>> ![Con titulo](imgtuto/hipatia.png "titulo")

>**Imagenes**  
>>
~~~
![Sin titulo](pictures/avatar.png)
~~~
>>> ![Sin titulo](imgtuto/hipatia.png)

>**Codigo**
>>  
    Esto es un párrafo normal.  
      Esto es un párrafo de código. <--cada línea de este bloque empiece por al menos 4 espacios o 1 tabulado.
    ~~~
    Esto es otro párrafo de código.
    ~~~
    ```Esto es un tercer párrafo de código.```

>>>Esto es un párrafo normal.  
>>>
        Esto es un párrafo de código.
~~~
    Esto es otro párrafo de código.
    ~~~
    ```Esto es un tercer párrafo de código.```

>**Lineas Horizontales**
>>
~~~
---
____
***
~~~
>>> ---
___
***
