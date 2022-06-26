### PASO A PASO de toda las Tareas de QA en sus actividades de testing para trabajar en una Historia de Usuario:  
(el tiempo de trabajo dependerá de los Story Points que tenga la US)

_**AQUÍ SE PUEDE VISUALIZAR UN FLUJO COMPLETO DEL TRABAJO QA (siempre actualizado):**_ 

[https://docs.google.com/spreadsheets/d/1Z4d56hPeVxO8AJ1p-ZK5wHlT4WuSzOvjyf3JYk0AFqA/edit?usp=sharing](https://docs.google.com/spreadsheets/d/1Z4d56hPeVxO8AJ1p-ZK5wHlT4WuSzOvjyf3JYk0AFqA/edit?usp=sharing)

_**ISSUES STRUCTURES BRANCHING FLOW (ISBF)**_

## RECOMENDACIÓN: [PASO-A-PASO (Detallado) Proceso QA de US](https://upexsprint7.atlassian.net/wiki/spaces/UPEX/pages/296521/PASO-A-PASO+%28Detallado%29+Proceso+QA+de+US)

1.  PRIMERO QUE NADA → Transita la US al estado de "**in progress**" antes de continuar:
    

**A trabajar**:

*   **Análisis de Requerimientos de la US**.
    
*   **Estimación de la tarea asignada** “\[QA\] Análisis, Test Design y Test Execution” de acuerdo a la capacidad personal (colocar un estimativo de cuanto te tardarías haciendo todo)
    
*   **Creación de Test Set**, análisis con test exploratorio en este caso, estrategia de pruebas que se debería usar y derivación de validaciones por realizar. + (linkearlo a la US)
    
*   **Creación de los Test Cases**, diseñar solamente, de acuerdo a la derivación por el TS (agregar los TC al TS)
    
*   (\*Adicional para un trabajo super completo) → Añadir los Test Cases al Test Plan, y agregarlos a la Suite de Feature respectiva.
    
    *   **IMPORTANTE!!!! LEER 👀**[MAYOR COBERTURA DE PRUEBAS → MAYOR CALIDAD](https://upexsprint7.atlassian.net/wiki/spaces/UPEX/pages/295909)
        
*   **Creación del Test Execution** (ya sea desde el Test Plan o desde la US), agregar los TC, y muy importante: confirmar el Test Plan y Test Environment de la ejecución (linkearlo a la US)
    
*   **Ejecutar las pruebas por Test Run** (vista de ejecución), y Reportar cualquier Defecto encontrado de forma adecuada.
    
*   **En caso de encontrar un Bug o Defecto**, **reportarlo**, dejarlo en OPEN (linkear Defecto o Bug a la US afectada).
    
    *   Luego de que Ely (suponiendo que sea el Dev) revise el Reporte, lo moverá al estado “Re-Test
        
        *   Proceder a crear la tarea. “Re-Test Execution” dentro del Defecto/Bug (ver clase de Re-Testing para conocer el proceso)
            
            *   Añadir el TC que falló y encontró el Defecto/Bug, y ejecutar nuevamente (como simulación, se supondrá que el Bug ha sido fixeado, y se deberá cerrar la tarea y el bug posteriormente)
                
*   **Asegurarse de marcar toda la trazabilidad** (que todo esté correctamente linkeado) →(Guía de Trazabilidad se puede encontrar en los marcadores del Bootcamp)
    
*   **Loguear las horas trabajadas en la actividad de la tarea asignada** “\[QA\] Análisis, Test Design y Test Execution”
    

Si tienen dudas, háganmelo saber, así podré cada vez mejorar esta guía (igual pronto haré una guía más completa y específica)

## ADICIONAL! PARA SER UN MEJOR TESTER Y CONTRIBUIR EN UPEX:

[https://youtu.be/cybq5xXY2Po](https://youtu.be/cybq5xXY2Po)