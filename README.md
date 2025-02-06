# Códigos del Taller
## Contenidos
* En este repositorio se encuentran los códigos propuestos en el taller [Programación paralela en Python](https://www.fdi.ucm.es/casas/actividad/2025-02-06-tallerparalelo/) de laXI Semana de la Informática
* Para poner a punto el taller se recomienda seguir los pasos de la sección [Setup del lab](#setup-del-lab)
* Los códigos que vamos a trabajar están disponibles en la [sección "Ejemplos"](#ejemplos), resumidamente trabajan algunos de los aspectos mostrados en la parte teórica:
    * Explotación de paralelismo multicore en Python mediante **NumPy**
    * Explotación de paralelismo heterogéneo (XPUs) mediante **Data Parallel Extension for Python**
    
# Setup del lab

## Transparencias
* Todo el material está disponible en el repositorio [github](https://github.com/garsanca/semanaInformatica2024)
    * Puede descargarse fácilmente clonando el repositorio ejecutando en un terminal el comando ```git clone https://github.com/garsanca/semanaInformatica2025.git```
* Además las transparencias del taller están disponible en el [directorio "transparencias"](transparencias/transparencias.pdf) 
* Los laboratorios se puedes desarrollar en el [Intel® Tiber™ AI Cloud](https://console.cloud.intel.com/)

## Guía Rápida para Acceder a Intel® Tiber™ AI Cloud

Intel® Tiber™ AI Cloud es una plataforma que ofrece recursos avanzados para el desarrollo y despliegue de aplicaciones de inteligencia artificial. A continuación, se detallan los pasos para acceder y comenzar a utilizar esta plataforma.

### 1. Registro en Intel® Tiber™ AI Cloud

1. **Visita el Sitio Web Oficial**:
   - Dirígete a [Intel® Tiber™ AI Cloud](https://console.cloud.intel.com/).

2. **Crear una Cuenta**:
   - Si no tienes una cuenta Intel, selecciona la opción para registrarte.
   - Completa el formulario de registro con tu información personal y profesional.
   - Verifica tu dirección de correo electrónico siguiendo las instrucciones enviadas a tu bandeja de entrada.

3. **Iniciar Sesión**:
   - Una vez registrada y verificada tu cuenta, inicia sesión con tus credenciales.

### 2. Navegación por el Panel de Control

- **Panel Principal**:
  - Al iniciar sesión, serás dirigido al panel principal donde podrás ver tus proyectos, recursos disponibles y estadísticas de uso.

- **Proyectos**:
  - Crea y gestiona tus proyectos de IA desde la sección de proyectos. Aquí puedes iniciar nuevos proyectos, acceder a los existentes y colaborar con otros usuarios.

- **Recursos**:
  - Accede a recursos como instancias de cómputo, almacenamiento y herramientas de desarrollo específicas para IA.

### 3. Soporte y Recursos Adicionales

- **Documentación**:
  - Accede a la documentación completa y guías de usuario en la sección de ayuda de la plataforma.

- **Soporte Técnico**:
  - Si encuentras problemas o necesitas asistencia, contacta al soporte técnico a través de los canales proporcionados en la plataforma.

- **Comunidad**:
  - Únete a la comunidad de desarrolladores de Intel para compartir conocimientos, obtener consejos y colaborar en proyectos de IA.

### 5. Cierre de Sesión

- Una vez que hayas terminado tu sesión, asegúrate de cerrar sesión para proteger tu cuenta. Puedes hacerlo seleccionando tu perfil en la esquina superior derecha y eligiendo "Cerrar Sesión".


## Ejemplos

Como parte de la exploración del **paralelismo en Python**, se han desarrollado ejercicios prácticos para evaluar el impacto del uso de **bibliotecas optimizadas en NumPy** y la **explotación del paralelismo** con **Data Parallel Extension for Python (DPEP)**.

### **Ejercicios Incluidos:**
1. **Ejercicios de NumPy con librerías optimizadas**:  
   - Cuadernos de Jupyter donde se evalúan las mejoras en rendimiento utilizando bibliotecas como **MKL (Intel Math Kernel Library)** y optimizaciones vectorizadas en NumPy.  
   - Ejercicio: [`numpy_ejercicio.ipynb`](Numpy/numpy_ejercicio.ipynb)

2. **Explotación de Paralelismo con DPNP**:  
   - Uso de **dpctl** y **DPNP** para acelerar computaciones en dispositivos paralelos.  
 
   - Ejercicio:  [`ejercicio_dpnp.ipynb`](DPEX/ejercicio_dpnp.ipynb)

### Objetivo de los Ejercicios
- Comparar el rendimiento entre **NumPy tradicional** y su ejecución en **entornos paralelizados** con DPNP.
- Medir la mejora en tiempos de cómputo al utilizar **paralelismo** y **aceleración con aceleradores con SYCL**.
- Explorar cómo **dpctl** gestiona dispositivos de cómputo de manera eficiente.

