# Audio-Technica ATH-MSR7NC

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -3.9dB
GraphicEQ: 21 0.0; 23 3.3; 25 3.0; 28 2.7; 31 2.4; 34 2.3; 37 2.3; 41 2.2; 45 2.2; 49 2.1; 54 2.0; 60 1.7; 66 1.3; 72 0.9; 79 0.5; 87 -0.0; 96 -0.5; 106 -1.0; 116 -1.3; 128 -1.6; 141 -1.7; 155 -1.9; 170 -1.9; 187 -1.8; 206 -1.6; 227 -1.3; 249 -1.0; 274 -0.5; 302 0.9; 332 2.1; 365 3.3; 402 3.2; 442 2.7; 486 2.1; 535 1.7; 588 1.4; 647 1.2; 712 1.0; 783 0.8; 861 0.6; 947 0.2; 1042 -0.1; 1146 -0.4; 1261 -1.0; 1387 -1.6; 1526 -2.8; 1678 -3.9; 1846 -4.8; 2031 -5.3; 2234 -4.7; 2457 -3.0; 2703 -2.0; 2973 -1.2; 3270 -0.3; 3597 1.3; 3957 1.6; 4353 -1.6; 4788 -1.3; 5267 1.0; 5793 3.0; 6373 2.8; 7010 0.4; 7711 -2.0; 8482 -3.1; 9330 -4.0; 10263 -3.2; 11289 -0.1; 12418 0.0
```

### HeSuVi
HeSuVi 2.0 ships with most of the pre-processed results. If this model can't be found in HeSuVi add
`Audio-Technica ATH-MSR7NC GraphicEQ.txt` to `C:\Program Files\EqualizerAPO\config\HeSuVi\eq\custom\` folder.
Set volume attenuation in the Connection tab for both channels to **-38**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Audio-Technica ATH-MSR7NC ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-4.0dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of **-3.6dB**.

| Type    | Fc      |    Q | Gain    |
|:--------|:--------|:-----|:--------|
| Peaking | 27 Hz   | 0.99 | 3.3 dB  |
| Peaking | 419 Hz  | 2.56 | 3.5 dB  |
| Peaking | 1980 Hz | 2.31 | -5.7 dB |
| Peaking | 6115 Hz | 4.39 | 4.1 dB  |
| Peaking | 9094 Hz | 2.77 | -4.4 dB |
| Peaking | 60 Hz   | 1.74 | 1.5 dB  |
| Peaking | 185 Hz  | 0.73 | -3.7 dB |
| Peaking | 299 Hz  | 0.57 | 2.1 dB  |
| Peaking | 3812 Hz | 6.69 | 3.0 dB  |
| Peaking | 4525 Hz | 7.08 | -2.6 dB |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/rtings/rtings/Audio-Technica%20ATH-MSR7NC/Audio-Technica%20ATH-MSR7NC.png)