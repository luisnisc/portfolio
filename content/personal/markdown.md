+++
title = 'Markdown'
date = 2024-10-04T13:38:22+02:00
draft = false
+++

Markdown es un lenguaje de marcado ligero que puedes usar para añadir formato a tus documentos de texto. Aquí te mostramos cómo usarlo.

# Encabezado 1

## Encabezado 2

### Encabezado 3

**Este texto está en negrita**
_Este texto está en cursiva_

- Elemento 1
- Elemento 2
- Elemento 3

1. Primer elemento
2. Segundo elemento
3. Tercer elemento

[Enlace a Google](https://www.google.com)

![Descripción de la imagen](https://ruta/a/la/imagen.jpg)

\```
Este es un bloque de código
\```

| Encabezado 1 | Encabezado 2 |
| ------------ | ------------ |
| Fila 1       | Columna 1    |
| Fila 2       | Columna 2    |

> Esta es una cita.

- [x] Tarea completada
- [ ] Tarea pendiente

Este es un ejemplo de `código en línea`.

{{< youtube 4x678Pwpk6A >}}

```mermaid
gitGraph
    commit
    commit
    branch develop
    checkout develop
    commit
    commit
    checkout main
    merge develop
    commit
```

```mermaid
timeline
    title History of Social Media
    2002 : LinkedIn
    2004 : Facebook
    2006 : Twitter
    2010 : Instagram
    2011 : Snapchat
    2016 : TikTok
```

```mermaid
gantt
    title A Gantt Diagram
    dateFormat  YYYY-MM-DD
    section Section
    A task           :a1, 2024-10-04, 30d
    Another task     :after a1, 20d
    section Another
    Task in sec      :2024-10-04, 12d
    another task     :after a1, 24d
```

{{% resources style="primary" expanded="false" /%}}

<!-- {{<text color="red" angle="180">}}

{{<text color="blue" angle="90">}}

{{<text color="green" angle="270">}}

{{<text color="yellow" angle="0">}}

{{<text color="purple" angle="45">}}

{{<text color="orange" angle="135">}}

{{<text color="pink" angle="225">}}

{{<text color="brown" angle="315">}}

{{<text color="black" angle="270">}}

{{<text color="white" angle="0">}} -->

{{<objetivos titulo="Primera Lista">}}Titulo1
Titulo2
Titulo3
Titulo4
Titulo5
Titulo6
Titulo7
Titulo8{{</objetivos>}}
{{<objetivos titulo="Segunda Lista">}}Titulo9
Titulo10
Titulo11
Titulo12
Titulo13
Titulo14
Titulo15
Titulo16{{</objetivos>}}
