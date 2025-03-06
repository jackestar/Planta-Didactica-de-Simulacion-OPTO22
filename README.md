
<h1 align="center">Implementación de una Estrategias de Control Estación Didáctica de Simulación UNEFA núcleo Maracay</h1>

Este repositorio contiene la implementación de diversas estrategias de control aplicadas a una planta piloto utilizando la suite OPTO22. El proyecto incluye los archivos de simulación correspondientes y los informes técnicos que describen el funcionamiento de cada una de las estrategias implementadas.

El proyecto se centra en la aplicación de estrategias de control en una planta piloto previamente caracterizada. Cada implementación sigue un proceso estructurado que incluye las siguientes etapas:

* Acondicionamiento Previo: Preparación y configuración de los componentes necesarios para garantizar el correcto funcionamiento de la planta piloto.

* Programación de la Estrategia: Desarrollo y codificación de las estrategias de control utilizando la suite OPTO22 (OptoScript).

* Diseño del HMI (Interfaz Hombre-Máquina): Creación de interfaces gráficas que permiten la interacción y el monitoreo de la planta piloto.

---

*Ultima version*: [TN-BD-PTV-P-PID](https://github.com/jackestar/Planta-Didactica-de-Simulacion-OPTO22/releases/download/v1.0/TN-BD-PTV-P-PID.zip)

---

## Implementaciones

### Implementación de una Estrategia de Control Retroalimentado Todo-Nada para el Tanque de Calentamiento TQ3

* **Informe:** [link](https://drive.google.com/file/d/1UkRAomM8qv7oFxNAX9hCHUneRsfY2LQu/view)
* **Proyecto:** [TN-BD-PTV](./TN-BD-PTV)
* **Version OPTO22:**  9.4

### Implementación de una Estrategia de Control Retroalimentado Todo-Nada con Banda Diferencial para el Tanque de Calentamiento TQ3

* **Informe:** [link](https://drive.google.com/file/d/14jTMw2_LIm2APT3jVAX86LZtf5JLbdOO/view)
* **Proyecto:** [TN-BD-PTV](./TN-BD-PTV)
* **Version OPTO22:**  9.4

### Implementación de una Estrategia de Control Retroalimentado Proporcional de Tiempo Variable Tanque de Calentamiento TQ3

* **Informe:** [link](https://drive.google.com/file/d/1UfsR6Gq44Tz98AokPwjAVX1wIHhMHM5m/view)
* **Proyecto:** [TN-BD-PTV](./TN-BD-PTV)
* **Version OPTO22:**  9.4

### Implementación de una Estrategia de Control Retroalimentado Proporcional para Llenado Y Vaciado Tanque TQ2 Abierto

* **Informe:** [link](https://drive.google.com/file/d/1cQZHIHq5xqoG1s9XL1iouH1-N-3KECh8/view)
* **Proyecto:** [P-PID](./P-PID/)
* **Version OPTO22:**  9.4

### Implementación de una Estrategia de Control Retroalimentado PID para el Proceso de Suministro de Agua

* **Informe:** [link](https://drive.google.com/file/d/1fldvGnJ3Glw2PWX88tps7nLcQ3j9l7xC/view?usp=drive_link)
* **Proyecto:** [P-PID](./P-PID/)
* **Version OPTO22:**  9.4

## Variables

`status_alarmas`
```
0
1 TQ1 < min
2 TQ2 < min
3 B100
4
5 TQ2 > max
6 Sobre dimensionado Estrategia
```

`E_Llenado_Force`
```
0 
1 IN
2 Out
3
4 TQ2
5 TQ1
```

`Interruptores`
```
0 Main
```

## Nomenclatura

### Estrategias

* **TN** Todo-Nada (On-Off)
* **BD** Banda Diferencial
* **PTV** Proporcional de Tiempo Variable
* **P** Proporcional
* **PD** Proporcional Derivativo
* **PI** Proporcional Integral
* **PID** Proporcional Integral Derivativo

## Cambios

* Apertura y cierre del panel: corregido
* Termo-neumático Principal (Breaker): Apaga todos los sistemas