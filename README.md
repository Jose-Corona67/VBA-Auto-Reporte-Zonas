# VBA-Auto-Reporte-Zonas

Aplicación desarrollada en VBA para Excel que automatiza la generación de reportes y gráficos de ventas por zona. El programa se conecta de forma segura a una base de datos externa (archivo Excel protegido con contraseña), maneja errores de conexión y proporciona una interfaz amigable para visualizar los resultados.

## Funcionalidad 

1.  Al ejecutarse, el programa intenta abrir la base de datos usando la última configuración válida.
2.  Si falla, informa al usuario si el problema es la **ubicación** o la **contraseña**.
3.  Ofrece la posibilidad de corregir la configuración errónea.
4.  Tras un acceso exitoso, procesa los datos y muestra el resumen y la gráfica en un UserForm.
5.  El UserForm incluye un botón "SALIR" para finalizar la aplicación.
