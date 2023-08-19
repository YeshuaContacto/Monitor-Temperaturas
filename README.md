# Monitor de Temperaturas con PySide6 y PyQtGraph - YeshuaContacto  
[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white&labelColor=101010)]()
[![PySide6](https://img.shields.io/badge/PySide6-Qt-4A90E2?style=for-the-badge&logo=qt&logoColor=white&labelColor=101010)](https://wiki.qt.io/Qt_for_Python)
[![PyQtGraph](https://img.shields.io/badge/PyQtGraph-3F7F7F?style=for-the-badge&logo=Python&logoColor=white&labelColor=101010)](http://www.pyqtgraph.org/)

![[https://github.com/YeshuaContacto](https://github.com/YeshuaContacto)](./Monitor-Temperaturas.jpg)


Este programa crea una interfaz gráfica para monitorear y mostrar temperaturas utilizando la biblioteca PySide6 para la interfaz de usuario y PyQtGraph para los gráficos.

## Funcionalidad

- Crea una ventana de aplicación con elementos de UI.
- Permite agregar nuevas lecturas de temperatura manualmente o automáticamente.
- Muestra gráficos en tiempo real de las temperaturas registradas.

## Características Principales

- Definición de la clase `MainWindow`, que hereda de `QtWidgets.QMainWindow` y `Ui_MainWindow`.
- Inicialización de sondas con nombres, valores, colores y símbolos.
- Combobox para seleccionar la sonda.
- Creación y configuración de gráficos utilizando PyQtGraph.
- Manejo de señales para los botones de adición de lecturas.
- Método `construirGrafico` para configurar la apariencia del gráfico.
- Método `nuevaLectura` para agregar nuevas lecturas a las sondas.

## Ejecución

- Inicialización de la aplicación y ventana principal.
- Visualización de la ventana de la aplicación.

## Uso

1. Selecciona una sonda desde el combobox.
2. Ingresa una temperatura manualmente y presiona el botón "Agregar Lectura" para agregar una nueva lectura.
3. Opcionalmente, presiona el botón "Generar Automáticamente" para agregar lecturas aleatorias a todas las sondas.

---

Este resumen proporciona una visión general de la funcionalidad y características del programa. Para obtener más detalles, consulta el código fuente completo.
