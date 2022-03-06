# Morosidad de clientes.
En este proyecto se aplicarán técnicas de aprendizaje automático, tanto supervisado como no supervisado, para predecir y analizar la morosidad de clientes.

El conjunto de datos está basada en los datos reales de una empresa proveedora de servicio de Internet.
Los datos han sido previamente anonimizados y escalados, con el fin de preservar la identidad de clientes, así como proteger la información sensible.

Diccionario del conjunto de datos.
<table>
    <tr>
        <td>
            <b>invoice_id</b>
        </td>
        <td>
            Identificador del número de factura.(Múltiples ítems pueden pertenecer a la misma factura).
        </td>
    </tr>
    <tr>
        <td>
            <b>service_contract_id</b>
        </td>
        <td>
            Identificador del número de contrato.
        </td>
    </tr>
    <tr>
        <td>
            <b>neighborhood</b>
        </td>
        <td>
            Sector en el que se ha instalado el servicio.
        </td>
    </tr>
    <tr>
        <td>
            <b>contract_days</b>
        </td>
        <td>
            Días transcurridos desde la fecha de contratación hasta la fecha de pago.
        </td>
    </tr>
    <tr>
        <td>
            <b>days_past_due</b>
        </td>
        <td>
            Días de retraso o anticipo en el pago <em>( 0< days_past_due >= 0 )</em>. Si <em>days_past_due</em> es negativo, significa que el pago se anticipó <em>|days_past_due|</em> días, caso contrario si es positivo, el pago se retrasó en <em>days_past_due</em>.
        </td>
    </tr>
    <tr>
        <td>
            <b>access_type</b>
        </td>
        <td>
            Tipo de acceso.
        </td>
    </tr>
    <tr>
        <td>
            <b>contract_plan</b>
        </td>
        <td>
            Tipo de contrato, corresponde al plan contratado por el cliente.
        </td>
    </tr>
    <tr>
        <td>
            <b>lat</b>
        </td>
        <td>
            Latitud de la instalación
        </td>
    </tr>
    <tr>
        <td>
            <b>lng</b>
        </td>
        <td>
            Longitud de la instalación
        </td>
    </tr>
    <tr>
        <td>
            <b>emision_date</b>
        </td>
        <td>
            Fecha de emisión de la factura
        </td>
    </tr>
    <tr>
        <td>
            <b>total_factura</b>
        </td>
        <td>
            Valor total de la factura a la cual pertenece el <em>item</em>. Pueden existir varios registros con el mismo numero de factura.
        </td>
    </tr>
    <tr>
        <td>
            <b>item_price</b>
        </td>
        <td>
            Valor del item facturado
        </td>
    </tr>
    <tr>
        <td>
            <b>incident_type</b>
        </td>
        <td>
            Tipo de incidente, NULL si el cliente no ha reportado un incidente  dentro del periodo (mes).
        </td>
    </tr>
    <tr>
        <td>
            <b>incident_count</b>
        </td>
        <td>
            Cantidad de veces que el cliente ha reportado un incidente dentro del periodo (mes).
        </td>
    </tr>
</table>

<b>Nota:</b> <em>trabajo en proceso, el diccionario de datos podría variar en función de nuevos requerimientos o descubrimiento de nuevas características que se consideren relevantes.</em>
