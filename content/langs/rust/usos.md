+++
title = "Rust y sus usos"
description = """En este post veremos los principales usos de Rust, el lenguaje
de programación de sistemas de memoria segura; así como lo que también puedes
hacer con este lenguaje pero que quizá sea mejor hacer con otro."""
date = 2022-01-03
weight = 1
+++

Rust es un lenguaje de programación de sistemas (_system programming language_),
lo que da mucho control sobre los recursos del sistema: memoria, etc. Es decir,
todo lo que puedas hacer de bajo nivel en C/C++, se podrá hacer en Rust: bases
de datos, compiladores, redes de bajo nivel...

¿Qué se puede hacer con Rust?

# CLI (Command Line Interface)
Son aquellas programas que se ejecutan en una consola, sin interfaces gráficas.

Estas, al ser más sencillas que otras, son mejores para comenzar. Es
recomendable buscar algo que te sea útil e intentar implementarlo.

# Web assembly
Gracias a Web Assembly, podemos usar lenguajes como Rust, C/C++ y otros para
obtener rendimiento extra, casi a nivel nativo, a la vez que JavaScript.

Lógicamente, debemos usar Web Assembly en operaciones o aplicaciones que
requieran ese rendimiento, como procesamiento de imágenes, audio, juegos,
operaciones matemáticas complejas, físicas, etc; pero no sencillas operaciones
que simplemente se solucionarían con JavaScript.

# Applicaciones de servidor
Rust también permite crear servidores eficientes, robustos y escalables. Con
frameworks ya listos para producción como [Rocket](https://rocket.rs/) o
[Actiz](https://actix.rs/); drivers nativos a Bases de Datos como:

+ [MongoDB](https://www.mongodb.com/es)
+ [SQLite](https://www.sqlite.org/index.html)
+ [PostgreSQL](https://www.postgresql.org/)
+ [MySQL](https://www.mysql.com/)

El ecosistema es bastante maduro, por lo que encontrarás todas las
funcionalidades básicas necesarias, pero no hay ningún framework que destaque.

# Embedded systems
Programar aplicaciones eficientes para relojes inteligentes, chips, Rasberry Pi,
etc; aquellos dispositivos centrados en determinadas tareas, normalmente forman
parte de un sistema más grande.

# Otras aplicaciones
Estas otras opciones, Rust todavía no puede competir con otras opciones más
establecidas.

+ Desarrollo de videojuegos: todavía no hay ningún framework super maduro, pero
igualmente la comunidad ha conseguido crear algunos juegos.
+ GUI: Hay algunas librerías que se podrían usar, pero todavía están muy verdes.

# Aplicaciones que no se deberían hacer con Rust
Básicamente cualquier cosa que no necesite de un rendimiento extremo, porque hay
opciones mucho más sencillas que utilizar un lenguaje de programación de tan
bajo nivel. Hazte un favor a ti mismo y usa algo más fácil.