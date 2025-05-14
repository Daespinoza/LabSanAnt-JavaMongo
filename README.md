# LabSanAnt-JavaMongo

**LabSanAnt-JavaMongo** es una aplicación de escritorio desarrollada en **Java** con **MongoDB**, orientada a digitalizar, centralizar y estandarizar los procesos internos del *Laboratorio Clínico San Antonio*. El sistema busca eliminar el uso de papel y facilitar la gestión clínica, administrativa y contable del laboratorio.

## 🎯 Objetivo

Digitalizar procesos como:
- Registro de pacientes
- Solicitud de exámenes clínicos
- Registro y gestión de análisis químicos
- Emisión de resultados
- Facturación e informes contables

Todo desde una aplicación de escritorio amigable y fácil de usar, compatible con sistemas Windows.

## 🧩 Tecnologías Usadas

- Java (IntelliJ IDEA Community)
- MongoDB (local)
- Interfaz gráfica (JavaFX o Swing, según documentación disponible)
- PDF y reportes exportables
- Sistema empaquetado como `.jar` y con instalador opcional

## 🧱 Estructura de Datos

Las principales entidades del sistema serán:
- `Empleado`
- `Acceso`
- `Paciente`
- `Solicitud`
- `Factura`
- `Análisis`
- `Resultados`

## 👥 Roles de Usuario

- **Administrador**: Acceso completo, gestión de usuarios y configuración.
- **Especialista**: Accede a toda la información y puede llenar resultados.
- **Asistente**: Puede registrar pacientes, crear solicitudes y descargar resultados.

## 🔒 Seguridad

- Login por usuario y contraseña.
- Cifrado de contraseñas en la base de datos.
- Control de acceso según roles.

## 📊 Contabilidad Sencilla

- Registro de ingresos o gastos
- Generación de informes mensuales, quincenales y anuales
- Visualización de gráficos
- Exportación en PDF

## 📦 Instalación y Despliegue

- Aplicación instalada localmente en un equipo Windows
- MongoDB local incluido en el instalador
- Exportaciones organizadas por carpeta
- Configuración inicial guiada al ejecutar por primera vez

---

© Proyecto para la digitalización del Laboratorio Clínico San Antonio.
