# Implementación de una Estrategias de Control Estación Didáctica de Simulación UNEFA núcleo Maracay

Ultima version: [TN-BD-PTV-P-PID](https://github.com/jackestar/Planta-Didactica-de-Simulacion-OPTO22/releases/download/v1.0/TN-BD-PTV-P-PID.zip)

### Implementación de una Estrategia de Control Retroalimentado Todo-Nada para el Tanque de Calentamiento TQ3

* **Informe:** En revision.
* **Proyecto:** [TN-BD-PTV](./TN-BD-PTV)
* **Version OPTO22:**  9.4

### Implementación de una Estrategia de Control Retroalimentado Todo-Nada con Banda Diferencial para el Tanque de Calentamiento TQ3

* **Informe:** En revision.
* **Proyecto:** [TN-BD-PTV](./TN-BD-PTV)
* **Version OPTO22:**  9.4

### Implementación de una Estrategia de Control Retroalimentado Proporcional de Tiempo Variable Tanque de Calentamiento TQ3

* **Informe:** En revision.
* **Proyecto:** [TN-BD-PTV](./TN-BD-PTV)
* **Version OPTO22:**  9.4

### Implementación de una Estrategia de Control Retroalimentado Proporcional para Llenado Y Vaciado Tanque TQ2 Abierto

* **Informe:** En revision.
* **Proyecto:** [P-PID](./P-PID/)
* **Version OPTO22:**  9.4

### Implementación de una Estrategia de Control Retroalimentado PID para el Proceso de Suministro de Agua

* **Informe:** En revision.
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

## Cambios

* Apertura y cierre del panel: corregido
* Termo-neumático Principal (Breaker): Apaga todos los sistemas