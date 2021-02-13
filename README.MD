# Cabeceras
# Cabecera H1
## Cabecera H2
### Cabecera H3
#### Cabecera H4
##### Cabecera H5
###### Cabecera H6


# Underlines
Underline 1
-----------

Underline 2
===========

# Formatos de énfasis
- Formato *italica* de la Primer forma.
- Formato _italica_ de la Segunda forma.
- Formato **bold o strong** de la primer forma
- Formato __bold o strong__ de la segunda forma
- Formato ~~tachado~~

# Listas
3. Esto es un item de lista ordenada
1. Esto es un item de lista ordenada
2. Esto es un item de lista ordenada

- Esto otro item de lista desordenada
- Esto otro item de lista desordenada
- Esto otro item de lista desordenada

# Links
- <a href="http://google.com">Esto es un link en html </a>
- [Esto es un link en markdown](http://google.com)
- [Esto es un link al index](index.html)

# Imagenes
![Logo Github](https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png) 

# Code Snippets
- SQL
```SQL
{
CREATE TABLE "topic" (
    "id" serial NOT NULL PRIMARY KEY,
    "forum_id" integer NOT NULL,
    "subject" varchar(255) NOT NULL
);
ALTER TABLE "topic"
ADD CONSTRAINT forum_id FOREIGN KEY ("forum_id")
REFERENCES "forum" ("id");

-- Initials
insert into "topic" ("forum_id", "subject")
values (2, 'D''artagnian');
}
```

# Tablas
| Nombre | Apellido | Documento |
| ------ | -------- | --------- |
| Dario | Medina | 41867876 |
| Kylian | Mbappe | 45655497 |

# Citas
Esto es un texto referente a una que pondremos debajo:
> Esto es una cita.

Esto es otro texto q no se relaciona con la cita anterior
> Otra cita

# Lineas Divisoras
Texto para dividir

---

Otro texto

***

Otro mas

___


# Saltos de linea
Esto es nuestro primer parrafo

Esto es nuestro segundo parrafo, separado por un espacio.

Esto es nuestro tercer parrafo, separado por un espacio.