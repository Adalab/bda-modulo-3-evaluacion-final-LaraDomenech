# Módulo 3: Ejercicio de Evaluación Final Lara Domènech

📖 Este repositorio recoge el trabajo completo de la Evaluación Final del Módulo 3. El examen está centrado en el análisis del comportamiento de los clientes dentro de un programa de fidelidad de una aerolínea.

Se utilizan dos fuentes de datos:
  - *Customer Flight Activity*: Registros mensuales de actividad de vuelo por cliente. Incluye el número de vuelos reservados, número de vuelos que ha viajado con acompañantes, el total de vuelos que ha realizado el cliente, la distancia volada, los puntos acumulados y       redimidos, y costos asociados a los puntos redimidos.
  - *Customer Loyalty History*: Historial de fidelización y datos demográficos. Incluye el país del cliente, la província, la ciudad, el código postal, el género, el nivel educativo, el salario, el estado civil, y detalles sobre sus características en el programa de          fidelidad (como el tipo de tarjeta, valor de vida del cliente, y fechas de inscripción y cancelación).

🧪 Criterios de evaluación:

  - Análisis Exploratorio de los datos
  - Gestión de nulos
  - Visualización de datos con matplotlib y seaborn
  - Estadística descriptiva e inferencial
  - README
  - Buenas prácticas en el código
  - Control de versiones Git

🛠️ Herramientas:
  - Lenguaje: Python
  - Entorno: Jupyter Notebook
  - Librerías:
      - Pandas para manipulación de datos
      - NumPy para operaciones numéricas
      - Matplotlib y Seaborn para visualización
      - Scipy para análisis estadístico

🚀 Instrucciones de ejecución:
  - Clonar el repositorio.
  - Cargar los CSV
  - Configurar variables
  - Ejecutar cada fase:
      - Limpieza
      - Visualización
      - Esatdística

📝 Descripción de las fases:

  - Fase 1 (Limpieza): carga de datos, tratamiento de nulos, conversión de fechas, duplicados y creación de nuevos campos.

  - Fase 2 (Visualización): series temporales, scatter, distribuciones, boxplots, etc.

  - Fase 3 (Estadística): test de normalidad, homogeneidad de varianzas, Kruskal-Wallis, Mann-Whitney U, etc.

📊 Conclusiones:

  - Correlación positiva entre distancia de vuelo y puntos acumulados.
  - Tendencias estacionales en las reservas de los vuelos.
  - Diferencias significativas en reservas de vuelos según el nivel educativo del cliente (p<0.05).
