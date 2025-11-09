# Modelo 4+1 (En base a Kruchten)

El modelo 4+1 posee las siguientes vistas:

- **Vista lógica:** Contendrá lo vinculado a los usuarios finales y mostrará las funcionalidades del sistema.  
- **Vista de procesos:** Parte enfocada a los integradores, donde se puede analizar el rendimiento y la escalabilidad.  
- **Vista física:** Utilizada por el personal de sistemas. Contiene diagramas sobre la topología del software y la comunicación entre dispositivos.  
- **Vista de desarrollo:** Incluye todo lo necesario para que los desarrolladores implementen y administren el software.  
- **Escenarios (+1):** Integran las demás vistas a través de ejemplos o recorridos concretos que muestran cómo interactúan los distintos elementos del sistema.

---

## Diagramas de la Vista Lógica

- **Diagrama de clases**  
- **Diagrama de casos de uso**  
- **Diagrama de secuencia**

---

## Diagramas de la Vista de Procesos

- **Diagrama de actividad:** Representa el flujo de procesos y actividades internas del sistema, incluyendo aquellas que pueden ser iniciadas por el usuario.

---

## Diagramas de la Vista de Desarrollo

- **Diagrama de paquetes:** Agrupan clases de una misma capa; se identifican como unidades lógicas y poseen una alta cohesión.  
- **Diagrama de componentes:** Agrupan paquetes que representan módulos lógicos o unidades de despliegue de software con interfaces definidas.

---

## Diagramas de la Vista Física

- **Diagrama de despliegue:** Representa cómo se establecerán las comunicaciones entre cada componente.  
- **Diagrama de topología:** Muestra la disposición física o la infraestructura donde se ejecutan los componentes del software.  

Ambos diagramas incluyen nodos, conexiones y protocolos de comunicación.  
(Ver estándar [IEEE 1471](http://www.iso-architecture.org/42010/cm/cm-1471-2000.html) y [C4 Model](https://c4model.com))

---

## Escenarios (+1)

- **Desarrollo de casos de uso:** Unifica todo lo que ocurre en el sistema de forma narrativa, tomando como referencia cada caso de uso de forma individual.  
  Son ejemplos o recorridos concretos que atraviesan las cuatro vistas.  
  No agregan nuevos diagramas, sino que reutilizan los existentes para ilustrar un flujo real del sistema.

---
