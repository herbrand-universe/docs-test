---
description: Listados de Lotes
---

# Lotes

## Listado de Lotes

![Listado de Lotes](../../.gitbook/assets/screenshot-guido.beerapp.com.ar-2019.07.29-15_10_20.png)

En esta pantalla se podrá observar todas los lotes. Las columnas darán un detalle de los datos relevantes de cada lote.

* **Fecha Cocción**: es fecha estimada de inicio de cocción.
* **Código**: es el código del lote, nos sirve para identificar un lote en el futuro.
* **Producto**: es el producto que se produce con la receta
* **Tanque:** es el tanque que contiene la cerveza.
* **Envasado:** es la cantidad de litros envasados hasta el momento
* **Disp:**  es la cantidad aproximada de litros por envasar
* **Barriles:**  Son los barriles ya envasados que todavía no vendiste este lote.
* **Estado:**  Lo explicaremos más adelante.

{% hint style="success" %}
Los **litros** de tu receta se utilizan para estima cuantos litros vas a producir en cada lote. \(Teniendo en cuenta el número de cocciones\)
{% endhint %}

## Búsqueda de Lote

![Barra de B&#xFA;squeda de Lote](../../.gitbook/assets/screenshot-guido.beerapp.com.ar-2019.07.28-15_32_03.png)

Por medio de la barra de búsqueda se podrá filtrar los **lotes**  por su **nombre**. Basta escribir un texto y apretar `Enter`

## Nuevo Lote

Para crear un nueva **Lote** basta hacer `click` a la derecha de la barra de búsqueda en el botón **'Nuevo'** .

![Bot&#xF3;n de Nuevo Lote](../../.gitbook/assets/screenshot-guido.beerapp.com.ar-2019.07.28-15_07_45.png)

Luego de esto aparecerá un formulario como el que sigue:

![Formulario de Alta/Edici&#xF3;n de Lotes](../../.gitbook/assets/screenshot-guido.beerapp.com.ar-2019.07.29-15_20_29.png)

Los campos a completar son los siguientes:

* **Receta**: es el nombre de la receta que vas a seguir.
* **Fecha Cocción**: es la fecha de inicio de cocción.
* **Cocciones**: es la cantidad de cocciones que vas a realizar
* **Código**: es el código de lote
* **Descripción**: descripción si es necesario.
* **No descuenta stock?**: Si se activa, no sé descontará los insumos de tu stock.

{% hint style="info" %}
Si no manejas el stock por sistema aún o es una cocción con insumos que no estan en el stock. Podes tildar la opción de **no descuenta stock**
{% endhint %}

{% hint style="warning" %}
Teniendo en cuenta los **litros** estimados de la receta y la cantidad de **cocciones** podemos estimar lo siguiente

**`litros_estimados = cocciones * litros_receta`**
{% endhint %}

{% hint style="warning" %}
Lo mismo pasa con los **insumos**, se multiplicará los insumos por la cantidad de **cocciones**.
{% endhint %}

Luego podes poner `click` en **Guardar** y se guardará tu **lote** el mismo quedará como `PLANIFICADO`.

## Detalle de la Receta

En el **listado de recetas** basta hacer `click` en el botón seleccionar de la receta que queremos saber más información para que nos llevé a la pantalla de detalle.

![Bot&#xF3;n de Selecci&#xF3;n de Receta](../../.gitbook/assets/screenshot-guido.beerapp.com.ar-2019.07.28-15_14_56.png)

A continuación se mostrará una pantalla como la siguiente:

![Detalle de Lote Planificado](../../.gitbook/assets/screenshot-guido.beerapp.com.ar-2019.07.29-15_35_16.png)

{% hint style="warning" %}
Acá podrás ver que se **copiaron** todos los **insumos** de la receta base.
{% endhint %}

{% hint style="danger" %}
Cualquier modificación de los insumos **no se verá reflejada en la Receta.** Si algún insumo no tenes stock podes cambiarlo por otro si tocar la receta base
{% endhint %}

Podrás realizar todas las modificación que gustes y cuando sea el día de la cocción deberás hacer `click` en el botón **Comenzar**

![](../../.gitbook/assets/screenshot-guido.beerapp.com.ar-2019.07.29-15_40_36.png)

{% hint style="danger" %}
Una vez comenzado la cocción ya no podrás modificar ningún insumo.
{% endhint %}

{% hint style="success" %}
En este momento si tenias habilitado la opción se descontarán todos los insumos utilizados
{% endhint %}

## Registrar en qué Tanque se guarda un Lote

Una vez terminada la **cocción** o la primera cocción tendrás la posibilidad de camiar el estado al lote que actualmente esta `EN COCCIÓN.`

Esto lo podes realizar ingresando al **Detalle de Lote**, ahí podrás ver este formulario:

![Formulario de Cambio de Estado en un Lote Activo](../../.gitbook/assets/screenshot-guido.beerapp.com.ar-2019.07.29-15_48_53.png)

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

## Finalizar un Lote

Cuando **no haya más que envasar** y los tanques estén vacíos de este Lote lo que tienes que hacer es finalizarlo.

![](../../.gitbook/assets/screenshot-guido.beerapp.com.ar-2019.07.29-15_59_34.png)

{% hint style="danger" %}
Atención luego de finalizar ya no se podrá seguir envasando.
{% endhint %}

{% hint style="info" %}
Todo lo que ya envaso seguirá igual, solo no se podrá envasar más
{% endhint %}

Al finalizar se recolectan estadísticas como cuantos litros reales se envasaron para su posterior uso.

