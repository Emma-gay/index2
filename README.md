<!DOCTYPE html>
<html lang="es">
<body>

<center> 
    <h1>Formulario</h1>
    <form action= "https://example.com/submit" method="POST">
        <label for="nombre">Nombre:</label>
        <input type="text" id="nombre" name="nombre"><br><br>

        <label for="edad">Edad:</label>
        <input type="number" id="edad" name="edad" min="0"><br><br>

        <label for="email">Email:</label>
        <input type="email" id="email" name="email"><br><br>

        <label for="pais">País:</label>
        <select id="pais" name="pais">
            <option value="españa">España</option>
            <option value="mexico">México</option>
            <option value="argentina">Argentina</option>
        </select><br><br>

        <label>Género:</label><br>
        <input type="radio" id="masculino" name="genero" value="masculino">
        <label for="masculino">Masculino</label><br>
        <input type="radio" id="femenino" name="genero" value="femenino">
        <label for="femenino">Femenino</label><br><br>

        <label for="comentarios">Comentarios:</label><br>
        <textarea id="comentarios" name="comentarios" rows="4" cols="50"></textarea><br><br>

        <input type="checkbox" id="suscripcion" name="suscripcion" value="si">
        <label for="suscripcion">Quiero suscribirme al boletín</label><br><br>

        <input type="submit" value="Enviar">
    </form></center>
 <font size="4">
<p>Crear un formulario complejo en HTML implica el uso de varias etiquetas y atributos para capturar diversos tipos de información del usuario, como texto, números, correos electrónicos, archivos, entre otros. A continuación, te explico paso a paso cómo estructurar un formulario con diferentes tipos de campos, validaciones y organización visual. Debes comenzar con la etiqueta <u>"form"</u> que define el área donde se recopilarán los datos. A continuacion debes usar <u>"action"</u>: la cual especifica a dónde se enviarán los datos cuando se envíe el formulario .
<u>"method"</u>: Define el método de envío de los datos (GET o POST). Se recomienda POST para formularios más complejos o sensibles.</p><p> Campos de texto ("input type="text"")<u>"label>"</u>: Vincula un texto con su campo correspondiente. El atributo for debe coincidir con el id del campo al que está asociado.
<u>"required"</u>: Hace que el campo sea obligatorio.</p>
<p>Campo de correo electrónico ("sinput type="email"")</p>
<p> Selector de números (input type="number"")</p>
<p>Selector de fechas ("input type="date"")</p>
<p>Área de texto (para agregar seccion de comentarios usa "textarea"</p>
<p>Menú desplegable usa "select"</p>
<p>Botones de radio ("input type="radio"")</p>
<p>Casillas de verificación ("input type="checkbox"")</p>
<p>Botón de envío ("button type="submit"")</p>
     

 <p> siguiente pagina <a href="https://emma-gay.github.io/index3/"> siguiente.</p>
