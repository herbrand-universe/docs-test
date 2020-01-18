---
description: >-
  En esta sección mostraremos todo lo referido a tu primer Lote/Batch en el
  sistema
---

# Primera Cocción

## Introducción

Asumimos que ya tenes cargado un producto en el sistema, si no es el caso podes ver la guia de primeros pasos

{% page-ref page="../primeros-pasos/" %}

Cuando cargas un producto automáticamente se genera una **Receta** con el mismo nombre.

Supongamos que tenemos cargado una cerveza **Amber Ale**, si nos dirigimos a `Producción => Receta` podremos ver lo siguiente



![Listado de Recetas](../.gitbook/assets/screenshot-guido.beerapp.net-2019.12.22-16_50_25.png)

Aquí se puede ver la receta base que se crea automáticamente al crear un producto.

## Edición de Receta

Las recetas esta compuesta por dos partes

* Datos Generales
* Insumos

Por ahora empecemos a cargar los datos generales de la receta, para esto hacemos `click` en el botón **Editar**.

A continuación podremos completar los datos generales, en especial un dato relevante que sugerimos completar es el de **Litros**, dado que este se utiliza para ir estimando los litros de un Lote.

Luego de eso si nos interesa podemos también ir cargando los insumos de las recetas, utilizando el botón **Seleccionar**. Esto nos permitirá llevar un control de stock de insumos utilizados.

Para ver más información sobre las recetas se puede acceder al siguiente link.

{% page-ref page="../produccion/menu-web/recetas.md" %}

## Creación de Lote

En este punto, tenemos tanto nuestro producto **Amber Ale** como también los datos de nuestra Receta base.

Nos dirigimos a **Producción =&gt; Lotes**, y aquí tendremos la posibilidad de crear uno nuevo. Lo primero que veremos es el listado de Lotes.

![Listado de Lotes](../.gitbook/assets/screenshot-guido.beerapp.com.ar-2019.07.29-15_10_20.png)

Para crear un nuevo **Lote** basta hacer `click` a la derecha de la barra de búsqueda en el botón **'Nuevo'** .

![Bot&#xF3;n de Nuevo Lote](../.gitbook/assets/screenshot-guido.beerapp.com.ar-2019.07.28-15_07_45.png)

Luego de esto aparecerá un formulario como el que sigue:

![Formulario de Alta/Edici&#xF3;n de Lotes](../.gitbook/assets/screenshot-guido.beerapp.com.ar-2019.07.29-15_20_29.png)

Los campos a completar son los siguientes:

* **Receta**: es el nombre de la receta base que vas a seguir.
* **Fecha Cocción**: es la fecha de inicio de cocción.
* **Cocciones**: es la cantidad de cocciones que vas a realizar
* **Código**: es el código de lote utilices
* **Descripción**: descripción si es necesario.
* **No descuenta stock?**: Si se activa, no sé descontará los insumos de tu stock.

{% hint style="info" %}
Si no manejas el stock por sistema aún o es una cocción con insumos que no están en el stock. Podes tildar la opción de **no descuenta stock**
{% endhint %}

{% hint style="warning" %}
Teniendo en cuenta los **litros** estimados de la receta y la cantidad de **cocciones** podemos estimar lo siguiente

**`litros_estimados = cocciones * litros_receta`**
{% endhint %}

{% hint style="warning" %}
Lo mismo pasa con los **insumos**, se multiplicará los insumos por la cantidad de **cocciones**.
{% endhint %}

Luego podes poner `click` en **Guardar** y se guardará tu **lote** el mismo quedará como `PLANIFICADO`.

## Detalle del Lote

En el **listado de lotes** basta hacer `click` en el botón **seleccionar** del lote que queremos saber más información para que nos llevé a la pantalla de detalle.

![Bot&#xF3;n de Selecci&#xF3;n de Lote](../.gitbook/assets/screenshot-guido.beerapp.com.ar-2019.07.28-15_14_56.png)

A continuación se mostrará una pantalla como la siguiente:

![Detalle de Lote Planificado](../.gitbook/assets/screenshot-guido.beerapp.com.ar-2019.07.29-15_35_16.png)

{% hint style="warning" %}
Acá podrás ver que se **copiaron** todos los **insumos** de la receta base.
{% endhint %}

{% hint style="danger" %}
Cualquier modificación de los insumos **no se verá reflejada en la Receta.** Si algún insumo no tenes stock podes cambiarlo por otro si tocar la receta base
{% endhint %}

Podrás realizar todas las modificación que gustes y cuando sea el día de la cocción deberás hacer `click` en el botón **Comenzar**

![](../.gitbook/assets/screenshot-guido.beerapp.com.ar-2019.07.29-15_40_36.png)

{% hint style="success" %}
En este momento si tenias habilitado la opción se descontarán todos los insumos utilizados
{% endhint %}

## Registrar en qué Tanque se guarda un Lote

Una vez terminada la **cocción** o la primera cocción tendrás la posibilidad de camiar el estado al lote que actualmente esta `EN COCCIÓN.`

Esto lo podes realizar ingresando al **Detalle de Lote**, ahí podrás ver este formulario:

![Formulario de Cambio de Estado en un Lote Activo](../.gitbook/assets/screenshot-guido.beerapp.com.ar-2019.07.29-15_48_53.png)

Los campos necesarios son los siguientes

* **Etapa:** podrás elegir una etapa descriptiva de en que proceso se encuentra el lote.
* **Tanque:** tenes que elegir a que tanque vas a mandar tu cerveza
* **Litros:** acá podes ir puliendo los litros estimados que hay en el tanque.

{% hint style="success" %}
El sistema validará que el Tanque este **VACIO** antes de asignarlo.
{% endhint %}

{% hint style="info" %}
Si divides un lote en varios tanques podes hacer `click` en el **+** en la esquina superior izquierda para agregar otro tanque.
{% endhint %}

{% hint style="warning" %}
Recuerda que cuando sale de cocción siempre tendrá que estar en, al menos, 1 tanque hasta su finalización.
{% endhint %}

Desde ahora hasta que finalices el lote tendrás disponibles las opciones de envasar o embarrilar.

## Envasado

Una vez finalizada la fermentación y la maduración es el momento de pasar tu cerveza sus respectivos envases, para esto existe la pantalla Producción =&gt; Envasado la que te permitirá ir sacando litros del Tanque y pasarlo a Envases de distintas formas:

* Envasarlo a barriles Propios
* Envasarlo a barriles Externos \(Barriles que no te pertenecen y no tenes cargado en tú sistema\)
* Otros Envases \(Lates, Botellas, PETs, etc\)

Para ver un poco más sobre como se realiza el envasado te sugerimos ver el siguiente enlace.

{% page-ref page="../produccion/menu-web/envasado.md" %}

Cuando ya todo este envasado y quieras liberar todos los fermentadores deberás finalizar el lote.

## Finalizar un Lote

Cuando **no haya más que envasar** y los tanques estén vacíos de este Lote lo que tienes que hacer es finalizarlo.

![](../.gitbook/assets/screenshot-guido.beerapp.com.ar-2019.07.29-15_59_34.png)

{% hint style="danger" %}
Atención luego de finalizar ya no se podrá seguir envasando.
{% endhint %}

{% hint style="info" %}
Todo lo que ya envaso seguirá igual, solo no se podrá envasar más
{% endhint %}

Al finalizar se recolectan estadísticas como cuantos litros reales se envasaron para su posterior uso.

Desde este momento todos los Tanques asociados pasaran a estar `Vacio` y se podrán usar para otro Lote.





