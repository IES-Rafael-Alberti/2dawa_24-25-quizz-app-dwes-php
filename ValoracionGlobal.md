## Lista de Verificación Integral de Prácticas de Programación en PHP

### **Evaluación Unificada: Aplicación de Cuestionario en PHP**

**Criterios de Evaluación:**

#### 1. **Diseño e Implementación de la Base de Datos**
- [ ] La base de datos está correctamente diseñada con tablas para usuarios, cuestionarios, preguntas y respuestas.
- [ ] La estructura de las tablas incluye claves primarias, relaciones entre tablas y validaciones adecuadas.
- [ ] Las consultas SQL funcionan correctamente para recuperar y almacenar datos del cuestionario.

#### 2. **Interfaz de Usuario**
- [ ] El diseño del formulario de cuestionario es claro, funcional y fácil de usar.
- [ ] Se utilizan elementos como botones de opción, menús desplegables y campos de texto para una experiencia de usuario intuitiva.
- [ ] La interfaz es completamente dinámica, cargando preguntas desde la base de datos.

#### 3. **Autenticación y Gestión de Sesiones**
- [ ] Los usuarios pueden registrarse, iniciar sesión y cerrar sesión correctamente.
- [ ] Las contraseñas están encriptadas antes de almacenarse en la base de datos.
- [ ] Las sesiones están bien gestionadas para rastrear el progreso del usuario en el cuestionario.

#### 4. **Lógica de Cuestionario**
- [ ] La aplicación valida que todas las preguntas sean respondidas antes de permitir el envío.
- [ ] Se calculan correctamente las puntuaciones basándose en las respuestas proporcionadas.
- [ ] Se proporciona retroalimentación inmediata al usuario indicando respuestas correctas e incorrectas.

#### 5. **Funcionalidad CRUD**
- [ ] Los administradores pueden añadir, editar y eliminar cuestionarios y preguntas desde un panel de gestión.
- [ ] Los cambios realizados en los cuestionarios se reflejan en tiempo real en la interfaz de usuario.

#### 6. **Seguridad**
- [ ] La aplicación está protegida contra inyecciones SQL y XSS.
- [ ] Los datos del usuario y los cuestionarios están gestionados de manera segura.
- [ ] Las cookies (si se utilizan) están configuradas correctamente para funciones como "Recordarme".

#### 7. **Pruebas y Depuración**
- [ ] Se realizaron pruebas exhaustivas para garantizar el correcto funcionamiento de las funcionalidades principales.
- [ ] Los errores encontrados durante el desarrollo fueron documentados y resueltos.

#### 8. **Extensibilidad y Características Adicionales**
- [ ] Opciones adicionales como temporizadores, aleatorización de preguntas o estadísticas están bien implementadas (opcional).
- [ ] La aplicación incluye características útiles como la posibilidad de guardar y continuar un cuestionario más tarde.

**Ponderación:**
- Diseño de la base de datos: 20%
- Interfaz de usuario: 15%
- Autenticación y sesiones: 15%
- Lógica del cuestionario: 20%
- CRUD y administración: 15%
- Seguridad: 10%
- Extensibilidad (opcional): 5%

