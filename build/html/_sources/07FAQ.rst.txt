********************
Preguntas Frecuentes
********************

*  **¿Quiénes pueden utilizar Atención-1?**

Pueden hacer uso de la aplicación Atención-1 el personal de Venemergencia con los roles de: **Operador**, **Médico**, **Despachador**, **Asistente**, **Coordinador**, **Gerente** y **Director**. Estas personas se designan, a efectos de la aplicación, bajo el nombre de *Usuarios*.

*  **¿Cuál es la diferencia entre Atenciones y Servicios?**

Para Atención-1 un *servicio* es una prestación sanitaria que se ofrece a afiliados, y una *atención* es el conjunto de servicios prestados al afiliado en un momento determinado. Cabe destacar que una atención puede englobar uno o más servicios.

*  **¿Cuáles servicios permite gestionar Atención-1?**

Atención-1 permite gestionar servicios OMT, AMD, EMD, TLD, PHD y LAB. Puedes consultar su significado y el de otras palabras en este :ref:`glosario` que hemos preparado.

*  **¿Cuántas atenciones puedo crear en un día a un mismo afiliado?**

Las atenciones creadas en un día para un mismo afiliado pueden ser varias. Sin embargo, te recomendamos que agrupes los servicios solicitados dentro de una sola atención teniendo presente las circunstancias particulares de cada caso.

*  **¿Atención-1 hace diferencia entre cancelar servicio y cerrar servicio?**

Cualquier servicio puede ser cancelado en cualquier momento durante su desarrollo. El proceso de cancelación incluye indicar el motivo por el cual se está cancelando. El cierre del servicio permite almacenar ese servicio y la atención que lo contiene en el histórico de atenciones de la base de datos de Atención-1 y requiere un nivel superior de autorización.

*  **¿Cuáles usuarios de Atención-1 pueden cancelar servicios y cuáles pueden cerrarlos?**

La cancelación de un servicio es una tarea que puede ser realizada por todos los usuarios. Sin embargo, el único usuario con *permisos* para realizar el *Cierre de Servicios* es el *Coordinador*. Puedes consultar los permisos atribuidos por usuario para el manejo de Atención-1 en la sección :ref:`roles` del manual de usuario que hemos preparado para tí.

*  **¿Para crear un servicio sucesivo debo antes cancelar el servicio que lo origina?**

Los servicios sucesivos se pueden crear en cualquier fase de un servicio y para esto *NO* necesariamente debes cancelar el servicio que lo origina, sino que se toma la información a partir de allí. 

*  **¿Con cuánto tiempo de anticipación muestra el sistema aquellos servicios programados para que sean atendidos sin retraso?**

En la sección *Próximas programadas* se muestran aquellas atenciones que deben ser tomadas en las próximas dos (02) horas. Al momento de aproximarse la hora programada, la atención pasará de la sección *Próximas programadas* a desplegarse en la sección *En espera* del panel de atenciones del usuario.

*  **Deseo crear una atención a un afiliado, pero no se encuentra en la base de datos. ¿Qué debo hacer?**

Esto puede suceder porque la persona ha contratado el servicio recientemente y su información aún no está disponible dentro del sistema. En estos casos la aplicación ofrece una sección donde puedes *Agregar un afiliado* donde, luego de hacer la búsqueda y comprobar que, efectivamente, sus datos no se encuentran en la base de datos, puedes agregar los datos básicos para atender sus solicitudes. 

En caso de que el afiliado haya contratado directamente su póliza de seguros, deberás seleccionar *Autofinanciada* como Contratante de dicha póliza. Es probable que se trate también de un usuario que desee acceder a servicios aunque no tenga ninguna póliza contratada con alguna aseguradora. En ese caso, puedes ofrecerle el pago por los servicios solicitados. Para ello, puedes agregarle una *póliza general* y seleccionar la opción Autofinanciada con plan *Retail*, que le permitirá pagar por los servicios solicitados.

*  **Si una persona solicita un determinado servicio y no se encuentra disponible en su póliza, ¿qué debo hacer?**

Al momento de seleccionar a un afiliado (luego de su búsqueda) Atención-1 muestra datos sobre sus planes y pólizas. Si observas que el plan de su póliza no incluye el servicio solicitado, puedes agregarle una póliza Autofinanciada con plan *Retail*, donde el afiliado podrá pagar por servicios adicionales distintos a los que le suministra su póliza.

*  **¿Cuáles datos son necesarios para agregar nuevos afiliados?**

Para incluir un nuevo afiliado, deberás asegurarte de introducir correctamente su nombre, apellido, género, fecha de nacimiento, compañía aseguradora, plan de la póliza, contratante y el nombre de la persona o instancia que autoriza esa inclusión.

*  **¿Cuáles datos son necesarios para crear atenciones?**

Una atención puede ser creada sólo cuando se completan todos los datos solicitados. Una vez realizada la consulta de los datos de afiliado, Atención-1 toma datos básicos de allí, a esos datos debe agregarse, al menos un número de teléfono del afiliado para proceder a la creación de la atención. Esto se observa cuando, al incluir y validar el número ingresado, se activa el botón *Crear* en la esquina inferior derecha.

*  **¿Qué debo hacer si no se despliegan las tripulaciones disponibles durante una guardia?**

Corresponde al *Despachador* agregar las tripulaciones al inicio del día. En caso de no desplegarse esta información se requiere que sea agregada por el rol correspondiente, asegurándose que el turno esté asignado de forma que abarque el horario en que se requiere.

*  **¿Qué debo hacer para incluir una entrega de equipos médicos?**

La entrega de equipos médicos se maneja a través de los servicios tipo EMD. En este caso, una vez introducido el equipo a entregar al afiliado, el sistema pedirá que se establezca la fecha y hora en que se retirará.

*  **¿Atención-1 permite acceder a información de servicios previos de los afiliados?**

El sistema permite mostrar, en el detalle de la atención, el histórico de atenciones y servicios anteriores. Esta información puede ser consultada, ingresando a la atención y desplegando la pestaña *Histórico de atenciones* ubicada en la sección izquierda debajo de la pestaña de los datos de afiliado.
Otra forma de realizar esta consulta es utilizando el módulo de *Consulta de afiliados* desde los roles de *Coordinador*, *Asistente*, *Gerente* o *Director*.

*  **¿Qué datos son necesarios para el cierre de servicios completados?**

Según el tipo de servicio, aquellos tengan estatus completado requerirán alguna información para permitir su cierre.

#. Los servicios OMT, TLD, PHD requieren tener diagnóstico para su cierre,
#. Un servicio AMD requiere diagnóstico y, además resultados si incluye laboratorio.
#. Un servicio EMD requiere diagnóstico y nota de despacho completa para su cierre.
#. Un servicio LAB requiere resultados para ser cerrado.

*  **¿Cómo notifico de un fallo en la aplicación?**

Se ha generado un formulario para reporte de fallos, que está disponible desde el siguiente `enlace <http://form.jotform.com/202515798622662>`_
