# Skullcandy Hesh 3

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -1.9dB
GraphicEQ: 21 -11.5; 23 -11.1; 25 -10.7; 28 -10.1; 31 -9.4; 34 -8.7; 37 -8.0; 41 -7.2; 45 -6.5; 49 -5.8; 54 -5.1; 60 -4.6; 66 -4.5; 72 -4.8; 79 -5.4; 87 -6.4; 96 -7.3; 106 -7.9; 116 -8.0; 128 -7.9; 141 -7.4; 155 -6.6; 170 -5.8; 187 -4.8; 206 -3.7; 227 -2.4; 249 -1.3; 274 -0.4; 302 0.4; 332 1.0; 365 1.5; 402 1.8; 442 1.8; 486 1.6; 535 1.3; 588 1.1; 647 0.7; 712 0.3; 783 0.1; 861 0.0; 947 0.0; 1042 0.0; 1146 0.2; 1261 0.7; 1387 1.3; 1526 1.6; 1678 1.3; 1846 0.6; 2031 -0.4; 2234 -1.0; 2457 -1.6; 2703 -2.3; 2973 -3.4; 3270 -3.9; 3597 -3.9; 3957 -2.7; 4353 -3.2; 4788 -4.1; 5267 -4.6; 5793 -7.8; 6373 -9.1; 7010 -9.5; 7711 -8.3; 8482 -7.9; 9330 -6.7; 10263 -4.3; 11289 -3.1; 12418 -3.1; 13660 -5.7; 15026 -8.6; 16529 -6.1; 18182 -3.6; 20000 -11.8
```

### HeSuVi
HeSuVi 2.0 ships with most of the pre-processed results. If this model can't be found in HeSuVi add
`Skullcandy Hesh 3 GraphicEQ.txt` to `C:\Program Files\EqualizerAPO\config\HeSuVi\eq\custom\` folder.
Set volume attenuation in the Connection tab for both channels to **-19**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Skullcandy Hesh 3 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-2.2dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of **--0.1dB**.

| Type    | Fc       |    Q | Gain     |
|:--------|:---------|:-----|:---------|
| Peaking | 14 Hz    | 0.57 | -10.8 dB |
| Peaking | 29 Hz    | 0.78 | -3.8 dB  |
| Peaking | 124 Hz   | 1.4  | -7.8 dB  |
| Peaking | 6803 Hz  | 1.26 | -8.4 dB  |
| Peaking | 20854 Hz | 0.26 | -7.3 dB  |
| Peaking | 420 Hz   | 1.87 | 2.6 dB   |
| Peaking | 1551 Hz  | 3.06 | 2.1 dB   |
| Peaking | 3122 Hz  | 3.77 | -2.5 dB  |
| Peaking | 11830 Hz | 3.53 | 2.4 dB   |
| Peaking | 14921 Hz | 4.74 | -4.1 dB  |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/rtings/avg/Skullcandy%20Hesh%203/Skullcandy%20Hesh%203.png)