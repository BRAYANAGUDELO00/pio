<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Desarrollo Formulario en HTML</title>
</head>
<body>
    <h2>FORMULARIO EN HTML</h2>
    <form action="/submit" method="post">
        <fieldset>
            <legend>DATOS PERSONALES</legend>
            <label for="nombre completo">Nombre Completo</label> <br>
            <input type="text" id="id" name="nombre completo" minlength="3" required><br><br>
            <label for="correo">Correo Electronico</label><br>
            <input type="email" name="correo" id="correo" required
            pattern="[a-zA-Z0-9._%+-]+@[a-zA-Z0-9]+\.a-zA-Z{2, }"
            title= "formato de correo electronico: ejemplo@dominio.com"><br>
            <br>
            <label for="password">Password</label>
            <br>
            <input type="password" id="password" name="password" minlength="8" required>
            <br>
            <label for="edad">Edad entre 18 y 100 años</label>
            <br>
            <input type="number" name="edad" id="edad" min="18" max="100">
            <br>
            <label for="fecha_nacimiento">Fecha de nacimiento</label>
            <br>
            <input type="date" name="fecha_nacimiento" id="fecha_nacimiento" required>
            <br>
            <label for="genero">Genero</label>
            <br>
            <input type="checkbox" name="femenino" id="femenino" required>Femenino
            <br>
            <input type="checkbox" name="masculino" id="masculino" required>Masculino
            <br>
            <input type="checkbox" name="otro" id="otro" required>Otro
            <br>

        </fieldset>
        <br>
        <br> 
        <fieldset>

            <label for="sitio web">Sitio Web Personal</label>
            <legend>INFORMACION ADICIONAL</legend>  
            <br>
            <input type="url" name="url" id="url" required>
            <br>
            <label for="documento">Documento</label>
            <br>
            <input type="file" name="documento" id="file" required>
            <br>
            <br>
            <label for="comentario">Regalanos un comentario para mejorar:(de 10 a 200 caracteres)</label>
            <br>
            <textarea name="comentario" id="comentario"></textarea>
            <br>
            <label for="T Y C">Aceptas los terminos y condiciones?</label>
            <br>
            <input type="checkbox" name="terminos y condiciones" id="checkbox" required>
            <br>
            <label for="suscripcion">Suscribase a nuestro boletin</label>
            <br>
            <input type="checkbox" name="suscripcion" id="suscripcion" required>
            <br>
            <label for="enviar"></label>
            <input type="submit" value="Enviar">
            <input type="reset" value="Borrar">
        </fieldset>
    </form>
</body>
</html>
