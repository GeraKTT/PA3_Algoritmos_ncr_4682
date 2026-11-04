# README — Evaluación

> **Curso:** ALGORITMO Y ESTRUCTURA DE DATOS BASADOS EN INTELIGENCIA ARTIFICIAL  
> **Código:** 4682  
> **Evaluación:** PA3   
> **Equipo:** Grupo 4  

## 1. Integrantes

| Integrante | Rol | Aporte principal |
|---|---|---|
| Geraldine Khatrina Tudela Theo | Desarrolladora | Desarrollo de la actividad 1: Representación gráfica, diseño de algoritmos de pila LIFO y Desarrollo de la actividad 3: Análisis y justificación del uso de estructuras LIFO y FIFO en situaciones reales. |
| Mijail Mendoza Chavez | Programador | Desarrollo de la actividad 2: Desarrollo de Cola FIFO, pseudocódigo e implementación en Java |
|Victor Manuel Fabricio Quispe Gonzales | Analista|Desarrollo de la Actividad 4: Comparación académica entre pilas y colas, elaboración del cuadro comparativo, redacción de la conclusión grupal y consolidación del README |
| [Nombre 4] | [Rol] | [Aporte] 
| [Nombre 5] | [Rol] | [Aporte] |

## 2. Descripción y objetivo

**Problema:**  
Una unidad de servicios académicos necesita gestionar dos procesos diferentes: el registro de acciones que deben deshacerse en orden inverso y la atención de solicitudes según su orden de llegada. Para ello, es necesario determinar qué estructura de datos permite organizar y procesar correctamente la información en cada situación.

**Objetivo:**  
Analizar y aplicar las estructuras de datos pila (LIFO) y cola (FIFO), comprendiendo sus características, operaciones y funcionamiento, para proponer soluciones que permitan gestionar las acciones y solicitudes de manera organizada y eficiente.

**Solución desarrollada:**  
Se desarrolló una propuesta basada en el uso de pilas y colas, incluyendo sus representaciones gráficas y algoritmos para insertar, retirar y consultar elementos. Asimismo, se analizaron situaciones reales para identificar la estructura más adecuada en cada caso y se elaboró una comparación de sus características, operaciones y ventajas, justificando su aplicación dentro del sistema académico.

## 3. Cómo ejecutar o revisar

```bash
El repositorio contiene el desarrollo de las cuatro actividades de la PA3, relacionadas con las estructuras de datos pila (LIFO) y cola (FIFO). Las soluciones se presentan mediante documentos que incluyen explicaciones, representaciones gráficas, pseudocódigos, aplicaciones y justificaciones.
```

**Pasos de revisión:**
1. Ingresar al repositorio de GitHub y revisar los archivos correspondientes a cada actividad.
2. Abrir o descargar los documentos para visualizar las explicaciones, representaciones gráficas, algoritmos y justificaciones desarrolladas.
3. Revisar la sección de evidencias del README, donde se muestran las capturas y los aportes realizados por los integrantes del equipo.

> No publicar contraseñas, tokens, credenciales ni datos sensibles.

## 4. Evidencias

Agregar aquí capturas, resultados, pruebas o enlaces que demuestren el funcionamiento.

- Evidencia 1:
  
Codigo:
<img width="1027" height="894" alt="codigo1" src="https://github.com/user-attachments/assets/66475d46-0a26-42dd-8147-d557464f9c70" />
<img width="1005" height="276" alt="codigo2" src="https://github.com/user-attachments/assets/9554ddc4-4129-49d9-8a27-7eb3b3c800f5" />
Ejecucion:
<img width="941" height="524" alt="ejecucion" src="https://github.com/user-attachments/assets/1384ac3b-f4bb-4e5e-a21d-795313088dba" />

- Evidencia 2:
<img width="1887" height="967" alt="4" src="https://github.com/user-attachments/assets/73d45212-1687-424d-b131-5c7886bb8871" />
<img width="1907" height="945" alt="3" src="https://github.com/user-attachments/assets/2ecf2a75-d882-4d70-a95d-a03fa97ab88d" />
<img width="1852" height="937" alt="2" src="https://github.com/user-attachments/assets/5c7ef3c0-6649-482f-ae6b-d36a1229cb6d" />
<img width="1847" height="947" alt="1" src="https://github.com/user-attachments/assets/14231f88-d3a9-4493-bf56-90d4c213060e" />
- Evidencia 3: Archivos de la actividad 3 subida al repositorio de GitHub, con registro de participación mediante commits.
- Evidencia 4: Documento finalizado de la Actividad 4 conteniendo el análisis comparativo entre Pilas y Colas, junto con la justificación técnica grupal sobre la selección de la estructura.

## 5. Matriz de participación

| Integrante | Desarrollo | Pruebas | Documentación | Exposición | Evidencia de participación |
|---|---|---|---|---|---|
| Geraldine Khatrina Tudela Theo | Alta | Media | Alta | Sí/No | Desarrollo de las actividades 1 y 3, representación gráfica de pila LIFO, pseudocódigo, análisis de casos, documentación y commits en GitHub. |
| mijail mendoza chavez | Alta | Alta | media | Sí/No | Desarrollo de Actividad 2, código Java y capturas. |
| Victor Manuel Fabricio Quispe Gonzales | Alta | Media | Alta | Sí | Desarrollo de la Actividad 4, cuadro comparativo, redacción de conclusiones y estructuración del README. |
| [Nombre 4] | [Alta/Media/Baja] | [Alta/Media/Baja] | [Alta/Media/Baja] | [Sí/No] | [Commits, avances, etc.] |
| [Nombre 5] | [Alta/Media/Baja] | [Alta/Media/Baja] | [Alta/Media/Baja] | [Sí/No] | [Commits, avances, etc.] |

## 6. Video de exposición

**Video público de YouTube:** 
- [https://www.youtube.com/watch?v=eF2kos8LJEE]

Todos los integrantes deben participar en la exposición con sus cámaras prendidas y explicar el procedimiento, la solución desarrollada y las decisiones tomadas.

## 7. Conclusiones

- Precisión LIFO (Pilas): Se determinó que la estructura de Pila es la única opción viable para gestionar el sistema de acciones que deben deshacerse. Al restringir el acceso únicamente por la parte superior (tope o cima), garantiza que se revierta siempre el cambio más reciente. Esto modela de forma segura los historiales con una eficiencia algorítmica de $O(1)$, de manera idéntica a cómo funciona el botón "atrás" de un navegador web.
- Equidad FIFO (Colas): Para el flujo de atención de solicitudes, se comprobó que la estructura de Cola asegura la equidad del proceso académico. Al permitir la inserción por el final (rear) y la extracción por el frente (front), mantiene un orden secuencial estricto, garantizando que el primer estudiante en llegar sea el primero en ser atendido. Esto replica sistemas reales como las colas de impresión o la planificación de procesos operativos con un rendimiento óptimo de $O(1)$.
- Impacto en la Arquitectura de Software: El desarrollo de esta evaluación demostró que la correcta selección entre una pila y una cola previene fallos críticos de funcionamiento. Intercambiar estas estructuras en el sistema académico habría corrompido la integridad de los datos (al deshacer la acción equivocada) o generado un flujo de atención injusto. Por tanto, elegir la estructura dinámica correcta es fundamental para modelar los procesos del mundo real con escalabilidad y eficiencia.
---

**Última actualización:** [03/11/2026]
