# Sistema de Modulación en Amplitud (AM)

## Descripción
Proyecto académico para la asignatura **Señales y Sistemas**. Implementa una simulación de
modulación en amplitud (AM) con Python y analiza la señal en los dominios del tiempo y la
frecuencia. También muestra los efectos de ruido gaussiano, distorsión por recorte y atenuación.

## Herramientas
- Python 3
- NumPy
- SciPy
- Matplotlib
- Google Colab

## Contenido
El cuaderno `Sistema_Modulacion_AM.ipynb` incluye:
1. Generación de la señal moduladora y la portadora.
2. Visualización de las señales de entrada.
3. Modulación AM convencional con portadora.
4. Análisis espectral mediante FFT.
5. Simulación de ruido gaussiano.
6. Simulación de distorsión por recorte.
7. Simulación de atenuación.

## Parámetros principales
- Frecuencia de muestreo: 100 kHz
- Frecuencia moduladora: 500 Hz
- Frecuencia portadora: 5 kHz
- Índice de modulación: 0.7 (70 %)
- Relación señal-ruido del ejemplo: 10 dB
- Factor de atenuación: 0.5 (50 %)

## Cómo ejecutar
1. Descarga `Sistema_Modulacion_AM.ipynb`.
2. Abre [Google Colab](https://colab.research.google.com/).
3. Selecciona **Archivo > Subir cuaderno** y carga el archivo.
4. Ejecuta las celdas en orden, desde la primera hasta la última.

Las bibliotecas NumPy, SciPy y Matplotlib suelen estar disponibles en el entorno estándar de Google Colab.

## Resultados esperados
Para los parámetros definidos, el espectro AM presenta componentes principales alrededor de:
- Banda lateral inferior: 4,500 Hz
- Portadora: 5,000 Hz
- Banda lateral superior: 5,500 Hz

El ruido añade fluctuaciones aleatorias; el recorte modifica los picos de la onda; y la atenuación reduce la amplitud sin alterar idealmente las frecuencias.

## Autor
Carlos Eduardo
## Asignatura
Señales y Sistemas
