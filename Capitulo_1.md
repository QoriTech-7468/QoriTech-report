## Capítulo I: Introducción
### 1.1. Startup Profile
### 1.1.1. Descripción de la Startup
### 1.1.2. Perfiles de integrantes del equipo
### 1.2. Solution Profile
### 1.2.1 Antecedentes y problemática
La técnica de las 5W analiza una situación mediante preguntas básicas que, al combinarse, generan una visión completa de un evento, interés o contexto.  
Por su parte, las 2H complementan las 5W al cuestionar los métodos y la cuantificación de eventos relacionados con el proyecto.

**5W**

**What (Qué)**

¿Qué problema enfrentan las empresas de transporte actualmente?

Las empresas de transporte enfrentan problemas como retrasos frecuentes por tráfico intenso, demoras en la preparación de la mercancía y situaciones con clientes no preparados (por ejemplo, locales cerrados o falta de pago al momento de la entrega), lo que obliga a reportes manuales vía WhatsApp y genera ineficiencias en la comunicación y el monitoreo.

**When (Cuándo)**

¿Cuándo evidencia mas problemas el proceso de transporte?

Los problemas se evidencian principalmente durante la fase de entrega y en ruta, como cuando ocurren retrasos por tráfico, pérdidas de productos, errores en la entrega o al momento de confirmar la entrega. También surgen incidencias comunes al reportar eventos como locales cerrados o clientes sin fondos, típicamente en horarios pico de tráfico o cuando los transportistas deben improvisar rutas no conocidas, lo que agrava las demoras en periodos de alta demanda o congestión vial

**Where (Dónde)**

¿Dónde ocurre el problema?

Los problemas ocurren principalmente en las rutas de transporte, en los puntos de entrega a clientes y dentro de los vehículos durante el viaje, donde factores como el tráfico o la falta de señalización en calles pueden causar confusión con en punto de entrega.

**Who (Quién)**

¿Quiénes son los involucrados?

Los involucrados principales son el personal de Administración, responsable de la planificación de rutas, registro de cargas y monitoreo general, y los Transportistas como choferes y auxiliares, quienes ejecutan las entregas, reportan incidencias y manejan herramientas digitales en el terreno. Además, afectan indirectamente a clientes/dueños de la carga por la falta de trazabilidad.

**Why (Porqué)**
¿Por qué se implementa este sistema?

Se implementa este sistema para optimizar la planificación, mejorar la trazabilidad de los envíos, reducir riesgos de pérdida y aumentar la eficiencia y confianza en el servicio.Esto agrega valor a las empresas al ofrecer alertas inmediatas y datos confiables, beneficiando a Administración en la planificación y a Transportistas en la resolución de problemas en ruta, fomentando mayor transparencia y competitividad.


**2H**

How (Cómo)
¿Cómo se puede dar solución al problema identificado?

La solución se puede lograr mediante la implementación de una plataforma digital con módulos específicos: Control de Ingreso para validar documentos digitalmente, Rutas para asignar y monitorear trayectos en tiempo real, Despacho para registrar cargas y confirmaciones, e integración IoT para sensores que envíen alertas sobre condiciones de la carga y desviaciones. Para Administración, esto optimiza la planificación y reduce confusiones; para Transportistas, facilita la localización con GPS y reportes automáticos, minimizando la dependencia de WhatsApp o conexiones inestables.

**How much(Cuánto)**

¿Cuánto afecta este problema? 

Según *Flock Freight (2023)*:

- **Pérdidas económicas**: cada empresa de alimentos y bebidas pierde más de **6 millones de dólares al año** por daños y pérdidas en envíos.  
  En Perú, esto puede representar millones de soles anuales para agroexportadoras, supermercados y distribuidoras de productos perecibles.  

- **Desperdicio de alimentos**: el **46 % de los transportistas** ha descartado envíos completos por retrasos, lo que equivale a **2.4 millones de libras de alimento desperdiciado por año**.  
  En Perú, frutas, verduras y productos frescos suelen deteriorarse por demoras logísticas o falta de refrigeración adecuada.  

- **Impacto en ventas**: retrasos de transporte generan una caída de hasta **8 % en ventas**.  
  En el mercado peruano, esto significa pérdida de contratos de exportación y menor disponibilidad de productos en góndola.  

- **Costos adicionales**: el **77 % de los transportistas** atribuye aumentos de precios al costo del transporte.  
  En Perú, factores como combustible, peajes e ineficiencia de rutas encarecen los productos finales para los consumidores.  

**En síntesis**: el problema genera pérdidas económicas significativas, desperdicio de alimentos, retrasos en la cadena de suministro, insatisfacción de clientes y mayor carga administrativa.

### 1.2.2 Lean UX Process.
### 1.2.2.1. Lean UX Problem Statements.
 
En la actualidad, las empresas de transporte y distribución enfrentan dificultades para poder gestionar y enviar de manera
eficiente sus productos. La falta de soluciones que permitan monitorear en tiempo real los vehículos, el estado de los productos, generan constantes retrasos, ciertas pérdidas de información y errores en las entregas. Esta situación impacta directamente en el cliente, que exige cada vez mayor rapidez y confiabilidad en los procesos de distribución de sus productos.

Frente a esta situación, nuestra aplicación se presenta como una alternativa innovadora que integra el seguimiento de tiempo real de los camiones con un gps integrado sin errores con una gestión de productos que logrará optimizar los tiempos de las entregas. La plataforma esta pensada paralos administradores y transportistas para que puedan llevar un control detallado de los paquetes, los productos entregados, y los que faltan entregar. En resumen, nuestra herramienta busca garantizar eficiencia, confiabilidad y simplicidad a nuestros usuarios.

### 1.2.2.2. Lean UX Assumptions.

#### A. Business Assumptions  
1. Creemos que nuestros clientes necesitan **reducir costos operativos y errores en la distribución de productos** mediante una mejor visibilidad de sus rutas y camiones.  
2. Estas necesidades se resuelven con una **plataforma ligera** que unifique seguimiento GPS, gestión de pedidos y monitoreo de camiones.  
3. Nuestros primeros clientes serán **empresas medianas de transporte y distribución**, así como **proveedores que gestionan múltiples entregas diarias**.  
4. Valor #1 esperado: **visibilidad en tiempo real** de la ubicación de camiones, estado de productos y entregas.  
5. Beneficios adicionales: **optimización de rutas, reducción de tiempos de entrega, consolidación de pedidos duplicados, trazabilidad de entregas y mayor satisfacción del cliente final**.  
6. Adquisición: **referencias en el sector logístico, visitas comerciales a empresas de transporte y asociaciones con proveedores.**.  
7. Ingresos: **modelo de suscripción mensual escalonado** según el rol (administradores / transportistas).  
8. Competencia principal: **Beetrack, SimpliRoute, Driv.in**.  
9. Ventaja competitiva: **corrección de errores recurrentes en otras apps, interfaz más intuitiva y pricing accesible**.  
10. Mayor riesgo de producto: **baja adopción por resistencia tecnológica de transportistas**.  
11. Mitigación: **onboarding guiado, capacitación en campo, quick-wins como consolidación automática de pedidos y soporte en tiempo real**.  
12. Otros supuestos críticos: **conectividad estable en las rutas, disposición de transportistas a usar dispositivos móviles y correcta integración de datos entre empresa–camión–cliente**.  

#### B. User Assumptions  
- **¿Quién es el usuario?** Administradores y transportistas.  
- **¿Dónde encaja el producto?** En la **gestión diaria de operaciones**, desde la planificación de rutas hasta la confirmación de entregas, accesible vía desktop y móvil.  
- **Problema a resolver:** falta de visibilidad en rutas, duplicidad de pedidos, registros manuales y errores en entregas.  
- **Uso típico:** visualizar ubicación del camión en tiempo real, monitorear estado del vehículo, consolidar pedidos, registrar entregas, reportar incidencias.  
- **Características importantes:** GPS integrado, consolidación de pedidos duplicados, gestión de paquetes cargados/entregados, alertas en tiempo real, reportes de desempeño.  
- **Look & feel:** interfaz clara y responsiva; dashboard con mapa en vivo, indicadores visuales de entregas y alertas de incidencias.  

#### C. User Outcome & Benefit Assumptions  
- Rutas más eficientes y menos viajes innecesarios.  
- Entregas puntuales y reducción de costos operativos.  
- Consolidación de pedidos duplicados → **menos errores y mayor productividad**.  
- Clientes finales más satisfechos al recibir pedidos de forma ordenada y sin retrasos.  
- Administradores con **mejor control y decisiones basadas en datos en tiempo real**.  

#### D. Business Outcome Assumptions (métricas objetivo)  
- **Aumentar en un 25 % el DAU (Daily Active Users)** en los primeros 2 meses.  
- **Reducir en un 40 % los errores de entrega y viajes duplicados** en 6 meses.  
- **Optimizar rutas y disminuir tiempos de entrega en un 30 %**.  
- Alcanzar **300 camiones activos en la plataforma en el primer año (2025)**.  
- **Consolidar el 90 % de pedidos duplicados automáticamente**, reduciendo desplazamientos innecesarios.  

#### E. Feature Assumptions  
1. **GPS integrado en camiones** mejora la visibilidad y reduce retrasos.  
2. **Consolidación automática de pedidos duplicados** optimiza rutas y evita viajes innecesarios.  
3. **Dashboard de administradores + app para transportistas** facilita coordinación y control en tiempo real.  
4. **Alertas de pago** mejor gestión de los pagos de los pedidos.  
5. **Reportes automáticos de entregas y tiempos de ruta** mejoran la toma de decisiones estratégicas.
     
### 1.2.2.3. Lean UX Hypothesis Statements.
### 1.2.2.4. Lean UX Canvas.

<table align='center'>

<tr style="background-color: #e6e6fa">

<th style="width:15%;" >1. Problema del Negocio </th>

<th style="width:15%;">5. Soluciones  </th>

<th style="width:15%;">2. Resultados comerciales</th>

</tr>

<tr>

<td>
Actualmente los transportistas
</td>

<td>
-Sistema de monitoreo
</td>

<td>
-Reducir en un 30% el tiempo de 
</td>

</tr>

<tr style="background-color: #e6e6fa">
<th style="width:15%;"  >3. Usuarios </th>

<th style="background-color: white;  "> </th>

<th style="width:15%;">4. Resultados y beneficios del usuario</th>
</tr>

<tr>

<td>
-Transportistas: Transportistas de materiales o de insumos desde provincia a Lima, con edades de entre 20 a 50 años <br>
-Administradores: Administradores micro y pequeñas empresas, con edades de 25 a 60 años, que
</td>

<td>
</td>

<td>
-Resultado 1 <br>
-Resultado 2 <br>
-Resultado 3 <br>
-Resultado 4 <br>

</td>

</tr>

<tr style="background-color: #e6e6fa">

<th style="width:15%;" >6. Hipótesis </th>

<th style="width:15%; ">7. ¿Qué es lo más importante que necesitamos aprender primero?</th>

<th style="width:15%;">8. ¿Cuál es la menor cantidad de trabajo que necesitamos hacer para resolver las dudas y para hacer siguiente más importante?
</th>

</tr>
<tr>

<td>
hipotesis 1 <br>
hipotesis 2 <br>
hipotesis 3 <br>
hipotesis 4 <br>

</td>

<td>
Saber el proceso de <br>
Saber el proceso de <br>
Saber el proceso de <br>


</td>

<td>
Entrevistas: Realizar entrevistas a nuestros posibles usuarios para que estos nos puedan contar sus experiencias. Con lo anterior, podriamos comprender sus necesidades, perspectiva y visión sobre el sistema de transportes y la administración<br>
<br>
Prototipos: Crear una versión preliminar y funcional de nuestra plataforma. Además, con este prototipo se realizarían pruebas y se recolectaría información para poder mejorar y corregir errores del mismo <br>

<br>
Pruebas: Estas se realizarian con los prototipos creados y serian a un grupo pequeño y seleccionado de nuestros usuarios que se ofrecieron a <br>

</td>

</tr>

</table>



### 1.3. Segmentos objetivo.
