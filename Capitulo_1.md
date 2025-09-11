## Capítulo I: Introducción
### 1.1. Startup Profile
### 1.1.1. Descripción de la Startup
### 1.1.2. Perfiles de integrantes del equipo
### 1.2. Solution Profile
### 1.2.1 Antecedentes y problemática
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
