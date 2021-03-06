# Sennheiser HD 471i

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -6.1dB
GraphicEQ: 21 0.0; 23 0.5; 25 0.2; 28 -0.0; 31 -0.2; 34 -0.4; 37 -0.4; 41 -0.4; 45 -0.4; 49 -0.3; 54 -0.2; 60 0.0; 66 0.3; 72 0.5; 79 0.7; 87 0.9; 96 0.9; 106 1.7; 116 2.5; 128 1.3; 141 -1.5; 155 -1.6; 170 -1.2; 187 -2.6; 206 -2.3; 227 -2.5; 249 -2.5; 274 -2.1; 302 -1.7; 332 -1.2; 365 -0.4; 402 -0.2; 442 -0.4; 486 -0.4; 535 -0.4; 588 -0.4; 647 -0.5; 712 -0.7; 783 -0.3; 861 -0.1; 947 -0.0; 1042 0.2; 1146 -0.1; 1261 -0.2; 1387 -0.5; 1526 -1.1; 1678 -1.0; 1846 -0.5; 2031 0.8; 2234 2.8; 2457 3.1; 2703 4.3; 2973 4.9; 3270 5.3; 3597 5.4; 3957 6.0; 4353 6.0; 4788 6.0; 5267 6.0; 5793 6.0; 6373 5.5; 7010 2.5; 7711 0.3; 8482 0.0
```

### HeSuVi
HeSuVi 2.0 ships with most of the pre-processed results. If this model can't be found in HeSuVi add
`Sennheiser HD 471i GraphicEQ.txt` to `C:\Program Files\EqualizerAPO\config\HeSuVi\eq\custom\` folder.
Set volume attenuation in the Connection tab for both channels to **-60**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Sennheiser HD 471i ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.3dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of **-6.7dB**.

| Type    | Fc      |    Q | Gain    |
|:--------|:--------|:-----|:--------|
| Peaking | 14 Hz   | 1.68 | 1.1 dB  |
| Peaking | 114 Hz  | 3.16 | 3.5 dB  |
| Peaking | 202 Hz  | 1.06 | -2.8 dB |
| Peaking | 1638 Hz | 2.89 | -2.6 dB |
| Peaking | 4109 Hz | 0.96 | 6.7 dB  |
| Peaking | 81 Hz   | 4.7  | 0.6 dB  |
| Peaking | 2819 Hz | 3.05 | 1.1 dB  |
| Peaking | 3780 Hz | 2.07 | -0.9 dB |
| Peaking | 6205 Hz | 2.85 | 4.2 dB  |
| Peaking | 7668 Hz | 1.59 | -3.1 dB |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/Sennheiser%20HD%20471i/Sennheiser%20HD%20471i.png)