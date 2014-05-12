<p style="text-align: justify;">El UML es llamado lenguaje de modelo desde los años 80’s y principios de los 90’s, donde se había establecido que es un modelo y no un método como la mayoría de las personas pretendían comprenderlo de esa forma. Por lo cual se explicó que los métodos son los que consisten de ambos, de un lenguaje de modelado y de un proceso.</p>
<!--more-->

<em>Tabla de contenido:</em>
<ol>
	<li>Que es UML.</li>
	<li>Herramientas de Modelado.</li>
	<li>Conclusión.</li>
	<li>Referencias.</li>
</ol>
<em>1. Que es UML.</em>
<p style="text-align: justify;">El lenguaje unificado de modelo es el que nos ayuda a obtener una mejor visualización de lo que puede tratar un sistema. No necesariamente debemos situarnos en los sistemas de información, ya que este tipo de lenguaje nos permite absorberlos todos y mostrarlos por medio de diagramas y gráficos, toda la información pertinente de su uso o simplemente de sus funcionalidades.</p>
<p style="text-align: justify;">UML fusiona los conceptos de la POO (Programación Orientada a Objetos) aportados por metodología como lo es la de Booch, Aportando todo este tipo de información hace que UML crezca en cuanto a métodos de análisis y diseño con Orientación a Objetos.</p>
<p style="text-align: justify;">Un punto fundamental sobre el lenguaje unificado de modelado es la estandarización, ya que esta es invaluable en todos sus sentidos, debido a que es la parte principal del proceso de comunicación que requieren los agentes que están involucrados dentro del proyecto.</p>
<p style="text-align: justify;">Una de las principales metas del lenguaje unificado de modelado es poder obtener el mejor rendimiento posible en cuanto a concepto visual por medio de gráficos, por lo cual a UML se le definió una semántica y una notación.</p>
<em>2. Herramientas de Modelado</em>
<p style="text-align: justify;">El Lenguaje tiene múltiples herramientas para lograr una especificación adecuada del modelo. De las cuales hablaremos de:</p>

<ul style="text-align: justify;">
	<li>Modelamiento de Clases</li>
	<li>Casos de Uso (Use Case)</li>
	<li>Diagrama de Interacción</li>
</ul>
<p style="text-align: justify;"><span style="text-decoration: underline;"><em><strong>Modelamiento de Clases:</strong></em></span></p>
<p style="text-align: justify;">En el Modelamiento de clases nos permitimos identificar que la funcionalidad está en visualizar las relaciones entre clases que estén conjuntas con el sistema, de las cuales estas pueden ser asociativas, de herencia, de uso y de contenimiento.</p>
<p style="text-align: justify;">Un diagrama de clases o modelo de clases está compuesto por unos elementos fundamentales que son:</p>

<ul style="text-align: justify;">
	<li type="disc">Clase: Atributos, Métodos y Visibilidad.</li>
	<li type="disc">Relaciones: Herencia, Composición, Agregación, Asociación y Uso.</li>
</ul>
<p style="text-align: justify;"><em>Clase:</em> Es la unidad básica que junta toda información que adquiere un objeto. Lo cual definidos también que el objeto es una instancia de una clase. Por medio de ella podemos modelar o referenciar un estudio específico como una casa, una cuenta corriente, entre otros.</p>
<p style="text-align: justify;">En UML, una clase se representa así:</p>
<a href="http://www.soyinformatico.org/portal/wp-content/uploads/2014/01/Fig1.jpg"><img class="alignnone size-full wp-image-244" src="http://www.soyinformatico.org/portal/wp-content/uploads/2014/01/Fig1.jpg" alt="UML de una Clase" width="115" height="112" /></a>

Representación en UML de una clase
<blockquote>
<p style="text-align: justify;">En la representación anterior observamos que en el cuadro superior será ubicado el nombre de la clase, en el cuadro intermedio irán todos los atributos o características que tenga dicha clase a estudiar (variables con visibilidad pública, privada o protegida) y en el último cuadro contienen todos los métodos u operaciones que hacen que el objeto interactúe de forma directa con su entorno.</p>
</blockquote>
<p style="text-align: justify;"><strong>Atributo:</strong> Son características específicas que tiene una clase, los cuales definen el grado de comunicación y visibilidad que tienen con su entorno. Se definen en tres tipos de visibilidad:</p>

<ul style="text-align: justify;">
	<li type="square">Public (+) : Indica que el atributo o característica será visible en toda la clase, lo cual indica que será de forma fácil de acceder.</li>
	<li type="square">Private (-) : Indica que los atributos o características podrán ser utilizadas desde dentro de la clase.</li>
	<li type="square">Protected (#) : Indica que los atributos o características podrá accederse por medio de métodos desde fuera de la clase.</li>
</ul>
<p style="text-align: justify;"><strong>Métodos:</strong> Es la forma en donde una clase se le permite interactuar por medio de estos con su ambiente o entorno; también manejan la misma visibilidad de los atributos pero con funcionalidad diferente:</p>

<ul style="text-align: justify;">
	<li type="square">Public (+) : Permite identificar el método como libre visibilidad desde cualquier clase manejada. Es accesible desde todas las clases.</li>
	<li type="square">Private (-) : Permite identificar al método solamente desde dentro de la clase utilizada. (teniendo en cuenta que también se pueden acceder desde otros métodos).</li>
	<li type="square">Protected (#) : Indica que el método no podrá tener un acceso desde afuera de la clase pero si se podrá acceder por los métodos de la clase.</li>
</ul>
<p style="text-align: justify;"><em>Relaciones entre Clases:</em> Teniendo en cuenta las definiciones antes vistas sobre clase, métodos y atributos; podemos empezar a definir esas interrelaciones que tienen las clases, teniendo en cuenta que las clases no necesariamente deben de ser iguales para hallar una relación.
Debemos empezar a definir un concepto fundamental que es la cardinalidad, la cual nos permite hallar el grado y nivel de dependencia que tiene una clase de otra y se denotan anotándose en cada extremo de la relación, de las cuales pueden ser:</p>

<ul style="text-align: justify;">
	<li type="square">Uno a muchos: 1…*(1…n).</li>
	<li type="square">0 a muchos: 0…*(0…n).</li>
	<li type="square">Número fijo: m (m denota el numero).</li>
</ul>
<ol style="text-align: justify;">
	<li value="1"><strong>Herencia (Especialización/Generalización)</strong> <a href="http://www.soyinformatico.org/portal/wp-content/uploads/2014/01/Herencia.jpg"><img class="alignnone size-full wp-image-255" src="http://www.soyinformatico.org/portal/wp-content/uploads/2014/01/Herencia.jpg" alt="Simb_Herencia" width="59" height="21" /></a> : La definición por medio de una observación es que a partir de una o más subclases siempre tendrán atributos o características y métodos que vienen de una super clase, donde claro debe estar que cada sub clase tendrá sus propios métodos y atributos.</li>
</ol>
<p style="text-align: justify;">Como ejemplo tendremos la siguiente cita:</p>

<blockquote><a href="http://www.soyinformatico.org/portal/wp-content/uploads/2014/01/Fig2.jpg"><img class="alignnone size-medium wp-image-251" src="http://www.soyinformatico.org/portal/wp-content/uploads/2014/01/Fig2-300x282.jpg" alt="Herencia" width="300" height="282" /></a>
<p style="text-align: justify;">Se especifica que Auto y Camión heredan de Vehículo, es decir, Auto posee las Características de Vehículo (Precio, VelMax, etc.) además posee algo particular que es Descapotable, en cambio Camión también hereda las características de Vehículo (Precio, VelMax, etc.) pero posee como particularidad propia Acoplado, Tara y Carga</p>
</blockquote>
<ol style="text-align: justify;">
	<li value="2"><strong> Agregación</strong> <a href="http://www.soyinformatico.org/portal/wp-content/uploads/2014/01/Agregacion.jpg"><img class="alignnone size-full wp-image-257" src="http://www.soyinformatico.org/portal/wp-content/uploads/2014/01/Agregacion.jpg" alt="Agregacion" width="82" height="26" /></a> : Para realizar relaciones de modelos de objetos complejos, ya no nos bastaran los datos comunes que siempre tenemos en cuenta que son dados por los lenguajes como enteros (int), reales (double) o cadena de caracteres (String). Cuando se necesite realizar este tipo de acciones con objetos instanciados se necesitan dos elementos:</li>
</ol>
<ul style="text-align: justify;">
	<li type="circle">Por Valor: Es la relación donde se debe tener en cuenta el tiempo de vida del objeto que se está manipulando e incluyendo dentro de la clase además del tiempo de vida del que lo incluye. A este tipo de relación se le denomina Composición.</li>
	<li type="circle">Por referencia: Es lo contrario a relación por valor ya que debemos de tener en cuenta solamente el tiempo de vida del objeto que se está incluyendo mas no el del que lo incluye. A este tipo de relación se le denomina Agregación.</li>
</ul>
<p style="text-align: justify;">Como ejemplo tendremos la siguiente cita:</p>

<blockquote>
<p style="text-align: justify;"><a href="http://www.soyinformatico.org/portal/wp-content/uploads/2014/01/Agregacion1.jpg"><img class="alignnone size-medium wp-image-261" src="http://www.soyinformatico.org/portal/wp-content/uploads/2014/01/Agregacion1-300x126.jpg" alt="Agregacion1" width="300" height="126" /></a></p>
<p style="text-align: justify;">En donde se destaca que:</p>

<ul style="text-align: justify;">
	<li>Un Almacén posee Clientes y Cuentas (los rombos van en el objeto que posee las referencias).</li>
	<li>Cuando se destruye el Objeto Almacén también son destruidos los objetos Cuenta asociados, en cambio no son afectados los objetos Cliente asociados.</li>
	<li>La composición (por Valor) se destaca por un rombo relleno.</li>
	<li>La agregación (por Referencia) se destaca por un rombo transparente.</li>
</ul>
<p style="text-align: justify;">La flecha en este tipo de relación indica la navegabilidad del objeto referenciado. Cuando no existe este tipo de particularidad la flecha se elimina.</p>
</blockquote>
<ol style="text-align: justify;">
	<li value="3"><strong>Asociación</strong> <a href="http://www.soyinformatico.org/portal/wp-content/uploads/2014/01/Asociacion.jpg"><img class="alignnone size-full wp-image-264" src="http://www.soyinformatico.org/portal/wp-content/uploads/2014/01/Asociacion.jpg" alt="Asociacion" width="82" height="26" /></a> : Este tipo de relaciones nos permite identificar cuando dos clases interactúan entre sí pero que no dependen entre ellas.</li>
</ol>
<p style="text-align: justify;">Como ejemplo citaremos lo siguiente:</p>

<blockquote>
<p style="text-align: justify;"><a href="http://www.soyinformatico.org/portal/wp-content/uploads/2014/01/Asociacion1.jpg"><img class="alignnone size-medium wp-image-265" src="http://www.soyinformatico.org/portal/wp-content/uploads/2014/01/Asociacion1-300x68.jpg" alt="Asociacion1" width="300" height="68" /></a>
Un cliente puede tener asociadas muchas Órdenes de Compra, en cambio una orden de compra solo puede tener asociado un cliente.</p>
</blockquote>
<ol style="text-align: justify;">
	<li value="4"><strong>Dependencia o Instanciación (uso)</strong> <a href="http://www.soyinformatico.org/portal/wp-content/uploads/2014/01/Dependencia.jpg"><img class="alignnone size-full wp-image-266" src="http://www.soyinformatico.org/portal/wp-content/uploads/2014/01/Dependencia.jpg" alt="Dependencia" width="84" height="21" /></a> : Esta relación nos permite identificar cuando una clase depende de otra teniendo en cuenta el tipo de métodos y atributos que posea esa dependencia y es mostrada en el diagrama por medio de una flecha punteada.</li>
</ol>
<p style="text-align: justify;">Como ejemplo citaremos lo siguiente:</p>

<blockquote>
<p style="text-align: justify;"><a href="http://www.soyinformatico.org/portal/wp-content/uploads/2014/01/Dependencia1.jpg"><img class="alignnone size-full wp-image-267" src="http://www.soyinformatico.org/portal/wp-content/uploads/2014/01/Dependencia1.jpg" alt="Dependencia1" width="282" height="61" /></a>
Se puede observar una aplicación grafica que instancia una ventana (la creación del Objeto Ventana está condicionado a la instanciación proveniente desde el objeto Aplicación).</p>
</blockquote>
<p style="text-align: justify;"><span style="text-decoration: underline;"><em><strong>Caso de Uso (Use Case):</strong></em></span>
Nos permite representar en el como un usuario (Autor) opera con el programa en desarrollo, además de cómo están interactuando los elementos principales de una clase por medio de su forma, tipo y orden.</p>
<p style="text-align: justify;">En este tipo de herramienta de especificación influyen unos elementos muy importantes que son:</p>

<ul style="text-align: justify;">
	<li>Actor</li>
	<li>Casos de Uso</li>
	<li>Relaciones de Uso, Herencia y Comunicación.</li>
</ul>
<p style="text-align: justify;"><strong>Actor</strong> <a href="http://www.soyinformatico.org/portal/wp-content/uploads/2014/01/Actor.jpg"><img class="alignnone size-full wp-image-268" src="http://www.soyinformatico.org/portal/wp-content/uploads/2014/01/Actor.jpg" alt="Actor" width="50" height="33" /></a> : Un actor es el usuario el cual está manipulando el sistema y permitiendo ver como interactúan el programa en desarrollo, cabe destacar que el rol de este usuario es muy importante ya que no es cualquier tipo de persona sino alguien más directo en contacto con el sistema.</p>
<p style="text-align: justify;"><strong>Casos de Uso</strong> <a href="http://www.soyinformatico.org/portal/wp-content/uploads/2014/01/Casos-de-uso.jpg"><img class="alignnone size-full wp-image-269" src="http://www.soyinformatico.org/portal/wp-content/uploads/2014/01/Casos-de-uso.jpg" alt="Casos de uso" width="50" height="30" /></a> : Son las operaciones específicas que se realizan mediante una acción ejecutada por un actor externo (usuario) o desde otro caso de uso.</p>
<p style="text-align: justify;"><strong>Relaciones:</strong></p>

<ul style="text-align: justify;">
	<li><strong>Asociación</strong> <a href="http://www.soyinformatico.org/portal/wp-content/uploads/2014/01/Asociacion.jpg"><img class="alignnone size-full wp-image-264" src="http://www.soyinformatico.org/portal/wp-content/uploads/2014/01/Asociacion.jpg" alt="Asociacion" width="82" height="26" /></a> : Es el tipo de relación que indica que tipo de casos de uso están interactuando por medio de operaciones.</li>
	<li><strong>Dependencia o Instanciación</strong> <a href="http://www.soyinformatico.org/portal/wp-content/uploads/2014/01/Dependencia.jpg"><img class="alignnone size-full wp-image-266" src="http://www.soyinformatico.org/portal/wp-content/uploads/2014/01/Dependencia.jpg" alt="Dependencia" width="84" height="21" /></a> : Es el tipo de relación que indica cuando una clase depende de otra o se está instanciando.</li>
	<li><strong>Generalización</strong> <a href="http://www.soyinformatico.org/portal/wp-content/uploads/2014/01/Herencia.jpg"><img class="alignnone size-full wp-image-255" src="http://www.soyinformatico.org/portal/wp-content/uploads/2014/01/Herencia.jpg" alt="Simb_Herencia" width="59" height="21" /></a> : Relación utilizada frecuentemente que tiene dos tipos de funciones que son de Uso y la otra es de Herencia.</li>
</ul>
<p style="text-align: justify;">Se cita el siguiente ejemplo para poder entender mejor la herramienta “Caso de Uso”:</p>

<blockquote>
<p style="text-align: justify;">Sistema que controla una máquina de reciclamiento de botellas, tarros y jabas. El sistema debe controlar y/o aceptar:</p>

<ul style="text-align: justify;">
	<li type="circle">Registrar el número de ítems ingresados.</li>
	<li type="circle">Imprimir un recibo cuando el usuario lo solicita:A. Describe lo depositado
B. El valor de cada ítem
C. Total</li>
	<li type="circle">El usuario/cliente presiona el botón de comienzo</li>
	<li type="circle">Existe un operador que desea saber lo siguiente:A. Cuantos ítems han sido retornados en el día.
B. Al final de cada día el operador solicita un resumen de todo lo depositado en el día.</li>
	<li type="circle">El operador debe además poder cambiar:A. Información asociada a ítems.
B. Dar una alarma en el caso de que:I. Ítem se atora.
II. No hay más papel.</li>
</ul>
<p style="text-align: justify;">Como una primera aproximación identificamos a los actores que interactúan con el sistema:</p>
<a href="http://www.soyinformatico.org/portal/wp-content/uploads/2014/01/InteraccionClienteOperador.jpg"><img class="alignnone size-medium wp-image-318" src="http://www.soyinformatico.org/portal/wp-content/uploads/2014/01/InteraccionClienteOperador-300x83.jpg" alt="InteraccionClienteOperador" width="300" height="83" /></a>

Interacción entre Cliente y Operador en Un Sistema definido.
<p style="text-align: justify;">Luego, tenemos que un Cliente puede Depositar Ítems y un Operador puede cambiar la información de un Ítem o bien puede Imprimir un informe:</p>
<a href="http://www.soyinformatico.org/portal/wp-content/uploads/2014/01/RelacionesUsoentreClases.jpg"><img class="alignnone size-medium wp-image-321" src="http://www.soyinformatico.org/portal/wp-content/uploads/2014/01/RelacionesUsoentreClases-300x79.jpg" alt="RelacionesUsoentreClases" width="300" height="79" /></a>
<p style="text-align: justify;">Además podemos notar que un ítem puede ser una Botella, un Tarro o una Jaba.</p>
<a href="http://www.soyinformatico.org/portal/wp-content/uploads/2014/01/Diagrama3ItemsDiferentes.jpg"><img class="alignnone size-medium wp-image-323" src="http://www.soyinformatico.org/portal/wp-content/uploads/2014/01/Diagrama3ItemsDiferentes-300x166.jpg" alt="Diagrama3ItemsDiferentes" width="300" height="166" /></a>
<p style="text-align: justify;">Otro aspecto es la impresión de comprobantes, que puede ser realizada después de depositar algún ítem por un cliente o bien puede ser realizada a petición de un operador.</p>
<a href="http://www.soyinformatico.org/portal/wp-content/uploads/2014/01/RelacionUsoentreObjetos.jpg"><img class="alignnone size-medium wp-image-324" src="http://www.soyinformatico.org/portal/wp-content/uploads/2014/01/RelacionUsoentreObjetos-300x236.jpg" alt="RelacionUsoentreObjetos" width="300" height="236" /></a>
<p style="text-align: justify;">Entonces, el diseño completo del diagrama Use Case es:</p>
<a href="http://www.soyinformatico.org/portal/wp-content/uploads/2014/01/DiagramaCasoUso.jpg"><img class="alignnone size-medium wp-image-325" src="http://www.soyinformatico.org/portal/wp-content/uploads/2014/01/DiagramaCasoUso-300x189.jpg" alt="DiagramaCasoUso" width="300" height="189" /></a></blockquote>
<p style="text-align: justify;"><span style="text-decoration: underline;"><em><strong>Diagrama de Interacción:</strong></em></span></p>
<p style="text-align: justify;">Este tipo de diagrama nos permite la comunicación directa entre un actor (usuario) y una clase en este tipo de diagrama son llamados objetos; comunicados a partir de una petición, evento o acción ejecutada. Con esto implica que realice un recorrido claro y conciso en todas las llamadas efectuadas donde se están obteniendo las responsabilidades.</p>
<p style="text-align: justify;">Este diagrama puede ser adquirido por medio de dos partes que sería el Diagrama estático de clases o el de Casos de uso.</p>
<p style="text-align: justify;">Los componentes que debemos de tener en cuenta en el Diagrama de Interacción son:</p>

<ul style="text-align: justify;">
	<li>Un Objeto o Actor</li>
	<li>Mensaje de un Objeto a otro Objeto</li>
	<li>Mensaje de un objeto a sí mismo</li>
</ul>
<p style="text-align: justify;"><strong>Un Objeto o Actor <a href="http://www.soyinformatico.org/portal/wp-content/uploads/2014/01/objeto-actor.jpg"><img class="alignnone size-full wp-image-332" src="http://www.soyinformatico.org/portal/wp-content/uploads/2014/01/objeto-actor.jpg" alt="objeto-actor" width="70" height="53" /></a> :</strong> El rectángulo representa un objeto instanciado y las líneas punteadas nos permite identificar la comunicación o llamadas que tienen los métodos del objeto.</p>
<p style="text-align: justify;"><strong>Mensaje a Otro Objeto <a href="http://www.soyinformatico.org/portal/wp-content/uploads/2014/01/mensajeAotroObjeto.jpg"><img class="alignnone size-full wp-image-329" src="http://www.soyinformatico.org/portal/wp-content/uploads/2014/01/mensajeAotroObjeto.jpg" alt="mensajeAotroObjeto" width="70" height="53" /></a> :</strong> Se representa por medio de una flecha de un objeto a otro, teniendo en cuenta que esta flecha es la comunicación de los métodos de un objeto en particular.</p>
<p style="text-align: justify;"><strong>Mensaje al mismo objeto <a href="http://www.soyinformatico.org/portal/wp-content/uploads/2014/01/MensajeMismoObjeto.jpg"><img class="alignnone size-full wp-image-330" src="http://www.soyinformatico.org/portal/wp-content/uploads/2014/01/MensajeMismoObjeto.jpg" alt="MensajeMismoObjeto" width="70" height="53" /></a> :</strong> A parte de utilizar llamadas desde un objeto desde afuera también se puede realizar llamadas desde el mismo objeto por medio de sus métodos.</p>
<p style="text-align: justify;">Se cita el siguiente ejemplo:</p>

<blockquote>
<p style="text-align: justify;">Tenemos el diagrama de interacción proveniente del siguiente modelo estático:</p>
<a href="http://www.soyinformatico.org/portal/wp-content/uploads/2014/01/ModeloEstatico.jpg"><img class="alignnone size-medium wp-image-331" src="http://www.soyinformatico.org/portal/wp-content/uploads/2014/01/ModeloEstatico-300x79.jpg" alt="ModeloEstatico" width="300" height="79" /></a>
<p style="text-align: justify;">Aquí se representa una aplicación que posee una Ventana gráfica, y ésta a su vez posee internamente un botón.</p>
<p style="text-align: justify;">Entonces el diagrama de interacción para dicho modelo es:</p>
<a href="http://www.soyinformatico.org/portal/wp-content/uploads/2014/01/DiagramaInteraccion.jpg"><img class="alignnone size-medium wp-image-328" src="http://www.soyinformatico.org/portal/wp-content/uploads/2014/01/DiagramaInteraccion-300x245.jpg" alt="DiagramaInteraccion" width="300" height="245" /></a>
<p style="text-align: justify;">En donde se hacen notar las sucesivas llamadas a Draw () (entre objetos) y la llamada a Paint () por el objeto Botón.</p>
<em>3. Conclusión.</em>
<p style="text-align: justify;">Podemos concluir que a partir de un análisis exhaustivo en cuanto a la estructura del programa a implementar, podremos identificar la cantidad de dependencias, relaciones y comunicaciones que tienen las clases a manipular con el UML, teniendo en cuenta que si no se tienen claros los conceptos de clase, atributo y método no se podrá tener un buen resultado en cuanto al análisis del problema.</p>
<p style="text-align: justify;">Cabe aclarar que a partir del análisis que se realiza al planteamiento previamente realizado, obtendremos los elementos suficientes para utilizar el UML y así identificar qué tipo de dependencias existen sobre cada clase y con esto lograr una guía adecuada para poder realizar el desarrollo adecuado y optimo de una aplicación.</p>
<em>4. Referencias.</em>
<ul>
	<li style="text-align: justify;">Diana Palliotto; Gabriel Romano Universidad Nacional de Santiago del Estero – Facultad de Ciencias Exactas y Tecnologías Dirección: Departamento de Informática - Av. Belgrano (S) 1912, (4200) Santiago del Estero, Argentina. http://www.dcc.uchile.cl/~psalinas/uml/introduccion.html</li>
	<li style="text-align: justify;">http://webbress.com.ar/site/materiales/proyecto/diagramas_del_uml.pdf</li>
	<li style="text-align: justify;">http://webbress.com.ar/site/materiales/proyecto/diagramas_del_uml.pdf</li>
</ul>
&nbsp;
<blockquote>No olvides dejar tus sugerencias, aportes e inquietudes en el gestor de comentarios.</blockquote>
</blockquote>
