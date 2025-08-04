# Plan de Estudios
Ingeniería en Computación UNTREF, Plan 2022

```mermaid
---
title: Ingeniería en Computación - UNTREF
---
flowchart TD
    classDef aprobada fill:#0e6902
    classDef enCurso  fill:#186328
    classDef regularizada fill:#c9bc04

    id1[Introducción a la Ingeniería en Computación]:::aprobada
    id2[Introducción a la Problemática del Mundo Contemporáneo]:::aprobada
    id3[Algoritmos y Programación I]:::aprobada
    id4[Álgebra I]:::aprobada
    id5[Matemática Discreta]:::aprobada
    id6[Problemas de Historia del Siglo XX]:::aprobada
    id7[Algoritmos y Programación II]:::regularizada
    id8[Programación de Bajo Nivel]:::aprobada
    id9[Álgebra II]:::aprobada
    id10[Diseño Lógico]
    id11[Análisis Matemático I]:::aprobada
    id12[Cuestiones de Sociología, Economía y Política]:::aprobada
    id13[Estructura de Datos]
    id14[Arquitectura de Computadoras I]
    id15[Inglés Básico]:::aprobada
    id16[Optativa Tecnicatura - IA]:::aprobada
    id17[Análisis Matemático II]:::aprobada
    id18[Cultura Contemporánea]:::aprobada
    id19[Sistemas Operativos]
    id20[Inglés Técnico]:::aprobada
    id21[Taller de Lectoescritura]
    id22[Ingeniería de Software]:::regularizada
    id23[Física I]:::aprobada
    id24[Comunicación de Datos]
    id25[Base de Datos]
    id26[Asignatura Optativa Ingeniería]
    id27[Física II]:::aprobada
    id28[Redes de Computadoras]
    id29[Diseño y Arquitectura de Sistemas de Computación]
    id30[Probabilidad y Estadística]
    id31[Trayecto Formativo Alternativo]
    id32[Matemáticas Especiales]:::aprobada
    id33[Dispositivos Eléctronicos]
    id34[Álgebra III]:::aprobada
    id35[Ingeniería de Calidad]
    id37[Asignatura Electiva]
    id38[Laboratorio de Electrónica]
    id39[Construcción de Sistemas de Computación]
    id40[Procesamiento de Señales]
    id41[Metodología de la Investigación]
    id43[Asignatura Electiva]
    id44[Sistemas Embebidos]
    id45[Sistemas Ciberfísicos]
    id46[Control Automático]
    id47[Ética y Legislación]
    id48[Higiene y Seguridad]
    id49[Práctica Profesional Supervisada]
    id50[Trabajo Final Integrador]

    subgraph a1 ["Primer Año"]
        subgraph Comunes1
        id2
        id6
        end
    id1
    id2
    id3
    id4
    id5
    id6
    id7
    id8
    id9
    id10
    end

    subgraph a2 ["Segundo Año"]
        subgraph Comunes2
        id12
        id18
        id21
        end
    id11
    id12
    id13
    id14
    id15
    id16
    id17
    id18
    id19
    id20
    id21
    end

    subgraph a3 ["Tercer Año"]
    id22
    id23
    id24
    id25
    id26
    id27
    id28
    id29
    id30
    end

    subgraph a4 ["Cuarto Año"]
    id31
    id32
    id33
    id34
    id35
    id37
    id38
    id39
    id40
    id41
    end

    subgraph a5 ["Quinto Año"]
    id43
    id44
    id45
    id46
    id47
    id48
    id49
    end

    a1  -.->a4
    a1  -.->a5
    a2  -.->a4
    a2  -.->a5

    id4 -->id9
    id4 -->id11
    id13-->id25
    id20-->id25
    id17-->id30
    id8 -->id19
    id13-->id19
    id11-->id23
    %%Álgebra III

    id11-->id17
    id10-->id14
    id7 -->id13
    id1 -->id8
    id3 -->id10
    id1 -->id10
    id5 -->id10
    id3 --> id7
    id22-->id29
    id19-->id29
    id19-->id24
    id23-->id27
    id17-->id27
    id7 -->id22
    id20-->id22
    id15-->id20
    id33-->id38

    %%Procesamiento de Señales
    id32-->id40
    id34-->id40

    %%Construcción de Sistemas de Computación
    id28-->id39
    id29-->id39

    %%Ingeniería de Calidad
    id22-->id35
    id30-->id35

    id24-->id28
    id27-->id33

    id22-->id41
    id35-->id47
    id35-->id48
    id32-->id46
    id33-->id44
    id39-->id44
    id39-->id45

    %%Práctica Profesional Supervisada
    a1 -.->id49
    a2 -.->id49
    a3 -.->id49
    id34-->id49
    id32-->id49
    id35-->id49
    id31-->id49

    %%Trabajo Final Integrador
    a1 -.->id50
    a2 -.->id50
    a3 -.->id50
    a4 -.->id50
    a5 -.->id50
```
