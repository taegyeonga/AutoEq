# Apple EarPods

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -6.1dB
GraphicEQ: 21 0.0; 23 6.0; 25 6.0; 28 6.0; 31 6.0; 34 6.0; 37 6.0; 41 6.0; 45 6.0; 49 6.0; 54 6.0; 60 6.0; 66 6.0; 72 5.2; 79 3.9; 87 2.7; 96 1.6; 106 1.0; 116 0.6; 128 0.3; 141 0.3; 155 0.3; 170 0.4; 187 0.6; 206 0.7; 227 1.1; 249 1.1; 274 1.3; 302 1.4; 332 1.5; 365 1.7; 402 1.8; 442 2.0; 486 1.7; 535 1.7; 588 2.0; 647 1.8; 712 1.5; 783 1.3; 861 0.9; 947 0.4; 1042 -0.3; 1146 -1.0; 1261 -2.2; 1387 -4.0; 1526 -6.2; 1678 -8.2; 1846 -9.7; 2031 -10.5; 2234 -10.7; 2457 -9.9; 2703 -8.9; 2973 -6.3; 3270 -3.4; 3597 -1.5; 3957 -1.5; 4353 -3.5; 4788 -4.6; 5267 -5.2; 5793 -7.7; 6373 -6.9; 7010 -5.4; 7711 -5.7; 8482 -7.2; 9330 -8.3; 10263 -5.9; 11289 -0.3; 12418 0.0; 13660 0.0; 15026 -1.3; 16529 -0.1; 18182 0.0
```

### HeSuVi
HeSuVi 2.0 ships with most of the pre-processed results. If this model can't be found in HeSuVi add
`Apple EarPods GraphicEQ.txt` to `C:\Program Files\EqualizerAPO\config\HeSuVi\eq\custom\` folder.
Set volume attenuation in the Connection tab for both channels to **-61**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Apple EarPods ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-7.1dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of **-7.1dB**.

| Type    | Fc       |    Q | Gain     |
|:--------|:---------|:-----|:---------|
| Peaking | 37 Hz    | 0.66 | 7.0 dB   |
| Peaking | 658 Hz   | 0.75 | 2.6 dB   |
| Peaking | 2070 Hz  | 1.51 | -11.6 dB |
| Peaking | 7742 Hz  | 1.19 | -7.0 dB  |
| Peaking | 24000 Hz | 2.21 | -6.1 dB  |
| Peaking | 67 Hz    | 5.91 | 2.1 dB   |
| Peaking | 3700 Hz  | 7.32 | 3.1 dB   |
| Peaking | 5813 Hz  | 4.74 | -3.9 dB  |
| Peaking | 9560 Hz  | 3.45 | -9.5 dB  |
| Peaking | 9768 Hz  | 1.3  | 6.0 dB   |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/Apple%20EarPods/Apple%20EarPods.png)