<div class="row">
  <div class="column"><img src="https://github.com/analiticafp/Caracterizaci-n-grupos-de-valor-DAPF/blob/8df078b958299e29ebe2835f22e23ca835848781/imaganes/2022-08-30_Logo_fp.jpg" align="left" alt="Función Pública"></div>
  <div class="column" align="center"><div><b>Documentación proyecto analítica V.1</b><br>Ultima actualización: Agosto de 2022</div>
</div>

<br>
<h1 >Analisis de datos Gestor Normativo</h1>

<h2>Participantes</h2>
<ul>
 <li type="circle">Luz Stella Rojas, lrojas@funcionpublica.gov.co</li>
 <li type="circle">Maritza Ibarra Duarte, Analista de datos,  mibarra@funcionpublica.gov.co</li>
 <li type="circle">Miguel Sebastian Rincon Ortega, Analista de datos, mrincon@funcionpublica.gov.co</li>
 <li type="circle">Karol Camargo Vargas, Analista de datos, kcamargo@funcionpublica.gov.co</li>
</ul>

<h2>Tipo de analitica</h2>
<ul>
<li type="circle">Descriptiva</li>
</ul>
 
<h2>Problema</h2>
<p>El departamento administrativo de la Función Pública elabora anualmente el informe de caracterización de usuarios y grupos de valor con el objetivo de identificarlos caracterizarlos y enfocar los esfuerzos de la entidad para satisfacción de estos usuarios, Sin embargo, dicho informe no permite tener claridad de los servicios y productos atendidos en la entidad dado que no se incluyen todos los insumos de los canales, además las bases de datos no muestran la trazabilidad completa de las atenciones.</p>

<h2>Justificación</h2>
<p>A través del análisis de los reportes generados desde el Gestor Normativo, la Dirección Jurídica busca identificar acciones de mejora que permitan brindar un mejor servicio, facilitando el acceso a la consulta de documentos con temas de la Función Pública tales como normas, jurisprudencia, conceptos, códigos y estatutos, entre otros.</p>
  
 
 <h2>Marco de referencia</h2>
  
  <table>
  <tr>
    <th>Marco contextual</th>
  </tr>
  <tr>
<p>Función Pública es una entidad pública del orden nacional del nivel central, junto con la Escuela superior de administración pública -ESAP- compone el sector de función pública. A partir del decreto legislativo 2169 de 1992 recoge nuevas funciones entre las cuales se encuentran el manejo del empleo público, la capacitación de los servidores, la creación y las reformas a las plantas de personal de las entidades estatales. En la última década el Departamento asume el liderazgo del sector y se agregan nuevas funciones asociadas al direccionamiento de las políticas de relacionamiento con la ciudadanía, como la política de integridad, racionalización de tramites, participación ciudadana, servicio al ciudadano, además de la política de gestión del conocimiento y la innovación en el sector público<p>

En el desarrollo de sus funciones el Departamento ha construido una planeación estratégica donde se establece que la misión de la entidad es “Fortalecer la gestión de las Entidades Públicas Nacionales y Territoriales, mejorar el desempeño de los servidores públicos al servicio del Estado, contribuir al cumplimiento de los compromisos del gobierno con el ciudadano y aumentar la confianza en la administración pública y en sus servidores.” Para dar cumplimiento a dicha misión la entidad formuló tres (3) objetivos estratégicos: enaltecer al servidor público y su labor, consolidar una gestión pública moderna, eficiente, transparente, focalizada y participativa al servicio de los ciudadanos y consolidar a Función Pública como un Departamento eficiente, técnico e innovador.<p>

Desde los objetivos misionales se identifican (3) grupos de valor asociados al despliegue de los productos y servicios de la entidad, ellos son: los servidores públicos, las entidades públicas y la ciudadanía. El objetivo de este documento es presentar el proceso de caracterización de usuarios asociados a esos grupos de valor, para actualizar el portafolio de bienes y servicios de la entidad y mejorar el diseño de acciones de diálogo en el marco del proceso de rendición de cuentas<p>
 </td>
  
<div>
<h2>Objetivos</h2>
<p><b>Obetivos del Negocio</b><br>
Posicionar el Gestor Normativo como buscador especializado en temas de función pública, para alcanzar una cobertuta y usabilidad en todo el territorio nacional.  .<br>

<b>Objetivo de la Mineria de datos:</b><br>
 <ul>

 <li type="circle">Realizar analisis de visitas, que permitan identificar los temas más consultados e inherentes a la Función Pública.</li>
<li type="circle">Identificar los grupos de valor más recurrentes en consultas.</li>
<li type="circle">Asegurar la actualización de la documentación dispuesta en la herramienta para el uso de nuestros grupos de valor.</li>
    <ul>
</p>
</div>
   
<h2>Criterios de Éxito</h2>
   <p>Desde el punto de vista de negocio, se puede considerar como criterio de éxito lograr la caracterización del 100% de las atenciones realizadas por Función Pública a los diferentes usuarios.</p>

<div>  
<h2>Riesgos y contingencias</h2>
   <p>  
    <ul>
<li type="circle">Información Incompleta, falta de información de los usuarios que consultan.</li>
<li type="circle">Errores de diligenciamiento.</li>
<li type="circle">Campos no paremetrizados en los canales.</li>
    <ul>  
   </p>
</div>
  
<h2>Costos y beneficios</h2>
      <p>El desarrollo de este ejercicio de analítica de datos no genera costos para la entidad, dado que se realizará tomando como fuentes de información reportes generados por los diferentes canales de atención.<br>
      
Como beneficios se pueden mencionar que el desarrollo de estos ejercicios son un valor agregado para la entidad al contar con información confiable, de fácil acceso, con procedimientos y metodologías reconocidas y estandarizadas que respaldan las cifras. De otra parte, se puede decir que con los resultados obtenidos se pueden contar con una caracterización más detallada de los grupos de valor, así como identificar oportunidades de mejora aplicables a la forma como se capturan los datos en los canales de atención así como a los procedimientos para el diligenciamiento de los aplicativos destinados a tal fin, qiue permitan enfocar los esfuerzos de la entidad en la atención de estos grupos.</p>

 <div>
 <h2>Productos/Entregables</h2>
 <ul>
 <li type="circle">Análisis de comportamiento de usuarios del gestor normativo.</li>
  <ul>
 </div>
   
 <h2>Metodología y Alcance</h2>
   <p><b>Metodología:</b> Para el desarrollo de este ejercicio se utilizaran las metricas que genera la herramienta de google analytics, las cuales nos permiten conocer los usuarios, explorar su comportamiento, medir sus interacciones, entro otros aspectos.</li><br> 
 
<b>Alcance:</b>  Para este ejercicio se realizará análisis de los usuarios que visitaron el gestor normativo desde enero de 2022 a 31 de octubre de 2022.</p>

<h2>Recursos tecnológicos del proyecto</h2>
<table>
   <tr>
    <th colspan="3">Descripción de software</th>
  </tr>
  <tr>
    <th>Software</th>
    <th>Justificación</th>
    <th>Archivos generados</th>
  </tr>
  <tr>
    <td>Google Analytics</td>
    <td>Heramienta de google, cuyo objetivo es medir el impacto de un sitio web y el comportamiento de sus usuarios. con el fin de entender el rendimiento del sitio y cómo optimizarlo.</td>
    <td>Métricas personalizadas de acuerdo con el tipo de análisis a realizar</td>
  </tr>
</table>

 
 <h2>Presentación y análisis de resultados</h2>
   
<h3>Visitas</h3>

</p>Entre el periodo de enero a octubre de 2022, se evidencia un total de 15.182.491, lo que equivale a 1.518.149 visitas en promedio mensual, tal y como se observa en la gráfica </li><br>

<div>   
<img src=https://github.com/analiticafp/Analitica-de-datos-gestor-normativo/blob/main/Imagenes/2022-15-11_Visitas.png></li><br>

<h3>Páginas visitadas</h3>

</p>En cuanto a las páginas visitadas en total se evidencian 24.007.813, lo que equivale a que los usuarios en sus vistas en promedio visitan 2 páginas del sitio en cada visita, lo anterior coincide con el objetivo del gestor normativo, donde los usuarios ingresan y consultan una norma específica.</li><br>

</p>Así mismo para ese periodo de tiempo se evidencia que las páginas más consultadas corresponden a manual de estructura del Estado, de acuerdo con la siguiente gráfica.</li><br>

<div>   
<img src=https://github.com/analiticafp/Analitica-de-datos-gestor-normativo/blob/main/Imagenes/2022-15-11_Top_paginas.png></li><br>


<h3>Usuarios</h3>

</p>De acuerdo con los resultados de Google Analytics, estos 15 millones de visitas las han realizado un total de 4.073.065 de usuarios, donde se evidencia que el mayor canal de acceso es la búsqueda en Google, seguido de accesos directos, tal y como se muestra en la siguiente tabla</li><br>

<table>
   <tr>
    <th colspan="4">Usuarios</th>
  </tr>
  <tr>
    <th>Canal</th>
    <th>Participación</th>
    <th>Usuarios Nuevos</th>
      </tr>
  <tr>
    <td>Búsqueda orgánica</td>
    <td>91,21%</td>
    <td>90,4%</td>
  </tr>
    <td>Directo</td>
    <td>7,18%</td>
    <td>6,79%</td>
  </tr>
    <td>Remsión</td>
    <td>1,51</td>
    <td>2,67%</td>
    </tr>
    <td>Red Social</td>
    <td>0,10%</td>
    <td>0,12%</td>
    </tr>
    <td><h3>Total</td></h3>
    <td><h3>79,57%</td></h3>
    <td><h3>88,65%</td></h3>
</table>

</p>Así mismo se puede observar que el 79,5% de los usuarios que visitan el gestor normativo son usuarios nuevos (Usuarios que ingresan por primera vez al sitio que corresponden al número de cookies nuevas que encuentra y contabiliza el sistema), mientras que el 88,6% corresponde a usuarios recurrentes</li><br>

<h3>Tiempo de permanencia en el sitio</h3>

<h3>Porcentaje de Rebote</h3>

<h3>usuarios Nuevos</h3>

<h3>Georreferenciación</h3>

   
<h2>Conclusiones</h2>
<p> Una vez analizadas las bases de datos de los reportes generados por los canales de atención, durante el 2021 y de enero a julio de 2022, se puede concluir que:</p><br> 
   
<li type="circle">Bogotá cuenta con el porcentaje de interacciones más altos con nuestra entidad </li>
 <br>  
 
<li type="circle">El Canal de atención que más registra interacciones es el de cursos eva donde la participación más alta es de curso de integridad, seguido del canal escrito </li><br>
  
<li type="circle">El mayor porcetanje de interacciones la realizan servidores públicos o contratistas</li><br>

<li type="circle">El árbol de temas es muy amplio y no facilita la asociación con el portafolio de servicios de la entidad </li><br>


</ul>
 <h2>Recomendaciones</h2>
 <p>Desde la Oficina Asesora de Planeación y el equipo de trabajo que desarrollo este ejercicio se sugiere lo siguiente:</p>
  
<li type="circle">Tipificar de manera obligatoria para todos los canales de atención el número de cédula, la pertenencia a un grupo de interés, grupo étnico y discapacidad.</li><br> 
  
<li type="circle">Estandarizar los grupos de interés, pertenencia étnica y discapacidad en los canales de atención.</li><br> 
  
<li type="circle">Estandarizar y alinear al portafolio de servicios los temas en los canales</li><br> 
  
<li type="circle">Establecer hasta que nivel se puede hacer desagregación de temas y subtemas, así como su estandarización en todos los canales.</li><br> 

<li type="circle">Interoperar el módulo de entidades con los canales, para que solo sea seleccionar la entidad y no permitir que se pueda escribir cualquier dato.</li><br>

<li type="circle">Crear una columna de tipo de identificación que facilite la validación del grupo de valor (Ejm: sigep; Cédula, nit, etc), lo anterior debido a que en la columna de nombre del usuario para algunos canales se encuentran nombres de entidades, números de cédula, nombre de personas, correos, etc, lo que dificulta la identificación del tipo de usuario.</li><br>

<li type="circle">Potencializar el CRM como herramienta para consolidar y analizar todas las interacciones con los grupos de valor y que permita contar una trazabilidad de las atenciones históricas.</li><br>

<li type="circle">Crear reportes que permitan hacer seguimiento y monitoreo a todas la interacciones, con el fin de identificar los grupos de valor y mejorar nuestra oferta institucional enfocada a la satisfacción de necesidades de dichos grupos.</li><br>

<li type="circle">Incluir la DIVIPOLA del DANE en los canales de atención que facilite la georreferenciación de los usuarios.</li><br>
