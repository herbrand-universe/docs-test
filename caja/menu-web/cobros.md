---
description: Funcionalidad de Cobros a Clientes
---

# Cobros

## Listado de Cobros

![Listado de Cobros](../../.gitbook/assets/screenshot-guido.beerapp.com.ar-2019.08.24-09_06_46.png)

En esta pantalla se podrá observar todos los cobros realizados y sus estados correspondientes.  Las columnas darán un detalle de los datos relevantes de los cobros.

* **Fecha**: el la fecha asociada al cobro
* **Cliente:**  es el cliente al que se realizo el cobro
* **Forma:**  Es la forma de pago.
* **Cuenta:** Es la cuenta desde donde se cargo el cobro.
* **Concepto:**  Concepto asociado al cobro.
* **Importe:** Importe cobrado
* **Activo:** Si el cobro esta activo o `Anulado`

## Búsqueda de Pagos

![Barra de Busqueda](../../.gitbook/assets/screenshot-guido.beerapp.com.ar-2019.08.24-08_56_24.png)

Por medio de la barra de búsqueda se podrá filtrar los **cobros**  por su **cuit, nombre o razón social**. Basta escribir un texto y apretar `Enter`

## Nuevo Cobro

Basta hacer `click` a la derecha de la barra de búsqueda en el botón **'Nuevo'** para acceder al formulario para la creación de un nuevo pago.

![Bot&#xF3;n de Nuevo Pago](../../.gitbook/assets/screenshot-guido.beerapp.com.ar-2019.07.28-15_07_45.png)

Luego de esto aparecerá un formulario como el que sigue:

![Formulario de Alta de Cobro](../../.gitbook/assets/screenshot-guido.beerapp.com.ar-2019.08.24-09_06_00.png)

Completando los siguientes datos solicitados :

* **Fecha:** Es la fecha en que se imputa el cobro
* **Cuenta**: Es la cuenta desde donde se reciben los fondos
* **Forma**: Es el medio de pago
* **Cliente**: El cliente al que se realiza el cobro
* **Plan de Cuenta:** Es un identificador para agrupar movimientos de cuentas
* **Concepto**: Es una descripción del cobro a realizar
* **Importe**: Es el importe que se va a cobrar.

Luego de eso podrá realizar `click` en Guardar. Esto generará dos cosas:

* Un ingreso de dinero en la cuenta seleccionada
* Un egreso de dinero en la cuenta corriente del cliente.

