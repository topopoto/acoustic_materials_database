# Parámetros del Modelo JCAL para Lana de Roca de Densidad Media

## Introducción
Para la simulación acústica y el diseño numérico de absorbentes microperforados parcialmente rellenos, el comportamiento de la capa porosa se modela con alta precisión mediante la formulación de Johnson-Champoux-Allard-Lafarge (JCAL). Este modelo requiere la definición de seis parámetros macroscópicos que gobiernan los fenómenos de disipación visco-inercial y térmica en el interior del medio poroelástico.

A continuación, se presentan los valores empíricos estandarizados para muestras de lana de roca con densidades comprendidas entre los **40 kg/m³** y **60 kg/m³**, basados en la caracterización y validación presentes en la literatura de referencia [1, 2].

## Parámetros Macroscópicos JCAL

*Tabla 1: Propiedades macroscópicas para el modelo JCAL (Lana de roca).*

| Parámetro | Símbolo | Rango Típico | Valor Sugerido | Unidades |
| :--- | :---: | :--- | :--- | :--- |
| Porosidad abierta | $\phi$ | 0.94 - 0.98 | 0.96 | - |
| Resistividad al flujo de aire | $\sigma$ | 13,500 - 30,000 | 13,500 | Pa·s/m² |
| Tortuosidad | $\alpha_\infty$ | 1.01 - 1.06 | 1.02 | - |
| Longitud característica viscosa | $\Lambda$ | 40 - 60 | 50 | μm |
| Longitud característica térmica | $\Lambda'$ | 100 - 150 | 120 | μm |
| Permeabilidad térmica estática | $k_0'$ | $1.0 \times 10^{-9}$ - $3.0 \times 10^{-9}$ | $1.5 \times 10^{-9}$ | m² |

---

## Referencias

1. Allard, J. F., & Atalla, N. (2009). *Propagation of Sound in Porous Media: Modelling Sound Absorbing Materials* (2nd ed.). John Wiley & Sons.
2. Olny, X., & Panneton, R. (2008). Acoustical determination of the parameters governing thermal dissipation in porous media. *The Journal of the Acoustical Society of America*, 123(2), 814–824. DOI: 10.1121/1.2821946