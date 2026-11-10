# Mi proyecto web: Guitarras
- **Nombre:** Antonio Serrano
- **Usuario de GitHub:** serraaa-ash
- **Tema:** Guitarras

## Por qué lo he elegido
Me gusta el mundo de las guitarras porque toco la guitarra flamenca desde hace un año, y creo que lo conozco lo bastante bien como para hacer una web sobre él. En ella quiero enseñar los distintos tipos de guitarras, accesorios y biografías de guitarristas.

## Qué he hecho en esta entrega
He hecho el index.html con una presentación mía, una foto de una guitarra española y una lista con mis 3 guitarras: mi Ritmo española, la Modesto Malla “Diego del Morao” que me gustaría tener y la Conde Hermanos que tocaba Paco de Lucía. También he puesto un enlace a la web de Modesto Malla y otro al XML. En datos.xml he guardado esas 3 guitarras con su marca, su tipo y su precio, y he marcado mi favorita.

## Palabra del día
contexto

## UD3 · Estructura HTML
- Le faltan las meta description, keywords y author en el head.
- No tiene bloques div, todo está suelto.
- No tiene h3, hr, blockquote ni pre.

### Validación W3C
| Página | Errores del validador | Cómo lo corregí |
|---|---|---|
| index.html | 0 | No tuvo errores |
| guitarras.html | 0 | No tuvo errores |
| guitarristas.html | 0 | No tuvo errores |
| accesorios.html | 0 | No tuvo errores |

### Qué he hecho en esta unidad
He completado la cabecera del index.html con las meta description, keywords y author, y he reorganizado el body en bloques div con comentarios, títulos h2 y h3, una frase de Paco de Lucía, una ficha con pre y entidades. Después he hecho el mapa del sitio y he creado tres páginas nuevas: guitarras, guitarristas y accesorios. Al final las he validado todas en el W3C y ninguna tenía errores.

## Mapa del sitio
| Fichero | title | Qué contiene |
|---|---|---|
| index.html | Inicio \| Guitarras Serrano | Portada: presentación, mis 3 guitarras, una cita de Paco de Lucía y la ficha de mi guitarra |
| guitarras.html | Mis guitarras \| Guitarras Serrano | Las 3 guitarras de datos.xml con su marca, tipo y precio |
| guitarristas.html | Guitarristas \| Guitarras Serrano | Guitarristas flamencos que me gustan: Paco de Lucía, Vicente Amigo… |
| accesorios.html | Accesorios \| Guitarras Serrano | Accesorios para tocar la guitarra: cejilla, cuerdas, afinadores… |
| contacto.html | Contacto \| Guitarras Serrano | Formulario para escribirme con consultas sobre guitarras y flamenco |

## Palabra del día (UD5)
día

## UD5 · Tablas y formularios
En la página guitarras.html voy a poner una tabla comparando varias guitarras españolas y flamencas, con su marca, tipo, madera y precio.
El formulario de contacto.html servirá para que los visitantes me escriban con consultas sobre guitarras y flamenco.

### Prueba con get
Al cambiar el formulario a method="get" y pulsar Enviar, la URL quedó así:

http://127.0.0.1:5500/proyecto/contacto.html?nombre=Prueba&email=prueba%40gmail.com&telefono=666666666&nivel=intermedio&tema=comprar&interes=flamenca-blanca&mensaje=Este+mensaje+es+de+prueba#

### Por qué uso post
Uso post porque con get todo lo que escribes (nombre, correo, teléfono…) sale en la URL y lo puede ver cualquiera. Con post se manda por dentro y no se ve.

### Validación W3C
| Página | Errores del validador | Cómo lo corregí |
|---|---|---|
| guitarras.html | 0 | No tuvo errores |
| contacto.html | 0 | No tuvo errores |

### Qué he hecho en esta unidad
He metido en guitarras.html una tabla para comparar cinco guitarras, con rowspan, colspan y todo eso. También he hecho la página de contacto con un formulario para que me escriban, y la he enlazado desde el index. Al final lo he pasado por el validador y no ha dado ningún error.