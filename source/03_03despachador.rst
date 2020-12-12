#############
Despachador/a
#############


El Despachador es la persona responsable de la puesta en marcha, seguimiento y gestión, en general, de servicios de atención que contemplan el traslado de medicamentos, personal y/o equipos.

Como Despachador, tienes permisos de acceso a labores de gestión de tripulaciones, operaciones con traslados de afiliados, entregas de medicamentos y otros servicios ofrecidos por Atención-1 que involucren el traslado de medicamentos, personal y/o equipos. Estos servicios son de tipo: AMD, TLD, EMD, PHD y LAB. Recuerda que si quieres conocer los conceptos utilizados en la plataforma Atención-1, puedes revisar este :ref:`glosario` que hemos preparado.

Para poder ingresar a Atención-1 como Despachador, el personal encargado de la administración del sistema debe, previamente, crear el usuario y asignarle el rol de Despachador.

Para acceder a la plataforma, debes escribir en la barra de dirección del navegador: https://atencion1.venedigital.com. Una vez allí podrás visualizar en la barra inferior un conjunto de enlaces, a través de los cuales podrás obtener información acerca de Atención-1, tener acceso a un manual de ayuda, guía de Preguntas Frecuentes y video tutoriales, contactar al equipo de desarrollo vía correo electrónico y reportar fallos/sugerencias.

Para ingresar debes indicar el nombre de usuario y contraseña. Una vez dentro de la plataforma, como usuario Despachador, desde la parte superior derecha puedes tener acceso a los datos del perfil de usuario y cerrar la sesión. En la esquina superior izquierda se despliega el menú de "hamburguesa", desde el cual puedes navegar fácilmente a los paneles de **Atenciones**, **Tripulaciones** y **Afiliados**. En la parte central se encuentra el panel de atenciones, dividido en cuatro secciones:

#. Atenciones **En espera**: atenciones abiertas sin servicios o con al menos un servicio abierto o retrasado.
#. Atenciones **Próximas programadas**: atenciones abiertas con al menos un servicio programado dentro de las próximas 24 horas (incluye PHDs y servicios AMD/LAB/TLD/EMD programados).
#. Atenciones **En progreso**: atenciones abiertas con al menos un servicio que actualmente está siendo atendido.
#. Atenciones **Por cerrar**: atenciones abiertas que contienen al menos un servicio completado o cancelado (por cerrar).

.. image:: ../images/Despachador/PanelAtencionesGeneral.jpg

En la parte superior puedes observar una leyenda de colores que indica el estatus del servicio:

#. El color amarillo indica un servicio abierto.
#. El color verde es un servicio en proceso.
#. El color azul es un servicio completado.
#. El color gris oscuro indica un servicio cerrado.
#. El color gris claro indica un servicio cancelado.
#. El color rojo indica un servicio retrasado.

Cuando una atención **En espera** contiene al menos un servicio en retraso, presenta una alerta intermitente de color rojo con un signo de admiración, ubicada en la parte izquierda de la fila (al lado del número de la atención).

Si la cantidad de atenciones en cada panel es mayor a 10, debes navegar a través de los botones de paginación en la parte inferior del panel, para revisar si existe algún servicio pendiente por atender o ubicar alguna atención específica que no se encuentre en el primer listado.

Para crear un nuevo servicio asociado a una atención, haces clic sobre el botón de **Crear Nuevo Servicio**, ubicado en la parte derecha de la fila correspondiente.

Para visualizar los detalles de una atención en particular, haces clic sobre el botón de **Abrir**, ubicado en la parte derecha de la fila correspondiente. Al posicionar el cursor sobre el ícono aparecerá el mensaje **Atender** o **Revisar**, según la sección en que se encuentre. Serás redireccionado a la página de detalles de la atención seleccionada.

.. image:: ../images/Despachador/DetallesAtención.jpg

En esta página podrás visualizar dos secciones. La sección lateral izquierda contiene cinco paneles con los datos importantes de la atención: el panel de información general de la atención, el panel de datos relevantes del afiliado atendido, el panel de información general de las pólizas asociadas al afiliado, el panel del historial de atenciones del afiliado y el panel de documentos adjuntos solicitados para los procesos propios de cada servicio de la atención. La sección lateral derecha presenta la información referente a los servicios contenidos en la atención. Los servicios se muestran, con los acrónimos de sus nombres, en pestañas. Al hacer clic sobre cada pestaña se despliega la información del servicio, distribuida en paneles. Esta información varía según el tipo de servicio.

Todos los paneles (de atenciones y servicios) se expanden y se reducen al hacer clic sobre la cabecera del mismo (donde se encuentra el título).

********************************
Gestionar Atenciones y Servicios
********************************

En lo referente a la gestión de atenciones y servicios, como usuario Despachador tienes permisos para crear nuevas atenciones y servicios, visualizar todos los detalles de una atención y de un servicio e imprimir el ticket del servicio, las solicitudes (récipes y recomendaciones) y las notas de despacho.

En cuanto a los permisos de actualización, como Despachador puedes:

* Editar las observaciones y los números de contacto asociados a una atención, editar datos de un afiliado (nombre, apellido, fecha de nacimiento, género, teléfonos y correos electrónicos) y adjuntar archivos (resultados de laboratorio, indicaciones, récipes e informes médicos), en los paneles **Información de Atención**, **Afiliado** y **Documentos Adjuntos**, respectivamente, de la sección lateral izquierda correspondiente a detalles de una atención.
* Editar los comentarios y el motivo de servicio, en el panel **Información de Servicio**.
* Editar la tripulación y ruta en el panel **Tripulación y Ruta**.
* Editar los síntomas y diagnósticos en el panel **Diagnósticos**.
* Editar la nota de despacho, en el panel **Nota de Despacho**.
* Editar la información referente a las solicitudes en el panel **Solicitudes**.
* Adjuntar resultados de laboratorio, en el panel **Resultados**.
* Cancelar servicios, en el panel del flujo de trabajo.
* Completar cada paso del flujo de trabajo de un servicio y editar sus fechas y horas, en el panel del flujo de trabajo.

.. note::
    Es importante destacar que como Despachador, podrás actualizar y atender los servicios de tipo AMD, TLD, EMD, PHD y LAB. 
    Para un servicio OMT, solamente tienes acceso a la edición de los comentarios, en el panel **Información de Servicio**.


********************
Atender servicio AMD
********************

Al iniciar la atención de un servicio AMD, lo primero que debes hacer es asignar la tripulación y, en caso de que no haya sido asignada previamente, la dirección de destino. Para ello, te ubicas en el panel **Tripulación y Ruta**.

.. image:: ../images/Despachador/PanelTripulaciónYRuta.jpg

En el campo **Tripulación** aparecerá un listado de las tripulaciones activas para el día. Al seleccionar una de ellas, los demás campos automáticamente se llenarán y podrás visualizar información relevante acerca de la tripulación: nombre, base, unidad y conductor. Si en el campo **Tripulación** no se despliega un listado y aparece el mensaje "No hay datos disponibles", debes dirigirte al panel de **Tripulaciones** (a través del menú de "hamburguesa" en la parte superior izquierda) para crear al menos una tripulación que estará activa para el día en curso. Para más detalles acerca de la creación de una tripulación, puedes revisar la sección :ref:`gestionar_tripulaciones`.

Como Despachador, podrás asignar una nueva dirección de destino o editar la que fue asignada previamente. Al hacer clic sobre el campo **Destino**, aparecerá una ventana de diálogo para este fin. 

.. image:: ../images/Despachador/AsignarDirección.jpg

Si haces clic en el campo **Dirección**, se presentará un listado desde el cual podrás seleccionar una dirección personal del afiliado, de un servicio ejecutado previamente o de un proveedor de salud. Si no encuentras la dirección deseada en este listado, también tendrás la opción de asignar una nueva dirección completando los campos presentados en la parte inferior de la ventana: Dirección Línea 1, Referencia (opcional), Estado, Municipio y Parroquia. Si desconoces la parroquia, selecciona la opción "Parroquia Desconocida". Para asignar una dirección, haz clic en el botón **Asignar**.

Recuerda que una vez asignada la tripulación y el destino, debes hacer clic en el botón **Guardar** en la esquina inferior derecha del panel, para que la información se guarde efectivamente. Podrás notar que desaparecerá la advertencia **Asignar Tripulación y Ruta** (en la cabecera) e indicará la unidad asignada.

.. image:: ../images/Despachador/TripulaciónYRutaAsignadas.jpg

Posteriormente puedes dar inicio al flujo de trabajo del servicio AMD, haciendo clic en el botón **Paso 1 Completado** una vez ejecutado el despacho.

.. image:: ../images/Despachador/AMDPanelFlujoDeTrabajoPaso1Activado.jpg

Al hacer clic en este botón, la fecha y hora de despacho será establecida automáticamente. Podrás visualizar que el servicio cambiará su estatus a "En progreso" y que serás asignado como encargado de atender el servicio (ver el campo **Atendido por**).

.. image:: ../images/Despachador/AMDPanelFlujoDeTrabajoPaso1Completado.jpg

Al recibir los reportes de completación de cada paso del flujo de trabajo, debes ir registrando cada paso como completado haciendo clic en el botón correspondiente. Las fechas y horas se asignarán automáticamente.

También tienes la opción de editar las fechas y horas asignadas. Al hacer clic en el botón de "edición" (con ícono de "lápiz"), en la esquina superior derecha del área donde se visualiza el flujo de trabajo, se presentará una ventana de diálogo donde tendrás la posibilidad de asignar nuevas fechas y horas y de editar aquellas asignadas previamente.

.. image:: ../images/Despachador/EditarFechasYHoras.jpg

En el panel **Información de Servicio**, podrás visualizar los detalles generales del servicio. En caso de que incluya la realización de exámenes de laboratorio, se presentará en la cabecera del panel (donde se encuentra el título) un ícono azul de **matraz de Erlenmeyer**. Al posicionar el cursor sobre el ícono aparecerá el mensaje "Incluye exámenes de laboratorio". Podrás consultar el conjunto de exámenes en el campo **Exámenes de laboratorio** y editar los comentarios y el motivo de servicio.

.. image:: ../images/Despachador/AMDInformaciónDeServicio.jpg

Es responsabilidad del Despachador completar la información de los paneles **Diagnósticos**, **Solicitudes** y **Resultados** (en caso de que el servicio incluya exámenes de laboratorio).

En el panel **Diagnósticos** podrás añadir información acerca de los síntomas y diagnósticos detectados en la ejecución del servicio.

.. image:: ../images/Despachador/AMDDiagnósticos.jpg

Debes seleccionar al menos un item en el campo **Diagnóstico**. Si el diagnóstico no se encuentra en el listado que se despliega, puedes escribirlo en el campo **Otros diagnósticos**. Al terminar, haz clic en **Guardar**.

En el panel **Solicitudes** podrás agregar información referente al récipe, indicaciones, exámenes paraclínicos, observaciones y recomendaciones. Al terminar, haz clic en "Guardar".

.. image:: ../images/Despachador/AMDSolicitudes.jpg

En el panel **Resultados** podrás adjuntar documentos correspondientes a resultados de laboratorio asociados al servicio.

.. image:: ../images/Despachador/AMDResultados.jpg

Para adjuntar un resultado de laboratorio, haz clic en el botón de **sujetapapeles**. Se presentará una ventana de diálogo donde podrás adjuntar un documento y agregar una descripción (opcional). Al terminar, haz clic en **Adjuntar**.

.. image:: ../images/Despachador/AdjuntarResultado.jpg

.. warning::
    Recuerda que como Despachador debes registrar al menos un diagnóstico y, en caso de que el servicio AMD incluya exámenes de laboratorio, adjuntar los resultados de los mismos, para que posteriormente el Coordinador pueda cerrar el servicio completado.

.. note::
    Los servicios AMD con estatus **Cancelado**, **Abierto** o **Retrasado** no requieren Diagnóstico ni Resultados.

********************
Atender servicio TLD
********************

Al iniciar la atención de un servicio TLD, lo primero que debes hacer es asignar la tripulación y, en caso de que no hayan sido asignadas previamente, las direcciones de origen y destino. Para ello, te ubicas en el panel **Tripulación y Ruta**.

TODO: agregar imagen

El procedimiento para la asignación de tripulación y direcciones es análogo al explicado para la atención de un servicio AMD.

Una vez asignadas la tripulación y ruta, puedes dar inicio al flujo de trabajo del servicio TLD, haciendo clic en el botón "Paso 1 Completado" una vez ejecutado el despacho. Recuerda que existen dos tipos de traslados: "simple" e "ida y vuelta", a continuación te presentamos ambos flujos de trabajo.

TLD simple

TODO: agregar imagen

TLD ida y vuelta

TODO: agregar imagen

Al recibir los reportes de completación de cada paso del flujo de trabajo, debes ir registrando cada paso como completado haciendo clic en el botón correspondiente. Las fechas y horas se asignarán automáticamente.

Recuerda que tienes la opción de editar las fechas y horas asignadas, haciendo clic en el botón de "edición" (con ícono de "lápiz"), en la esquina superior derecha del panel de flujo de trabajo.

En el panel **Información de Servicio**, podrás visualizar los detalles generales del servicio. También podrás editar los comentarios y el motivo de servicio. Si el traslado corresponde a una emergencia, podrás visualizar una alerta roja en la parte derecha de la cabecera del panel. Al posicionar el cursor sobre el ícono aparecerá el mensaje "EMERGENCIA".

Es responsabilidad del Despachador completar la información del panel **Diagnósticos**.

.. warning::
    Recuerda que como Despachador debes registrar al menos un diagnóstico,
    para que posteriormente el Coordinador pueda cerrar el servicio completado.

.. note::
    Los servicios TLD con estatus **Cancelado**, **Abierto** o **Retrasado** no requieren
    Diagnóstico.

********************
Atender servicio EMD
********************

Es responsabilidad del Despachador completar la información de los paneles **Diagnósticos** y **Nota de Despacho**. En caso de que la nota de despacho haya sido completada, el Despachador debe verificarla.

.. note::
    Los roles Operador, Médico, Despachador, Coordinador, Gerente y Director,
    están autorizados para crear y/o editar la nota de despacho.

En el panel **Diagnósticos** debes añadir información acerca de los diagnósticos detectados en la ejecución del servicio.

TODO: agregar imagen

En el panel **Nota de Despacho** podrás crear, visualizar y editar el listado de los medicamentos, insumos y/o equipos médicos a ser entregados. Es importante señalar que si la nota de despacho incluye un equipo médico, debes programar un nuevo servicio EMD para su búsqueda.

.. warning::
    Recuerda que como Despachador debes registrar al menos un diagnóstico, así como
    completar y verificar la nota de despacho, para que posteriormente el Coordinador
    pueda cerrar el servicio completado.

.. note::
    Los servicios EMD con estatus **Cancelado**, **Abierto** o **Retrasado** no requieren
    Diagnóstico ni Nota de Despacho.

********************
Atender servicio PHD
********************

TODO: desarrollar

********************
Atender servicio LAB
********************

TODO: desarrollar

******************
Crear una atención
******************

Como Despachador, podrás crear nuevas atenciones. Ver sección :ref:`crear-atencion`.

**************
Crear servicio
**************

Como Despachador podrás crear servicios de tipo OMT, AMD, TLD, EMD, PHD y LAB. Ver detalles en las siguientes secciones:

* :ref:`crear-OMT`
* :ref:`crear-AMD`
* :ref:`crear-TLD`
* :ref:`crear-EMD`
* :ref:`crear-PHD`
* :ref:`crear-LAB`

Recuerda que en cualquier fase de ejecución de un servicio, podrás crear un nuevo servicio sucesivo, haciendo clic en el botón **Servicio sucesivo**. Al crear un servicio de esta manera, tienes la ventaja de que la plataforma asigna automáticamente ciertos datos relevantes asociados al servicio desde el cual se está creando el sucesivo: las direcciones de origen y destino, los diagnósticos y, en el caso de un servicio EMD, el origen de solicitud del mismo. Durante la creación de un servicio sucesivo, tendrás la opción de editar algunos de estos datos.

**************************************************
Detalles sobre la creación de un servicio sucesivo
**************************************************

1) La dirección de origen de un servicio TLD será asignada como la dirección de destino del servicio sucesivo AMD/EMD/LAB.
2) La dirección de destino de un servicio AMD/EMD/LAB será asignada como la dirección de origen del servicio sucesivo TLD.
3) La dirección de destino de un servicio HHC/HMD/LAB será asignada como la dirección de destino del servicio sucesivo AMD/EMD/LAB.
4) La información contenido en los campos **Diagnósticos** y **Otros Diagnósticos** será asignada al nuevo servicio sucesivo.
5) El origen de solicitud de un servicio OMT/AMD será asignado al servicio sucesivo EMD (no editable).

*****************
Cancelar servicio
*****************

La cancelación de un servicio puede ser ejecutada por cualquier usuario (a excepción del rol Asistente) y puede ocurrir en cualquier momento del desarrollo del mismo, por diversos motivos, por ejemplo: si el lugar en que se iba a prestar el servicio corresponde a una zona de difícil acceso y el afiliado no desea acordar otro punto de encuentro, si no se logra establecer contacto con el afiliado, etc.

El botón de **Cancelar Servicio** está ubicado en la cabecera del panel del flujo de trabajo. Si el servicio fue previamente cancelado o completado, el botón estará deshabilitado. Si el botón está habilitado aparecerá en color rojo. Al hacer clic sobre él, podrás visualizar una ventana de diálogo donde debes seleccionar el motivo de cancelación. Una vez seleccionado el motivo, haz clic en **Confirmar** y el servicio será cancelado inmediatamente.

.. image:: ../images/Despachador/CancelarServicio.jpg

.. _gestionar_tripulaciones:

***************************
Imprimir ticket de servicio
***************************

TODO: editar

Vamos a ver ahora cómo se hace la impresión de un ticket en el que se incluyen todos los detalles de un servicio. En todo momento vemos que dentro de la pestaña del servicio tenemos habilitado un ícono con la imágen de una impresora que sirve precisamente para imprimir los detalles del servicio.
Recordemos que en la impresión del ticket del servicio se imprime toda la información que se ha cargado en ese servicio. Es decir, si tenemos una tripulación asignada se informa y si tenemos un Diagnóstico también se informa. Sin embargo, si algunos de esos campos falta pues no aparecen al momento de la impresión del ticket, con lo cual es importante imprimir el ticket solamente en el momento en el que toda la información relativa a cada uno de los servicios involucrados, en este caso al servicio que se quiere imprimir, esté completamente indicada. 
Al seleccionar cualquiera de los servicios disponibles y hacer clic en **Imprimir ticket** del servicio se despliega la información disponible que será la que se refleja en el ticket impreso. Hacemos clic en el botón **Imprimir** y se genera un archivo en PDF que se pide a través de la instancia y se debe seleccionar la ubicación dentro de la computadora para ser almacenado.
Esa información se almacena en la carpeta que seleccione la persona y ya se ha generado el ticket respectivo en formato PDF.

***********************
Gestionar Tripulaciones
***********************

Si haces clic en el item **Tripulaciones** del menú lateral izquierdo, podrás visualizar el listado de tripulaciones activas (del día). Dispones de un campo de búsquedas en la parte superior derecha del listado para localizar una tripulación en específico.

.. image:: ../images/Despachador/ListadoTripulaciones.jpg

Al hacer clic sobre una fila del listado, se despliega una ventana de diálogo con todos los detalles de la tripulación seleccionada. 

.. image:: ../images/Despachador/DetallesTripulación.jpg

Podrás imprimir esta información haciendo clic en el ícono de "impresora", ubicado en la esquina inferior izquierda de la ventana de diálogo.

Si deseas editar una tripulación en particular, haz clic sobre el botón de "lápiz", en la fila correspondiente. Al terminar la edición, haz clic en **Guardar**.

.. image:: ../images/Despachador/EditarTripulación.jpg

Para crear una nueva tripulación, haz clic en el botón verde circular con signo "+". Al posicionar el cursor sobre el botón aparecerá el mensaje **Crear Tripulaciones**. Al hacer clic sobre el botón, aparecerá una ventana de diálogo con un formulario que debes completar. Te sugerimos que el nombre que le establezcas a la tripulación sea pertinente, de manera que te oriente al momento de seleccionar la tripulación a asignar a un servicio (por ejemplo: podría incluir el tipo de vehículo). Al terminar, haz clic en **Crear**.

.. image:: ../images/Despachador/CrearTripulación.jpg

Si deseas borrar una tripulación en particular, haz clic sobre el botón de **papelera**, en la fila correspondiente. Te aparecerá un aviso, para confirmar la eliminación de la tripulación, haz clic en **Borrar**.


.. image:: ../images/Despachador/AvisoBorrarTripulación.jpg