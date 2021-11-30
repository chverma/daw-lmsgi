# DTD

Donat el següent document XML, crea un fitxer DTD per tal de compartir la informació de tots els sistemes informàtics de la Conselleria d'Educació, Cultura i Esports.

## Criteris de correcció:
- Crear tots els elements necessaris (2 punts)
- Crear tots els atributs necessaris (2 punts)
- Crear els atributs que puguen ser del tipus enumerable, és a dir, si sols poden ser certs valors (1 punts)
- Configurar atributs obligatoris i opcionals (1) 
- Configurar correctament el número d'elements que podem trobar dins de cada element pare (modificadors) (4)

## Document XML
[Punxa ací per descarregar el fitxer XML](notes.xml)

[Punxa ací per descarregar la plantilla DTD](notes.dtd)
    <?xml version="1.0" encoding="UTF-8" ?>

    <!DOCTYPE notas SYSTEM "notes.dtd">
    <notas>
        <alumno convocatoria="Septiembre">
            <nombre>Carlos</nombre>
            <apellidos>Amaya Arozamena</apellidos>
            <nif>56534432X</nif>
            <matricula>m019843</matricula>
            <cuestionarios>8.0</cuestionarios>
            <tareas>8.0</tareas>
            <examen>6.0</examen>
            <final>8.0</final>
        </alumno>
        <alumno convocatoria="Junio">
            <nombre>Jose</nombre>
            <apellidos>Muñoz Soto</apellidos>
            <nif>2222123123X</nif>
            <matricula num_matriculaciones="2">m019872</matricula>
            <faltas_justificadas>4</faltas_justificadas>
            <problemas_personales>
                <problema tipo="físico">Se desplaza en silla de ruedas</problema>
            </problemas_personales>
            <cuestionarios>7.0</cuestionarios>
            <tareas fuera_de_plazo="2">9.0</tareas>
            <examen>7.0</examen>
            <final>8.5</final>
            <observaciones>Trabaja mucho</observaciones>
        </alumno>
        <alumno convocatoria="Junio">
            <nombre>Ana</nombre>
            <apellidos>Martinez de la Fuente</apellidos>
            <matricula>m097215</matricula>
            <cuestionarios>8.0</cuestionarios>
            <tareas>9.0</tareas>
            <examen>9.0</examen>
            <final>8.5</final>
        </alumno>
        <alumno convocatoria="Septiembre">
            <nombre>Roberto</nombre>
            <apellidos>Carrera Fernández</apellidos>
            <matricula>m059312</matricula>
            <faltas_injustificadas>20</faltas_injustificadas>
            <cuestionarios>6.0</cuestionarios>
            <tareas>7.0</tareas>
            <examen>6.0</examen>
            <final>6.5</final>
        </alumno>
        <alumno convocatoria="Septiembre">
            <nombre>Concepción</nombre>
            <apellidos>Lalinde Priego</apellidos>
            <nie>202211X</nie>
            <matricula>m034093</matricula>
            <cuestionarios>4.0</cuestionarios>
            <tareas>3.0</tareas>
            <examen>2.0</examen>
            <final>3.0</final>
        </alumno>
        <alumno convocatoria="Junio">
            <nombre>Esther</nombre>
            <apellidos>Pereda</apellidos>
            <matricula>m938762</matricula>
            <problemas_personales>
                <problema tipo="laboral">Trabaja 8h/dia</problema>
                <problema tipo="personal">Tiene 3 hijos</problema>
            </problemas_personales>
            <cuestionarios>2.0</cuestionarios>
            <tareas>3.0</tareas>
            <examen>2.0</examen>
            <final>2.5</final>
        </alumno>
    </notas>
