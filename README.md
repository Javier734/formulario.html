# formulario.html<!DOCTYPE html>
<html>
<head>
	<meta charset="UFT-8">
	<title>Mision</title>
</head>
<body style="background:#0C897C">
	<h1 style="color:white; background:black">Formulario</h1>
	<table border="1">
	<tr colspan="2">Datos Personales</tr>
	<tr>
		<td><label for="">Nombres</label></td>
		<td><input type="text" name="nombre" id="" value=""></td>
	</tr>

	<tr>
		<td><label for="">Apellidos</label></td>
		<td><input type="text" name="nombre" id="" value=""></td>
	</tr>

	<tr>
		<td><label for="">Correo</label></td>
		<td><input type="text" name="nombre" id="" value=""></td>
	</tr>

	<tr>
		<td><label for="">Cedula</label></td>
		<td><input type="text" name="nombre" id="" value=""></td>

	</tr>
</table>
<br>
<input type="checkbox" name="musica" id="" value="menor de edad">Menor de edad
<br>
<br>
<br><label for="">Elige tu profesion</label>
<input type="checkbox" name="medico" id="" value="medico">Medico
<input type="checkbox" name="ingeniero" id="" value="ingeniero">Ingeniero
<input type="checkbox" name="estudiante" id="" value="estudiante">Estudiante
<input type="checkbox" name="otro" id="" value="otro">Otro
<br>
<br>

<br><label for="">Elige tu sexo</label>
<select id="" name="sexo">
<option value="masculino">Masculino</option>
<option value="femenino">Femenino</option>
<option value="sin especificar">Sin especificar</option>
</select>

<br><label for="">Elige tu pais</label>
<select id="" name="pais">
	<option value="colombia">Colombia</option>
	<option value="argentina">Argentina</option>
	<option value="chile">Chile</option>
	<option value="brasil">Brasil</option>
	<option value="peru">Peru</option>
	<option value="ecuador">Ecuador</option>
	<option value="uruguay">Uruguay</option>
	<option value="holanda">Holanda</option>
</select>

<br>
<br>
<a href="https://www.facebook.com" target="about_blank">Ir A Facebook</a>

<br>
<br>
<input type="submit" name="Enviar">
<input type="reset" name="Restablecer">
<br>
<br>

</body>
</html>
