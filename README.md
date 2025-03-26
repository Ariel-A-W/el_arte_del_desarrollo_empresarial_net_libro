# **El Arte del Desarrollo Empresarial con Microsoft .NET Core**

![](images/Cover_book.png)

# Prólogo

El mundo del desarrollo de software ha evolucionado rápidamente en los últimos años, y en medio de esta revolución tecnológica, Microsoft .NET Core ha emergido como uno de los pilares fundamentales para la creación de soluciones empresariales de alto rendimiento y escalabilidad. Este libro nace con el propósito de llenar un vacío en la literatura técnica actual. El enfoque principal es la de proporcionar una guía avanzada que, no solo cubra los fundamentos de Microsoft .NET Core, sino que ofrezca una profundización práctica y técnica para profesionales que buscan llevar a cabo todas sus habilidades a un siguiente nivel.

A lo largo de toda esta obra técnica podrás encontrarás un completo recorrido y detallado de aquellos aspectos más avanzados del desarrollo de software en Microsoft .NET Core. Esta obra no está dirigido únicamente para los desarrolladores senior, con una vasta cantidad de años de experiencia sino también para un público más junior que busca profundizar en todos estos temas.

Si bien, en esta obra cubro el uso de conceptos complejos y el uso patrones de diseño avanzados, por otra parte en este libro, también cubro aspectos específicos siendo escritos y pensando para aquellos desarrolladores junior, aquellos menos experimentados, que quieren profundizar y comprender las mejores prácticas utilizadas en la industria del desarrollo del software. La intención es que cualquier profesional, sin importar su nivel, encuentre en estas páginas un recurso que lo impulse hacia la excelencia técnica.

En resumen, este libro está diseñado para profesionales del desarrollo que buscan mejorar su comprensión técnica y práctica de Microsoft .NET Core en un contexto empresarial. Está dirigido tanto a desarrolladores senior, que necesitan un enfoque más profundo para resolver problemas complejos, como a junior, que desean expandir sus conocimientos más allá de los conceptos básicos y adentrarse en un mundo de soluciones reales, escalables y avanzadas.

Nuestro objetivo es que, al finalizar este libro, cada lector se sienta capacitado para enfrentar los desafíos del desarrollo en un entorno industrial moderno, con todas las herramientas, patrones y mejores prácticas que hoy en día definen la excelencia en el desarrollo de software. Este no es solo un libro para aprender, es un manual para la implementación práctica y efectiva en proyectos del mundo real. ¡Bienvenido a un nuevo nivel de desarrollo en Microsoft .NET Core!

Autor, Ariel Alejandro Wagner

---

## Temario del Libro

Prólogo

Prólogo 

Capítulo 1

Introducción
Arquitecturas Avanzadas y Patrones de Diseño
Los Servicios API
Gestión de Fuentes de Datos
Despliegue y Mantenimiento de Microservicios
Procesos para la Seguridad Operacional y Funcional
Procesos de Pruebas, Optimización y CI/CD
Inteligencia Artificial Aplicada al Ámbito del Desarrollo de Software
Desafíos para las Soluciones Empresariales Reales

Capítulo 2

Arquitectura Avanzada
¿Qué es la Arquitectura y qué es el Diseño del Software?
Comportamiento y Arquitectura
Juicio a los Valores
Dimensiones que Rodean la Arquitectura del Software
Desarrollo
Despliegue
Operación
Mantenimiento
Opciones Abiertas
Dependencia de los Dispositivos
Arquitecturas Disponibles
Tipos de Arquitecturas
Patrones de Diseño
Patrones vs. Antipatrones
Tipos de Patrones Modernos
Arquitectura Universal de 3 Capas
Analizando el Código
Patrón Inyección de Dependencias
Métricas
Parámetros Utilizados en la Medición
Mantenibilidad
Complejidad Ciclomática
Profundidad de Herencia o Anidación
Factor de Acoplamiento
Líneas por Código
Complejidad Cognitiva
Métrica Halstead
Métricas LCOM (Lack of Cohesion of Methods)
Índice de Reutilización de Código (Code Reuse Index)
Cobertura del Código (Code Coverage)

Capítulo 3

Arquitecturas Modernas
Arquitectura DDD (Domain Driven-Design) – (DDD Architecture)
Dominio
Subdominio
Identificando los Límites de los Subdominios
Análisis para un Caso de Estudio sobre Datos
La Gran División de los Datos
Malla de Datos
Modelando la Lógica de Datos y el Dominio
Datos Como Producto
Arquitectura Lógica, la Arquitectura Cuántica
Analizando el Código para un Caso de Arquitectura DDD
Uso para Colección de Datos
Uso para Bases de Datos
Arquitectura Hexagonal (Hexagonal Architecture)
¿Cuál Fue el Motivo de su Creación?
Descripción de los Puertos y Adaptadores
Puertos y Adaptadores Primarios y Secundarios
Dominio Hexagonal
Entidades
Objeto de Valor
Aplicación Hexagonal
Caso de Uso
Framework Hexagonal
Operaciones de Conducción y los Adaptadores de Entrada y Salida
Representación para un Caso de Uso Sencillo
Analizando Código para un Caso de Arquitectura Hexagonal
Métricas de esta Arquitectura
Arquitectura Limpia (Clean Architecture)
Principios de la Arquitectura Limpia
Componentes Claves
Entidades
Atributos y Métodos de las Entidades
Relaciones entre Entidades
Casos de Usos
Adaptadores
Capas Externas
¿Qué Son las Capas Externas?
Principios Fundamentales de las Capas Externas
Interface de Usuario – UI (User Interface)
Otros Servicios Externos
Analizando el Código para un Caso de Arquitectura Limpia
Infraestructura
Dominio
Aplicación
Web API
DTO (Data Transfer Object)
Arquitectura de Motores de Datos
Gestión Convencional o Nativa
Tecnología DAO
Tecnología ADO y ADO.NET
Objetos Comunes de ADO.NET
Librerías para el Acceso y Manipulación de Datos
Clase Connection
Clase DataAdapter
Clase DataSet
Clase DataReader
Clase Command
Clase Parameters
Resumen de Comparación Rápida Final
Motores ORM
¿Qué es un Motor ORM?
La Tecnología de Entity Framework
Modelos de Desarrollo en Entity Framework
Dándole Vida a los Datos
Acceso y Cambios de Datos en las Entidades
Arquitectura de Entity Framework
El Modelo de los Datos de la Entidad - EDM
Componentes Clave del Motor Entity Framework
DbContext
DbSet
Migrations
LINQ (Lenguage Integrated Query)

Capítulo 4

Patrones
Antipatrones vs. Patrones
Prácticas No Recomendadas y Recomendadas
Código Spaghetti
God Object (Objeto Dios)
Reinventar la Rueda
Deficiencias Generales en las Prácticas del Desarrollo del Código
El Martillo de Oro (Gold Hammer)
Flujo de Lava (Lava Flow)
Poltergeist
Programación de Culto al Cargo (Cargo Cult Programming)
Prevención de Antipatrones
Patrónes S.O.L.I.D.
Single Responsibility Principle (SRP)
Ejemplo
Open/Closed Principle (OCP)
Ejemplo
Liskov Substitution Principle (LSP)
Ejemplo
Interface Segregation Principle (ISP)
Ejemplo
Dependency Inversion Principle (DIP)
Ejemplo
Patrones GoF
Otras Alternativas
Resolviendo Problemas
Hallando la Solución Más Apropiada
Determinando la Granularidad de un Objeto
Profundizando sobre los Patrones GoF
Creational
Abstract Factory
Factory Method
Builder
Protoype
Singleton
Structural
Adpater
Bridge
Composite
Decorator
Facade
Flyweight
Proxy
Behavioral
Interpreter
Templated Method
Chain of Responsability
Command
Iterator
Mediator
Memento
Observer
State
Strategy
Visitor
Patrón CQRS (Command and Query Responsibility Segregation)
Introducción
Propuesta Tradicional
Propuesta de CQRS
Comandos
Consultas
Generalidades
El Patrón MediatR
Profundizando
Librería MediatR
Descripción General de MediatR
Característica Clave
Arquitectura
Aspectos de Usabilidad de MediatR
Clean Architecture – Arquitectura Limpia
Aplicación – Caso de Uso
Domain
Infraestructura
Características Clave de MediatR para CQRS
Application
Query
Command
Api
Repositorio

Capítulo 5

Diseño e Implementación de API
¿Qué es una API?
Razones de Usos
Tipos de API
CORBA
Características Clave de CORBA:
Funcionamiento Básico
REST
API RESTful
Características Claves de las APIs RESTful
Ventajas de una API RESTful
Cuestiones de Diseño
Aspectos Claves para el Diseño
Datos Sensibles vs Datos Útiles
Anatomía de una API Clásica
Formato de los Datos de las Solicitudes y Respuestas
API Basado en el Uso de Clases Clásicas
Manejo de las Solicitudes y Respuestas
Mecanismo de Seguridad CORS
Importancia de CORS en APIs
Funcionamiento de CORS
Mecanismo de AntiForgery para CSRF
¿Cómo se Produce el Ataque?
¿Cómo Evitar este Tipo de Ataques?
GraphQL
Flexibilidad y Agilidad con GraphQL
¿Cuáles son las Ventajas de Utilizar GraphQL?
¿Cómo Funciona GraphQL?
Comparando GraphQL API vs. Rest API
Características para la Integración de Sistemas Existentes
Query
Ejemplo Sencillo para Query
Query y Mutation Operando Juntos
Creando el Proyecto
Creando la Clase Query
Creando la Clase Mutation
Resultados y Pruebas
El Protocolo RPC
El Protocolo gRPC
Arquitectura de gRPC
Los Búferes de gRPC
Implementación de gRPC
Creando un Servicio Cliente Servidor con gRPC
Backend – Lado del Servidor
Frontend – Lado del Cliente
Creando un Servicio Más Complejo con gRPC

Capítulo 6

Arquitectura en las Soluciones de .NET
Arquitectura Monolítica
Importancia de la Arquitectura Monolítica
Aclarando Conceptos Erróneos
Estructura Monolítica
Características del Enfoque Monolítico
Ventajas
Desventajas
Diseño de Proyectos en la Solución
Arquitectura de Microservicios
Introducción
Características Generales
Autonomía
Especialización
Beneficios Generales
Agilidad
Flexibilidad de Escalamiento
Facilidad en la Implementación
Libertad Tecnológica
Reutilización de Código
Robustez
Implementación de una Arquitectura de Microservicios
API Gateway
El Patrón API Gateway
¿Cómo Funciona API Gateway?
Arquitectura API Gateway
Características de API Gateway
API Gateway sobre una Arquitectura Microservicios
Integración de API Gateway y Kubernetes
Herramientas Más Populares de las API Gateway
Beneficios del uso de API Gateway
Enfoque del Diseño sobre API Gateway
Microservicios Básico
Acceso a las Rutas
El Código
Microservicios Contra Ataques DDoS
¿Cómo se Produce el Ataque?
¿Cómo Evitar el Ataque?
Total de Seguridades que Ofrece Ocelot
Autenticación y Autorización
Control de Acceso Basado en Roles (RBAC)
Rate Limiting y Throttling
Inspección y Filtrado de Solicitudes (Validación de Datos)
Cifrado de Datos en Tránsito (HTTPS)
Firewall de Aplicaciones Web (WAF)
Reglas de CORS (Cross-Origin Resource Sharing)
Token Refresh y Gestión de Sesiones
Registro y Monitoreo de Seguridad
Filtrado de IP y Geolocalización

Capítulo 7

Modelos de Datos
Modelo de Entidad Relación
Entidad
Atributos
Relación
Conjunto de Relaciones
Restricciones
Cardinalidades
Participación
Claves
Diseño de Base de Datos Mediante DER
Motores ORM
Componentes Principales de la Arquitectura ORM
Funcionamiento Interno de un ORM
Mapeo de Datos y Relaciones Complejas
Ventajas Técnicas de Usar un ORM
Desventajas Técnicas y Consideraciones de Rendimiento
ORM y Arquitecturas Modernas (Microservicios y CQRS)
Características Fundamentales
Mapeo de Objeto Relacional
Patrones ORM
Patrón Repository
Objetivos del Patrón Repository
Arquitectura y Componentes del Patrón Repository
Ejemplo de Uso
Patrón Active Record
Principales Características
Ejemplo de Uso
Entity Framework Core
Etapas Principales en Entity Framework Core
¿Cómo se Compone Entity Framework Core?
Enfoque para el Diseño
Especificación CSDL
Especificación SSDL
Especificación MSL
Acceso y Cambio de los Datos desde las Entidades
Optimización
Optimización Avanzada
Migrations
Automatización para las Migraciones
Modelos en Entity Framework Core
Definición
Configuraciones Avanzadas
Dapper o Micro ORM
Características Más Destacables
Características de Dapper
Ventajas de Usar Dapper
Analizando Algunos Ejemplo
Consulta Básica
Usando Parámetros en las Consultas Dapper
Bases de Datos No Relacionales – NoSQL
Almacenamiento Basado en clave-valor KV
Base de Datos MongoDB
Indexación
Replicación
Equilibrio de Carga
Almacenamiento de archivos
Agregación
Colecciones Limitadas
Ejemplo de Uso de MongoDB
Un Ejemplo para Dos Tablas Vinculados
Redis
Características de Redis
Redis vs. MongoDB
Analicemos un Ejemplo para Redis
Integración de Algunas Tecnologías con Redis
Arquitectura General de la Solución o Proyecto
Sector de Gestión de Almacenamiento
Sector de Gestión del Caché de Redis

Capítulo 8

Evaluación del Software
Fases de la Evaluación del Software
Criterios de Evaluación del Software
Herramientas Comunes para la Evaluación del Software
Metodologías Relacionadas
Pruebas Unitarias
Importancia del Unit Testing
Características de las Pruebas Unitarias
Creación de Evaluaciones Unit Test en .NET Core
¿Qué Beneficios Nos Proporciona Automatizar las Pruebas Unitarias?
Diseño de Pruebas
Aplicando Pruebas Básicas a un Proyecto
Aplicando Pruebas Sobre la Sección de la Aplicación

Capítulo 9

Inteligencia Artificial
Áreas de Aplicación de la IA en el Diseño de Software
Introducción a la IA
Algoritmos
Tipos de Algoritmos de la Inteligencia Artificial
Machine Learning
Algoritmos de Aprendizaje Por Refuerzo
Algoritmos de Aprendizaje Supervisado
Algoritmos de Aprendizaje No Supervisado
Algoritmos de Aprendizaje Profundo
Algoritmos de Procesamiento Natural NLP (Natural Language Processing)
Tareas Más Frecuentes de NLP
Redes Neuronales
Aprendizaje Profundo
Redes Neuronales y Peso
¿Para qué se Utiliza una Red Neuronal Profunda?
Aplicaciones Prácticas de IA
Caso de Clasificación de Texto
Código de Ejemplo
Caso de Regresión Usando FastTree
¿Qué es FastTree?
Explicación del Problema
Explicación del Código
Definición de Clases
Transformaciones y Modelo
Caso de Aprendizaje No Supervisado para un Clustering
¿Qué es el Clustering?
Detección de Fraude Financiero
¿Cómo es el Cálculo K-Means?
Caso de Clasificación para el Control de un Horno Industrial
Regresión Logística
Caso de Regresión Utilizado para el Cálculo de Huella Hídrica
Detallado Completo del Proyecto
Explicación Técnica de SDCA
Entrenamiento y Optimización de Modelos de ML

Capítulo 10

Máquinas Virtuales vs. Contenedores
Docker y Kubernetes
Introducción a Docker
Archivos y Configuraciones
Aplicación Sencilla de .NET Core Sobre Docker
Creación del Proyecto
Despliegue en Docker
Diferencia entre los archivos Dockerfile y docker-compose.yml
Despliegue Usando el Archivo docker-compose.yml junto a Dockerfile
Diferencias entre DevOps y CD-CI
DevOps
Fases de DevOps
Planificación (Plan)
Desarrollo (Code)
Construcción (Build)
Pruebas (Testing)
Liberación (Release)
Despliegue (Deployment)
Operación y Monitoreo (Operation & Monitoring)
Retroalimentación (Feedback)
CI-CD (Integración Continua – Despliegue Continuo)
Fases de CI-CD
Control de Versiones (Versionados)
Integración Continua – CI (Continuous Integration)
Construcción del Artefacto
Pruebas Continuas
Despliegue Continuo – CD (Continuous Deployment)
Monitoreo y Retroalimentación (Feedback)
Flujo General CI/CD para .NET Core
Organización para un Escenario Empresarial
Proceso de Implementación
Configuración del Repositorio de Código
Pipeline de CI (Integración Continua)
Pipeline de CD (Despliegue Continuo)
Monitoreo y Feedback
Flujo Práctico de Trabajo
Beneficios Obtenidos

------------