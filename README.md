
# Control_MPC_en_Simulacion_de_Epidemias  
---
Este repositorio contiene el código y los resultados asociados al uso del **Control Predictivo Basado en Modelos (MPC)** aplicado en simulaciones de epidemias utilizando un modelo **SIR**. El objetivo del proyecto es **ayudar en la investigación de control epidemiológico** mediante la experimentación con diferentes configuraciones de control y funciones de costo, ofreciendo un ejemplo práctico del uso de MPC en problemas de salud pública.

---

## Contenido del Repositorio  

- **`MPC-SIR.ipynb`**: Contiene el código principal donde se realizan las simulaciones del modelo SIR con control MPC.
- **`/Exp MPC/`**: Carpeta que almacena gráficos de los experimentos realizados anteriormente. Cada gráfico refleja los resultados de diferentes configuraciones del MPC, como horizontes de control y predicción, o el uso de distintas funciones de costo.

---

## Requisitos  

Este proyecto utiliza **Python 3.12** y las siguientes bibliotecas:  
- **Numpy**  
- **Matplotlib**  
- **Math**  
- **Scipy** (específicamente, `odeint` y `minimize`)  

Asegúrate de tenerlas instaladas mediante:  
```bash
pip install numpy matplotlib scipy
```

---

## Instrucciones de Uso  

1. **Ejecutar el notebook**:  
   El código se encuentra en formato **Jupyter Notebook**. No se necesita instalación adicional más allá de las dependencias.

2. **Explorar los resultados previos**:  
   Los gráficos de los experimentos realizados con diferentes configuraciones se encuentran en la carpeta **`/graficas/`**. Estos muestran cómo cambian los resultados según los parámetros y funciones de costo seleccionados.

---

## Licencia  

Este proyecto se distribuye bajo la licencia **MIT**. Consulta el archivo `LICENSE` para más detalles.

---

## Contacto  

Si tienes preguntas o comentarios sobre este proyecto, no dudes en ponerte en contacto:  
**Emiliano Viaña** – [jose.viana@alumno.buap.mx](mailto:jose.viana@alumno.buap.mx)

---
