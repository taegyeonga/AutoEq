# Creative Sound Blaster EVO ZxR

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -6.1dB
GraphicEQ: 21 0.0; 23 2.3; 25 1.4; 28 0.3; 31 -0.7; 34 -1.5; 37 -2.3; 41 -3.1; 45 -3.9; 49 -4.5; 54 -5.2; 60 -5.9; 66 -6.5; 72 -7.0; 79 -7.4; 87 -8.0; 96 -8.4; 106 -8.9; 116 -9.4; 128 -9.8; 141 -10.1; 155 -10.5; 170 -10.7; 187 -10.8; 206 -10.8; 227 -10.7; 249 -10.6; 274 -10.4; 302 -10.6; 332 -10.4; 365 -9.6; 402 -8.7; 442 -7.7; 486 -6.5; 535 -5.0; 588 -3.5; 647 -1.7; 712 0.1; 783 1.3; 861 0.7; 947 0.4; 1042 0.1; 1146 0.7; 1261 1.3; 1387 2.6; 1526 3.8; 1678 4.8; 1846 5.6; 2031 6.0; 2234 6.0; 2457 6.0; 2703 5.3; 2973 2.5; 3270 0.9; 3597 1.7; 3957 0.0; 4353 -1.9; 4788 1.5; 5267 0.2; 5793 -0.1; 6373 -1.1; 7010 -1.5; 7711 -4.1; 8482 -5.8; 9330 -4.8; 10263 -3.1; 11289 -2.6; 12418 -2.0; 13660 -0.7; 15026 0.0
```

### HeSuVi
HeSuVi 2.0 ships with most of the pre-processed results. If this model can't be found in HeSuVi add
`Creative Sound Blaster EVO ZxR GraphicEQ.txt` to `C:\Program Files\EqualizerAPO\config\HeSuVi\eq\custom\` folder.
Set volume attenuation in the Connection tab for both channels to **-60**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Creative Sound Blaster EVO ZxR ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.5dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of **-6.4dB**.

| Type    | Fc      |     Q | Gain    |
|:--------|:--------|:------|:--------|
| Peaking | 20 Hz   |  2.01 | 4.5 dB  |
| Peaking | 135 Hz  |  0.48 | -9.5 dB |
| Peaking | 332 Hz  |  1.28 | -6.1 dB |
| Peaking | 2023 Hz |  1.23 | 6.7 dB  |
| Peaking | 8813 Hz |  1.94 | -5.8 dB |
| Peaking | 12 Hz   |  0.33 | -0.5 dB |
| Peaking | 489 Hz  |  3.93 | -1.2 dB |
| Peaking | 763 Hz  |  4.7  | 2.9 dB  |
| Peaking | 2598 Hz | 10.46 | 1.6 dB  |
| Peaking | 4223 Hz | 11.63 | -3.2 dB |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/rtings/avg/Creative%20Sound%20Blaster%20EVO%20ZxR/Creative%20Sound%20Blaster%20EVO%20ZxR.png)