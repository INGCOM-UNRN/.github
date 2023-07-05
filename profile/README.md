## ¡Hola!

Aqui trataremos de reunir toda la información acerca de la carrera Ingeniería
en Computación de la Universidad Nacional de Rio Negro ubicada en la Sede 
Andina de San Carlos de Bariloche.

## ¿Que es la carrera?

### Objetivos

 * Desarrollar las habilidades propias de un Ingeniero de primer nivel
 * Desarrollar software sobre hardware propio
 * Procesamiento de datos y señales
 * Construir bases de datos
 * Trabajar sobre todas las etapas de un proyecto de Software
 * Trabajar en equipo con especialistas de diversa formación
 * Hacer peritajes informáticos
 
### ¿Cómo es la carrera?

En tres años, podes acceder al titulo intermedio de Técnico en Computación
y en dos años mas, al titulo de Ingeniero en Computación

### ¿Qué información hay acá?

Por ahora, enlaces a los calendarios de las materias en un formato que es
posible incorporar a telefonos que puedan emplear el formato iCal.

[UNRN - Ingeniería en Computación](https://www.unrn.edu.ar/carreras/Ingenieria-en-Computacion-78)

![Youtube](https://img.shields.io/youtube/channel/views/UCOfhdmTG9-tkcTm4TmsvrzQ?label=Ingenier%C3%ADa%20en%20Computaci%C3%B3n&style=social)

Calendario [General](https://calendar.google.com/calendar/embed?src=c_42sm1h4p62g11qkhlglcsmegro%40group.calendar.google.com&ctz=America%2FArgentina%2FBuenos_Aires)

### Correlativas

```mermaid
graph RL;
    subgraph 1A1C
    B6000[Matemática I];
    B6001[Intro ICom]
    T0002[ILEA]
    end
    subgraph 1A2C
    B6002[Física I] --> B6000
    B6003[Programación I] --> B6001
    B6004[Electrónica Digital]
    B6005[Química]
    end
    subgraph 2A1C
    B6006[Matemática II] --> B6000
    B6011[Física II] --> B6002
    B6008[Programación II] --> B6003
    B6009[Arq. Computadoras I] --> B6004
    end
    subgraph 2A2C
    B6010[Matemática III] --> B6006
    B6012[Analisis Circuitos] --> B6002
    B6007[Algebra y Geometría] --> B6000
    B5638[Inglés Tecnico]
    end
    subgraph 3A1C
    B6017[Seg. Laboral] --> B5638
    B6013[Bases de Datos] --> B6000
    B6014[Sist. Paralelos] --> B6009
    B6014 --> B6003
    B6016[Lab. Sist. Embed.] --> B6009
    end
    subgraph 3A2C
    B6015[Programación III] --> B6000
    B6018[Sistemas Operativos] --> B6009
    B6019[Señales y Sistemas] --> B6006
    B6019 --> B6012
    B6020[Redes] --> B6009
    end
    subgraph 4A1C
    B6021[Ingeniería Software] --> B6001
    B6021 --> B6008
    B6022[Probabilidad y Estadistica] --> B6006
    B6023[Electrónica Analógica] --> B6012
    B6024[Arq. Computadoras II] --> B6009
    end
    subgraph 4A2C
    B6025[Inteligencia Artificial] --> B6015
    B6025 --> B6021
    B6026[Optativa I*]
    B6027[Compiladores e Interpretes] --> B6008
    B6027 --> B6009
    B6028[Sistemas Operativos II] --> B6014
    B6028 --> B6018
    end
    subgraph 5A1C
    B5617[Economía y Org. Empresarial] --> T0002
    B6029[Optativa II*]
    B5672[Comunicaciones Analógicas y Digitales] --> B6019
    B5672 --> B6022
    B6030[Trabajo Social]
    end
    subgraph 4A2C
    B6030[Optativa III*]
    B6032[Seguridad Informática] --> B6020
    B6032 --> B6018
    B6033[Practica Profesional]
    end

```
