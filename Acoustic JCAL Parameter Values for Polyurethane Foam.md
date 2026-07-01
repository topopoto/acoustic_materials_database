# Acoustic JCAL Parameter Values for Polyurethane Foam

The Johnson-Champoux-Allard-Lafarge (JCAL) model describes the acoustical behavior of rigid-frame porous materials using up to six characteristic (non-acoustic) parameters: open porosity ($\phi$), static airflow resistivity ($\sigma$ or $r$), tortuosity ($\alpha_\infty$), viscous characteristic length ($\Lambda$), thermal characteristic length ($\Lambda'$), and static thermal permeability ($\bar{k}'_o$). The first five constitute the classical Johnson-Champoux-Allard (JCA) model; the sixth is added in the JCAL extension to more accurately capture low-frequency thermal dissipation [1]-[3]. Below is a synthesis of experimentally determined and numerically predicted JCAL parameter values for various polyurethane (PU) foams, drawn from the literature.

---

## 1. Fully Reticulated (Open-Cell) Polyurethane Foams

Fully reticulated PU foams have all cell windows open (reticulation rate $Rw = 100\%$) and typically exhibit high porosity, low tortuosity, and relatively low airflow resistivity.

| Parameter | Symbol | Typical Range | Notes & References |
| :--- | :--- | :--- | :--- |
| Porosity | $\phi$ | 0.968–0.99 | Highly porous, typically ~0.98 [1], [4] |
| Airflow resistivity | $\sigma$ (N·s·m$^{-4}$) | 600–4,000 | Increases as cell size decreases (500–1,500 $\mu$m); e.g., ~1,677 at Cs $\approx$ 1,000 $\mu$m [1] |
| Tortuosity | $\alpha_\infty$ | ~1.05 | Approximately constant for fully reticulated foams [1], [4] |
| Viscous characteristic length | $\Lambda$ ($\mu$m) | 100–300 | $\Lambda \approx t/4$ for fibrous-like struts ($t =$ strut thickness); e.g., 128–240 $\mu$m for cell sizes 500–1,000 $\mu$m [1], [4] |
| Thermal characteristic length | $\Lambda'$ ($\mu$m) | 200–550 | $\Lambda' \approx 0.56 \cdot \text{Cs}$; e.g., 250–500 $\mu$m [1], [4] |
| Ratio $n = \Lambda'/\Lambda$ | $n$ | ~1.55 | Mean value for fully reticulated foams [1] |
| Static thermal permeability | $\bar{k}'_o$ ($\times 10^{-9}$ m$^2$) | ~4–40 | Typically larger than viscous permeability $k_o$; e.g., sample A: 24.3 $\times 10^{-9}$ m$^2$ [5] |

**Specific measured examples:** For a fully reticulated foam with cell size Cs = 673 $\mu$m, Doutres et al. [4] report $\phi = 0.956$, $\sigma = 3,490$ N·s·m$^{-4}$, $\alpha_\infty = 1.06$, $\Lambda = 187$ $\mu$m, $\Lambda' = 250$ $\mu$m. Ning et al. [5] provide additional examples: sample A ($\phi = 0.978$, $k_o = 6.78 \times 10^{-9}$ m$^2$, $\Lambda = 208.7$ $\mu$m, $\bar{k}'_o = 24.3 \times 10^{-9}$ m$^2$, $\Lambda' = 513$ $\mu$m, $\alpha_\infty = 1.05$); sample B ($\phi = 0.987$, $k_o = 9.77 \times 10^{-9}$ m$^2$, $\Lambda = 272$ $\mu$m, $\bar{k}'_o = 35.3 \times 10^{-9}$ m$^2$, $\Lambda' = 534.9$ $\mu$m); sample C ($\phi = 0.968$, $k_o = 4.57 \times 10^{-9}$ m$^2$, $\Lambda = 195.2$ $\mu$m, $\bar{k}'_o = 11.4 \times 10^{-9}$ m$^2$, $\Lambda' = 306.9$ $\mu$m).

---

## 2. Partially Reticulated Polyurethane Foams

Partially reticulated foams contain membranes that partially close cell windows (reticulation rate $Rw < 100\%$). 

| Parameter | Symbol | Typical Range | Notes & References |
| :--- | :--- | :--- | :--- |
| Tortuosity | $\alpha_\infty$ | - | Increases as Rw decreases; empirical relation: $\alpha_\infty = 1 + 0.5 \cdot (1 - Rw)$ [1] |
| Viscous characteristic length | $\Lambda$ ($\mu$m) | 20–200 | Decreases markedly with membranes; e.g., 24 $\mu$m for $Rw = 5\%$ [4] |
| Thermal characteristic length | $\Lambda'$ ($\mu$m) | 100–500 | Less affected than $\Lambda$; depends on both cell size and closed-pore content [1] |
| Ratio $n = \Lambda'/\Lambda$ | $n$ | 1.5–8.2 | Increases with closed-pore content; e.g., $n = 8.2$ for 80% closed pores [1] |
| Static thermal permeability | $\bar{k}'_o$ ($\times 10^{-9}$ m$^2$) | 1–40 | Generally decreases with closed-pore content [5] |

**Specific measured examples [4]:** Foam P2 ($Rw = 32\%$): $\phi = 0.958$, $\sigma = 17,440$ N·s·m$^{-4}$, $\alpha_\infty = 1.73$, $\Lambda = 46$ $\mu$m, $\Lambda' = 220$ $\mu$m. Foam P3 ($Rw = 5\%$): $\phi = 0.971$, $\sigma = 19,360$ N·s·m$^{-4}$, $\alpha_\infty = 2.16$, $\Lambda = 24$ $\mu$m, $\Lambda' = 458$ $\mu$m. Foam M10 ($Rw \approx 69\%$): $\phi = 0.982$, $\sigma = 3,670$ N·s·m$^{-4}$, $\alpha_\infty = 1.25$, $\Lambda = 240$ $\mu$m, $\Lambda' = 310$ $\mu$m.

---

## 3. Key Microstructure-Parameter Relationships

The following semi-empirical scaling laws link measurable microstructural features to JCAL parameters for high-porosity PU foams [1], [6], [7]:

* **Porosity:** $\phi = 1 - C**q(t/l)^2$, where $C**q \approx 0.785$ for a triangular-concave strut cross-section, $t =$ strut thickness, $l =$ strut length. For a cell-size-based (2-parameter) model: $\phi = 1 - C**q/B^2$, where $B = l/t \approx 3.78$ [6].
* **Airflow resistivity** (fully reticulated): $\sigma = (C**\sigma \cdot \eta)/(\phi \cdot Cs^2)$, where $\eta = 1.85 \times 10^{-5}$ Pa·s, $C**\sigma \approx 128 \cdot \alpha_\infty$, giving $\sigma \propto \text{Cs}^{-2}$ [6], [7].
* **Airflow resistivity** (partially reticulated): $\sigma = \sigma_0 \cdot [Rw]^{-1.1166}$, where $\sigma_0$ is the fully-reticulated value [1].
* **Thermal characteristic length:** $\Lambda' = [2Vf]/[As + (1 - Rw) \cdot Aw]$, where $Vf =$ fluid volume, $As =$ strut surface area, $Aw =$ window area [1], [6].
* **Viscous characteristic length:** For fully reticulated: $\Lambda = \Lambda'/1.55$. For partially reticulated: $\Lambda = \Lambda'/n$ where $n = 1.55 \cdot [Rw]^{-0.676}$ [1].

---

## 4. The Role of the Sixth Parameter (Static Thermal Permeability)

The JCAL model adds the static thermal permeability $\bar{k}'_o$ to improve predictions of the dynamic bulk modulus at low frequencies. For PU foams, $\bar{k}'_o$ is typically 2–5 times larger than the viscous static permeability $k_o = \eta/\sigma$ [2], [5]. Measured values range from ~ $1 \times 10^{-9}$ m$^2$ for highly resistive partially-reticulated foams to ~ $40 \times 10^{-9}$ m$^2$ for fully reticulated, large-cell foams [5]. The relationship $\bar{k}'_o \approx \phi \cdot \Lambda'^2 / 8$ (derived for idealized pore shapes) is only approximate for real PU foams; therefore, direct experimental determination via the three-microphone impedance-tube method is recommended when using the full JCAL model [2], [3].

---

## 5. Comparison with Other Porous Materials

For context, typical JCAL parameter values for melamine foam (an open-cell foam with ligament-like structure) include: $\phi \approx 0.984$, $\sigma \approx 9,365$ N·s·m$^{-4}$, $\alpha_\infty \approx 1.03$, $\Lambda \approx 116$ $\mu$m, $\Lambda' \approx 256$ $\mu$m, $\bar{k}'_o \approx 4.0 \times 10^{-9}$ m$^2$ in the uncompressed state [3]. PU foams span a much wider range of parameters, especially in airflow resistivity and tortuosity, due to the ability to control reticulation rate and cell size during manufacturing.

---

## References

1. O. Doutres, N. Atalla, and K. Dong, "Effect of the microstructure closed pore content on the acoustic behavior of polyurethane foams," *Journal of Applied Physics*, vol. 110, no. 6, Sep. 2011. DOI: 10.1063/1.3631021
2. O. Doutres, N. Atalla, and K. Dong, "A semi-phenomenological model to predict the acoustic behavior of fully and partially reticulated polyurethane foams," *Journal of Applied Physics*, vol. 113, no. 5, Feb. 2013. DOI: 10.1063/1.4789595
3. L. Lei, N. Dauchez, and J. D. Chazot, "Prediction of the six parameters of an equivalent fluid model for thermocompressed glass wools and melamine foam," *Applied Acoustics*, vol. 139, pp. 44–56, Oct. 2018. DOI: 10.1016/j.apacoust.2018.04.010
4. O. Doutres, M. Ouisse, N. Atalla, and M. Ichchou, "Impact of the irregular microgeometry of polyurethane foam on the macroscopic acoustic behavior predicted by a unit-cell model," *The Journal of the Acoustical Society of America*, vol. 136, no. 4, pp. 1666–1681, Oct. 2014. DOI: 10.1121/1.4895695
5. J. Ning, G. Zhao, and X. He, "Non-acoustical parameters and sound absorption characteristics of porous polyurethane foams," *Physics of Fluids*, vol. 31, no. 3, Mar. 2019. DOI: 10.1063/1.5079486
6. Y. Ji, S. Chen, and W. Zhu, "The effect of pore numbers in the cell walls of soybean oil polyurethane foam on sound absorption performance," *Applied Acoustics*, vol. 157, p. 107010, Jan. 2020. DOI: 10.1016/j.apacoust.2019.107010
7. H. Abdessalam, B. Abbès, F. Abbès, Y. Li, and Y.-Q. Guo, "Prediction of acoustic properties of polyurethane foams from the macroscopic numerical simulation of foaming process," *Applied Acoustics*, vol. 120, pp. 129–136, May 2017. DOI: 10.1016/j.apacoust.2017.01.021