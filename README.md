<div align="center">
<table>
    <theader>
        <tr>
            <td><img src="https://github.com/rescobedoq/pw2/blob/main/epis.png?raw=true" alt="EPIS" style="width:50%; height:auto"/></td>
            <th>
                <span style="font-weight:bold;">UNIVERSIDAD NACIONAL DE SAN AGUSTIN</span><br />
                <span style="font-weight:bold;">FACULTAD DE INGENIERÍA DE PRODUCCIÓN Y SERVICIOS</span><br />
                <span style="font-weight:bold;">ESCUELA PROFESIONAL DE INGENIERÍA DE SISTEMAS</span>
            </th>
            <td><img src="https://github.com/rescobedoq/pw2/blob/main/abet.png?raw=true" alt="ABET" style="width:50%; height:auto"/></td>
        </tr>
    </theader>
    <tbody>
        <tr><td colspan="3"><span style="font-weight:bold;">Formato</span>: Guía de Práctica de Laboratorio / Talleres / Centros de Simulación</td></tr>
        <tr><td><span style="font-weight:bold;">Aprobación</span>:  2022/03/01</td><td><span style="font-weight:bold;">Código</span>: GUIA-PRLD-001</td><td><span style="font-weight:bold;">Página</span>: 1</td></tr>
    </tbody>
</table>
</div>

<div align="center">
<span style="font-weight:bold;">INFORME DE LABORATORIO</span><br />
<span>(formato estudiante)</span>
</div>


<table>
<theader>
<tr><th colspan="6">INFORMACIÓN BÁSICA</th></tr>
</theader>
<tbody>
<tr><td>ASIGNATURA:</td><td colspan="5">Programación Web 2</td></tr>
<tr><td>TÍTULO DE LA PRÁCTICA:</td><td colspan="5">Django</td></tr>
<tr>
<td>NÚMERO DE PRÁCTICA:</td><td>05</td><td>AÑO LECTIVO:</td><td>2022 A</td><td>NRO. SEMESTRE:</td><td>III</td>
</tr>
<tr>
<td>FECHA DE PRESENTACION:</td><td>08-Jun-2022</td><td>HORA DE PRESENTACION:</td><td colspan="3">21:00</td>
</tr>
<tr><td colspan="3">Integrantes:
<ul>
<li>Kevin Pedro Yare Chulunquia</li>
<li>Joel Erick Gutierrez Puma</li>
<li>Joaquín Gonzalo Paredes Mescco</li>
</ul>
</td>
<td>NOTA:</td><td colspan="2"></td>
</tr>
<tr><td colspan="6">DOCENTES:
<ul>
<li>Richart Smith Escobedo Quispe (rescobedoq@unsa.edu.pe)</li>
</ul>
</td>
</<tr>
</tdbody>
</table>


# Solución y resultados

## I.		SOLUCIÓN DE EJERCICIOS/PROBLEMAS

-  Crea un blog sencillo en un entorno virtual utilizando la guía: https://tutorial.djangogirls.org/es/django_start_project/
-  Especificar paso a paso la creación del blog en su informe.
-  Crear un video tutorial donde realice las operaciones CRUD (URL public reproducible online)
-  Adjuntar URL del video en el informe.

  https://youtu.be/7hWELOk0Dp0

#
    
## II.	SOLUCIÓN DE CUESTIONARIO

- ¿Cuál es un estándar de codificación para Python? Ejemplo: Para PHP en el proyecto Pear https://pear.php.net/manual/en/standards.php
    * Un estandar muy conocido para python es PEP8, que fue creado en 2001. Y es el manual de estilo que aborda los temas de cómo nombrar clases, funciones y variables. Además de como cubre todos los aspectos de estilos que pueden surgir mientras programamos, en consecuencia, el estándar completo es un poco extenso.
    * ![image](https://user-images.githubusercontent.com/64146055/173198788-16b69c0b-d7df-4b8f-b98d-0b5e3b228aa8.png)
    * Por otro lado, esta PyPI, el cual es el repositorio de software oficial para aplicaciones de terceros en el lenguaje de programación Python. De esta manera, los desarrolladores de Python pretenden que sea un catálogo exhaustivo de todos los paquetes de Python escritos en código abierto.
 
- ¿Qué diferencias existen entre EasyInstall, pip, y PyPM?
    * Pip resulta como alternativa de EasyInstall, ya que este último quedo en desuso.
    * De esta manera podemos encontrar algunas diferencias entre estos últimos.
    <table style="width:100%">
  <tr>
    <td style="text-align:right"></td>
    <td style="text-align:right">pip</td>
    <td style="text-align:right">easy_install</td>
  </tr>
  <tr>
    <td>Instalaciones desde Wheels</td>
    <td>si ( )python -m pip uninstall</td>
    <td>No</td>
  </tr>
   <tr>
    <td>Desinstalar paquetes</td>
    <td>Si</td>
    <td>No</td>
  </tr>
   <tr>
    <td>Anulaciones de dependencia</td>
    <td>Sí ( archivos de requisitos )</td>
    <td>No</td>
  </tr>
    </tr>
   <tr>
    <td>Lista de paquetes instalados</td>
    <td>si ( y )python -m pip listpython -m pip freeze</td>
    <td>No</td>
  </tr>
   <tr>
    <td>Apoyo PEP 438</td>
    <td>si</td>
    <td>No</td>
  </tr>
  <tr>
    <td>Formato de instalación</td>
    <td>Paquetes 'planos' con egg-info metadatos.</td>
    <td>Formato Huevo Encapsulado</td>
  </tr>
  <tr>
    <td>modificación de sys.path</td>
    <td>No</td>
    <td>Si</td>
  </tr>
  <tr>
    <td>soporte de pylauncher</td>
    <td>No</td>
    <td>Si</td>
  </tr>
  <tr>
    <td>Excluir scripts durante la instalación</td>
    <td>No</td>
    <td>Si</td>
  </tr>
  <tr>
    <td>índice por proyecto</td>
    <td>Solo en virtualenv</td>
    <td>Sí, a través de setup.cfg</td>
  </tr>
</table>
    * Por otro lado, PyPM, Administrador de paquetes de Python para Python 3, es similar a npm. Nos permite realizar tareas de localización, instalación, actualización y eliminación de paquetes de Python. Por otro lado, PyPM no es gratuito y solo se puede usar con la distribución ActivePython de ActiveState .
   
- En un proyecto Django que se debe ignorar para usar git. Vea: https://github.com/django/django/blob/main/.gitignore. ¿Qué otros tipos de archivos se deberían agregar a este archivo?
- Utilice python manage.py shell para agregar objetos. ¿Qué archivos se modificaron al agregar más objetos?

#

## III.	CONCLUSIONES

- En conclusión, Django es uno de los Frameworks de Python más populares, trayendo grandes beneficios a los desarrolladores. Así, a pesar de que recien empezamos a conocer este framework, ya resulta muy práctico su uso y comprensión.
- 

## REFERENCIAS Y BIBLIOGRÁFIA RECOMENDADAS
-   [https://www.w3schools.com/python/python_reference.asp
-   https://docs.python.org/3/tutorial/1](https://developer.mozilla.org/es/docs/Learn/Server-side/Django/Models
-   https://tutorial.djangogirls.org/es/django_models/
-   https://pear.php.net/manual/en/standards.php
-   https://docs.djangoproject.com/en/4.0/)
-   https://www.youtube.com/watch?v=M4NIs4BM1dk
-   https://pypi.org/
-   https://pip.pypa.io/en/latest/user_guide/
-   https://packaging.python.org/en/latest/tutorials/installing-packages/
-   https://peps.python.org/pep-0008/
-   https://packaging.python.org/en/latest/discussions/pip-vs-easy-install/
