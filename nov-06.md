## Clase 06  de noviembre



#### Difrencia entre

- Llamada a sistema
  
  - Solicita un servicio del kernel

- API
  
  - Se comunica con una aplicación

**Interacciónes**

- Síncronas

- Asíncronas
  
  - Promesas de javascript
  
  - Fech para detener el flujo

- Interfaces Badas en eventos

- Eventos y Callbacks
  
  - callback fragmento de cófigo que se atiende cuando ocurre un evento

- Interfacer remotas
  
  - http
  
  - mqtt
    
    - modelo de publicación / suscripción
    
    - comunicaicón mediante un brocker
    
    - Frecuente en sistemas IOT
    
    - Ejemplo: ROST -> Sistema operatuvo para robots
    
    - Cooncepto de tópicos
    
    - Ejemplo yolo

ejecución en un sistema embebido

Procesos hilos y mtareas

- Procexo: Instancia de un programa en ejecuación

- Hijo:flujo de ejecuación de un proceso 

- Ventajas y riezgos de los hilos
  
  - Ventajas
    
    - separacion de responsabilidades 
  
  - Desventajas}
    
    - Condiciones de carrera 
      
      - Solucion: Exlsusipin mutiua ( C++ std::mutex )

- Tareas en RTOS
  
  - Una tarea es una unidad de ejecuación planificable
    
    - pila propia
    
    - estado de ejecución
    
    - prioridad -> mas tiempo de procesamiento
    
    - contexto que debe conservarse

- Conclusiones
  
  - Procesos organizan recursos y proporcionan aislamiento
  
  - hilos permiten varios flujos de ejecución
  
  - Tareas representan unidades de trabajo en ejecución
  
  - concurrencia requoiere sincronicación






