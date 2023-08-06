# Proyecto: Analisis del costo por abandono de empleados

Analizamos los datos de empleados en la empresa "Y" para calcular cuanto dinero pierde anualmente en entrenamiento, al nuevo personal que se debe contratar o mover de area, tras la renuncia de los empleados antiguos. Ademas nos permitio saber que empleados estan en riesgo de renunciar basandos en tecnicas de aprendizaje automatico, lo que nos permite generar politicas de retencion sobre personas especificas.

**La tabla con la que concluimos**:

<table>
  <thead>
    <tr>
      <th>Departamento</th>
      <th>Conteo de empleados en riesgo</th>
      <th>Impacto economico</th>
      <th>ID de empleado en riesgo</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Investigación y desarrollo</td>
      <td>4</td>
      <td>u$s 16.709</td>
      <td>9502, 3948, 7448, 9525</td>
    </tr>
    <tr>
      <td>Ventas</td>
      <td>2</td>
      <td>u$s 6.917</td>
      <td>2967, 5320</td>
    </tr>
  </tbody>
</table>

* Con un 50% de probabilidad, perderemos seis empleados el proximo año, dos en ventas y otros cuatro en Research & Development
* El costo asociado a ambas renuncias sera de unos u$s 23.626
* En la columna id_empleado podemos ver el numero de identificacion de los empleados en riesgo de renuncia