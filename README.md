<h1> 🧠 Optimización de la Operación Marítima mediante Análisis de Datos Logísticos </h1>

<h2>📊 Descripción General</h2>

En este proyecto se analizó la operación logística marítima de una empresa que administra barcos, contenedores y rutas portuarias.

<h2>❌ Situación problema</h2>

La empresa Transmar presentaba problemas de retrasos, mala distribución de contenedores y altos costos en ciertas rutas, afectando la satisfacción de los clientes lo que nos llevó a plantearnos 5 preguntas concretas
1. ¿Cuáles son las rutas más costosas y cuántas operaciones tienen?
2. ¿Qué barcos presentan más retrasos en sus operaciones?
3. ¿Qué tipo de contenedores generan más costos operativos?
4. ¿Qué puertos generan mayor tiempo de tránsito?
5. Qué barcos generan el mayor costo total en operaciones y cuántas operaciones realizan?
   
<h2>🛠 Herramientas por utilizar</h2>

Los datos están originalmente en CVS procederemos a crear una base de datos MySQL para almacenar, limpiar, transformar y analizar los datos dado que nos permite manejar grandes volúmenes de información sin perder rendimiento lo cual es esencial para una operación logística donde los datos crecen constantemente.

<h2>✅ Conclusiones</h2>
El análisis de la operación portuaria revela que los costos, tiempos de tránsito y desempeño operativo están fuertemente determinados por el tipo de carga, la ruta y la intensidad de uso de cada barco. Se evidencian patrones consistentes donde ciertos tipos de contenedores y rutas intercontinentales concentran los mayores costos y tiempos, mientras que algunos barcos destacan por un costo promedio elevado pese a realizar menos operaciones. En conjunto, los resultados permiten comprender cómo interactúan estos factores dentro del sistema logístico y muestran una estructura operativa marcada por diferencias significativas en eficiencia y demanda entre barcos, contenedores y rutas.

<h2>🗂️ Recomendaciones</h2>

1. **Cambiar el tipo de barco asignado en ciertas rutas criticas:** usar embarcaciones con mejor rendimiento de combustible o mayor capacidad TEU para bajar el costo por operación.
2. **Reducción de escalas en puertos caros:** eliminar o sustituir escalas intermedias que aumenten tarifas portuarias y tiempos de atraque.
3. **Programar mantenimiento preventivo prioritario para los barcos con mayor porcentaje de retrasos** (arriba de 40%). Esto ataca fallas mecánicas que suelen generar retrasos recurrentes.
4. **Revisar las rutas asignadas a estos barcos**: en muchos casos, retrasos altos vienen de operar en puertos congestionados o rutas largas que exceden la capacidad del barco.
5. Se recomienda **analizar las operaciones específicas asociadas a los Open Top** para identificar qué parte del proceso encarece
6. **Optimizar la asignación de barcos para estas rutas críticas**, utilizando embarcaciones con: **Mayor velocidad de crucero**, **Mejor eficiencia de combustible**, **Menor necesidad de mantenimiento durante el trayecto**.
7. Implementar una **auditoría de costos por operación** enfocada en estos barcos que destacan por costos promedio altos.
