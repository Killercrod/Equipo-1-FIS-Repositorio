**Caso de Uso 1: Ver Guía de Asignaturas**

-   **Usuario:** Alumno de nuevo ingreso
-   **Objetivo:** Facilitar al alumno la consulta de las asignaturas del primer al tercer semestre.
-   **Precondiciones:**

-   El alumno debe haber iniciado sesión en el sistema.

-   **Flujo principal:**

1.  El alumno accede a la guía FTBUADY mediante sus credenciales

2. El sistema muestra una lista con las asignaturas de los respectivos semestres.

3. El alumno elige una asignatura para consultar su información.

4. El sistema despliega la información general de la asignatura.

**Caso de Uso 2: Visualización de colores para asignaturas no relacionadas**

**Usuario:** alumno de nuevo ingreso

**Objetivo:** El sistema mostrará un color en cada asignatura, similar a un semáforo, para indicar qué asignaturas no están estrechamente relacionadas con el curso seleccionado.

**Precondiciones**:

-   El usuario ha iniciado sesión en el sistema.
-   El usuario ha seleccionado un curso o materia en el sistema.

**Flujo de Eventos**:

1.  **Flujo Principal**:

1.  El usuario selecciona una materia.
2.  La guía muestra la relación de cada asignatura con el curso seleccionado.
3.  El guía asigna un color a cada asignatura:

-   **Verde**: Asignaturas muy relacionadas con el curso seleccionado.
-   **Amarillo**: Asignaturas moderadamente relacionadas con el curso seleccionado.
-   **Rojo**: Asignaturas poco relacionadas con el curso

5.  El sistema muestra los colores correspondientes junto al nombre(s) de cada asignatura.
6.  El usuario puede ver y analizar la lista de asignaturas con los colores indicados.

Para el requisito proporcionado, aquí tienes un caso de uso detallado:

**Caso de Uso 3: Recomendación de asignaturas relacionadas en base a consejos**

**Usuario**: alumno de primer semestre

**Precondiciones**:

-   El estudiante ha iniciado sesión en el sistema.

-  El estudiante ha seleccionado una asignatura de su interés

-   **Flujo Principal**:

1.  El estudiante ingresa al sistema y selecciona una asignatura de su interés o que desea continuar.
2.  La guía muestra las asignaturas relacionadas a la asignatura seleccionada.
3.  El sistema genera consejos en base a las asignaturas más relacionadas o en caso contrario, menos relacionadas
4.  El estudiante puede ver el consejo de la(s) materia más relacionada y así determinar con cual continuar
