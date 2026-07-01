# Acoustic Biot-Allard Parameters for Basotect Foam

Basotect is a melamine resin open-cell foam widely used as a sound-absorbing material. Its acoustic behavior is most comprehensively described by the **Biot-Allard model** (also called the Biot-Johnson-Champoux-Allard or BJCA model), which combines Biot's theory of elastic wave propagation in fluid-saturated porous media with the Johnson-Champoux-Allard (JCA) description of the fluid phase. This model requires up to **nine material parameters**: five transport (fluid-phase) parameters, two elastic (solid-frame) parameters, the bulk density, and additional thermal permeability (sixth parameter) if the full JCAL model is used.

Below is a detailed summary of the measured and predicted Biot-Allard parameters for Basotect (melamine) foam, synthesized from experimental studies.

---

## 1. Fluid-Phase (Transport) Parameters

The Johnson-Champoux-Allard (JCA) / JCAL model describes visco-thermal dissipation in the pore fluid. The five core parameters, plus the optional static thermal permeability, have been extensively characterized for Basotect.

### 1.1 Porosity ($\phi$)

Basotect foam is highly porous. The porosity is typically estimated from the bulk density $\rho_1$ and the skeleton density $\rho_m$ ($\rho_m$ = 1570 kg/m³ for melamine) via:

$$\phi = 1 - \frac{\rho_1}{\rho_m}$$

For uncompressed Basotect TG with bulk density ~8.8–10.3 kg/m³, porosity values range from **0.992 to 0.995** [1], [7]. For compressed samples, porosity decreases following [1]:

$$\phi^{(n)} = 1 - n(1 - \phi^{(1)})$$

where $n$ is the compression ratio.

### 1.2 Static Airflow Resistivity ($\sigma$)

Flow resistivity is one of the most influential parameters for sound absorption [5]. For uncompressed Basotect TG (bulk density ~8.8 kg/m³), the flow resistivity is approximately **6200 Pa·s/m²** [1]. For Basotect samples with higher bulk density, values increase to **10,500–17,500 Pa·s/m²** [7]. For compressed samples, values can reach **122,325 Pa·s/m²** at a compression ratio $n \approx 6.6$ [1], [2].

Kino et al. [1] established the following empirical relationship for Basotect TG:

$$\sigma_{\text{Kino(BTG)}} d_{\text{Kino(BTG)}}^2 \rho_1^{-1.53} = 8.0 \times 10^{-9}$$

where $d$ is the fiber-equivalent diameter (~5.5–6.5 μm) and $\rho_1$ is the bulk density.

### 1.3 Tortuosity ($\alpha_\infty$)

Tortuosity describes the sinuosity of the pore paths. For uncompressed Basotect TG (sample 61), the measured tortuosity is **1.0101** [1]. For the Illtec melamine foam, values are similarly low (~1.0053–1.0090) [7]. These low values indicate a very open, straight-pore structure. Upon compression, tortuosity increases gradually, reaching up to **1.073** at high compression rates [1], [2].

### 1.4 Viscous Characteristic Length ($\Lambda$)

The viscous characteristic length relates to the smaller pore dimensions where viscous dissipation dominates. For uncompressed Basotect TG (bulk density 8.77 kg/m³), $\Lambda \approx$ **271 μm** [1]. For Illtec melamine foam samples (bulk density 10.3 kg/m³), $\Lambda \approx$ **199 μm** [7]. Under compression, $\Lambda$ decreases approximately as [1], [3]:

$$\Lambda^{(n)} = \frac{\Lambda^{(1)}}{n} + \frac{a}{2} \left( \frac{1}{n} - 1 \right)$$

where $a$ is the fiber-equivalent radius (~3 μm). At $n \approx 6.6$, $\Lambda$ can drop to ~37–48 μm [1], [3].

### 1.5 Thermal Characteristic Length ($\Lambda'$)

The thermal characteristic length is related to the total surface-to-volume ratio of the pores. For uncompressed Basotect, $\Lambda'$ is approximately twice the viscous characteristic length: $\Lambda' \approx$ **572 μm** for Basotect TG [1]. For Illtec foam, $\Lambda' \approx$ **460 μm** [7]. The ratio $\Lambda'/\Lambda$ generally satisfies $\Lambda'/\Lambda \geq 2$ [1], [6].

### 1.6 Static Thermal Permeability ($k_0'$) (JCAL model)

The full six-parameter JCAL model includes static thermal permeability. For uncompressed melamine foam, $k_0'$ is on the order of **4.0–6.3 $\times 10^{-9}$ m²** [3]. Under compression, it decreases according to a relationship derived from fiber-array models [3].

---

## 2. Summary of Measured Values for Uncompressed Basotect TG

| Parameter | Symbol | Unit | Value (Ref. Sample 61) [1] |
| :--- | :--- | :--- | :--- |
| Bulk density | $\rho_1$ | kg/m³ | 8.77 |
| Surface density | - | g/m² | 173 |
| Porosity | $\phi$ | - | 0.9944 |
| Flow resistivity | $\sigma$ | Pa·s/m² | 6,197 |
| Tortuosity | $\alpha_\infty$ | - | 1.0101 |
| Viscous char. length | $\Lambda$ | μm | 271 |
| Thermal char. length | $\Lambda'$ | μm | 572 |

For Illtec melamine foam (Sample 51, uncompressed) [1]:

| Parameter | Value |
| :--- | :--- |
| $\rho_1$ | 12.39 kg/m³ |
| $\phi$ | 0.9921 |
| $\sigma$ | 10,943 Pa·s/m² |
| $\alpha_\infty$ | 1.0090 |
| $\Lambda$ | 230 μm |
| $\Lambda'$ | 460 μm |

---

## 3. Elastic (Solid-Frame) Parameters

For poroelastic modeling under the full Biot model, the elastic properties of the melamine skeleton are required. Measurements show that Basotect foam is **orthotropic** (not simply isotropic) [4].

### 3.1 Young's Modulus ($E$)

The Young's modulus of melamine foam is strongly dependent on density and direction. For a typical uncompressed melamine foam of bulk density ~9–10 kg/m³, static Young's moduli in the compressional directions are on the order of **100–200 kPa** [6], [4]. Specifically, Cuenca et al. [6] determined the compressional moduli (elements of the Hooke's matrix) for melamine foam:

* $H_{11} \approx$ 1.2–1.3 MPa (highest stiffness direction)
* $H_{22} \approx$ 1.2–1.4 MPa
* $H_{33} \approx$ 3.7–3.8 MPa (lowest stiffness in the rise direction)

From a dynamic characterization, the Young's modulus for melamine foam used in impedance tube inverse methods is approximately **190–200 kPa** [6].

### 3.2 Poisson's Ratio ($\nu$)

Poisson's ratio for open-cell melamine foams is typically in the range **0.3–0.44** [6]. For the purposes of one-dimensional impedance tube modeling, it is often set to zero because the lateral deformation cannot be independently resolved from a single normal-incidence measurement [6].

### 3.3 Loss Factor ($\eta$)

The structural damping of melamine foam is typically $\eta =$ **0.04–0.12** [6]. The specific value depends on frequency and temperature.

### 3.4 Bulk Density ($\rho_1$)

The bulk density of Basotect foam is typically **8–12 kg/m³** for uncompressed commercial grades [1], [7]. Under thermo-compression, it scales linearly with compression ratio: $\rho_1^{(n)} = n \cdot \rho_1^{(1)}$ [3].

---

## 4. Sensitivity and Model Selection

### 4.1 Which Parameters Matter Most?

A global sensitivity analysis by Ouisse et al. [5] using the Champoux-Allard (five-parameter) and Biot-Allard (nine-parameter) models revealed a strong frequency-dependent hierarchy:

* **Flow resistivity ($\sigma$)** and **viscous characteristic length ($\Lambda$)** are the most influential parameters across the audio frequency range for sound absorption.
* **Porosity ($\phi$)** has limited impact on the absorption coefficient except at very low frequencies.
* **Tortuosity ($\alpha_\infty$)** plays a secondary but non-negligible role, particularly around mid-frequencies.
* **Elastic parameters ($E$, $\nu$, $\eta$)** become critically important in frequency regions where the frame resonance (fluid-structure coupling) occurs. For standard 25–30 mm thick melamine foam, this is typically around **1350–1500 Hz** [6].

### 4.2 Rigid-Frame vs. Elastic-Frame Models

For many applications, Basotect can be modeled with the **rigid-frame Johnson-Champoux-Allard model** (5 parameters), as the frame motion is negligible at low frequencies or when the material is thick enough [1], [7]. However, when the foam is used in thin layers or when structural coupling is important (e.g., in sandwich panels), the full **Biot-Allard model** (9 parameters including $E$, $\nu$, $\eta$, $\rho_1$) is required to capture the additional damping caused by the frame resonance [6], [5].

### 4.3 Compression Effects

Basotect foams are often thermo-compressed in automotive applications. The compression model proposed by Lei et al. [3] provides a comprehensive framework to predict all six JCAL parameters at any compression rate $n$ from the initial (uncompressed) values. A key finding is that the **fiber/ligament orientation changes under compression**, significantly affecting $\sigma$ and $\Lambda$ but having weaker effects on $\alpha_\infty$ [3].

### 4.4 Cross-sectional Pore Shape Factors

The Johnson-Allard model introduces cross-sectional shape factors $c$ and $c'$. For Basotect TG, these are approximately **$c \approx$ 0.25–0.57** and **$c' \approx$ 0.24–0.40**, which are significantly lower than those for glass wool ($c \approx$ 0.71–0.78) [7]. This explains how melamine foam achieves high flow resistivity despite having large characteristic lengths [7].

---

## 5. Typical Complete Parameter Set for Biot-Allard Modeling

Based on the reviewed literature, a representative complete set of Biot-Allard parameters for **uncompressed Basotect TG melamine foam** (bulk density $\approx$ 8.8 kg/m³) is compiled below:

| Parameter | Symbol | Unit | Typical Value | Source |
| :--- | :--- | :--- | :--- | :--- |
| Porosity | $\phi$ | - | 0.994 | [1] |
| Flow resistivity | $\sigma$ | Pa·s/m² | 6,200–13,100 | [1], [7] |
| Tortuosity | $\alpha_\infty$ | - | 1.005–1.010 | [1], [7] |
| Viscous char. length | $\Lambda$ | μm | 200–270 | [1], [7] |
| Thermal char. length | $\Lambda'$ | μm | 450–570 | [1], [7] |
| Static thermal perm. | $k_0'$ | $\times 10^{-9}$ m² | 4.0–6.3 | [3] |
| Bulk density | $\rho_1$ | kg/m³ | 8–12 | [1] |
| Young's modulus | $E$ | kPa | 190–200 | [6] |
| Poisson's ratio | $\nu$ | - | 0 (or 0.3–0.44) | [6] |
| Loss factor | $\eta$ | - | 0.04–0.05 | [6] |

---

## 6. Recent Advances in Parameter Estimation

Cuenca et al. [6] developed a powerful multi-observation inverse method that simultaneously estimates all nine Biot-Allard parameters (plus thickness) from two impedance tube measurements (rigid-backed and coupled to an expansion chamber). Applied to a melamine foam sample, this method yielded:

* $h =$ 23.14 mm, $\rho_1 =$ 11.87 kg/m³
* $\phi =$ 1.00 (near unity), $\sigma =$ 18.6 kN·s/m⁴, $\alpha_\infty =$ 1.001
* $\Lambda =$ 69.5 μm, $\Lambda' =$ 158.7 μm
* $E =$ 194 kPa, $\eta =$ 4.6%

These values demonstrate the consistency of the Biot-Allard framework when properly applied to melamine foam characterization.

---

## References

1. N. Kino, T. Ueno, Y. Suzuki, and H. Makino, "Investigation of non-acoustical parameters of compressed melamine foam materials," *Applied Acoustics*, vol. 70, no. 4, pp. 595–604, Apr. 2009. DOI: 10.1016/j.apacoust.2008.07.002
2. N. Kino, "A comparison of two acoustical methods for estimating parameters of glass fibre and melamine foam materials," *Applied Acoustics*, vol. 73, no. 6–7, pp. 590–603, Jun. 2012. DOI: 10.1016/j.apacoust.2011.12.007
3. L. Lei, N. Dauchez, and J. D. Chazot, "Prediction of the six parameters of an equivalent fluid model for thermocompressed glass wools and melamine foam," *Applied Acoustics*, vol. 139, pp. 44–56, Oct. 2018. DOI: 10.1016/j.apacoust.2018.04.010
4. C. Van der Kelen, J. Cuenca, and P. Göransson, "A method for the inverse estimation of the static elastic compressional moduli of anisotropic poroelastic foams -- With application to a melamine foam," *Polymer Testing*, vol. 43, pp. 123–130, May 2015. DOI: 10.1016/j.polymertesting.2015.03.006
5. M. Ouisse, M. Ichchou, S. Chedly, and M. Collet, "On the sensitivity analysis of porous material models," *Journal of Sound and Vibration*, vol. 331, no. 24, pp. 5292–5308, Nov. 2012. DOI: 10.1016/j.jsv.2012.07.018
6. J. Cuenca, P. Göransson, L. De Ryck, and T. Lähivaara, "Deterministic and statistical methods for the characterisation of poroelastic media from multi-observation sound absorption measurements," *Mechanical Systems and Signal Processing*, vol. 163, p. 108186, Jan. 2022. DOI: 10.1016/j.ymssp.2021.108186
7. N. Kino and T. Ueno, "Comparisons between characteristic lengths and fibre equivalent diameters in glass fibre and melamine foam materials of similar flow resistivity," *Applied Acoustics*, vol. 69, no. 4, pp. 325–331, Apr. 2008. DOI: 10.1016/j.apacoust.2006.11.008