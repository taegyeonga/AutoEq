# Bose SoundLink On-Ear

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -4.3dB
GraphicEQ: 21 -6.8; 23 -6.9; 25 -7.0; 28 -7.2; 31 -7.3; 34 -7.3; 37 -7.3; 41 -7.3; 45 -7.2; 49 -7.2; 54 -7.1; 60 -6.9; 66 -6.9; 72 -6.8; 79 -6.6; 87 -6.5; 96 -6.3; 106 -6.3; 116 -6.2; 128 -6.2; 141 -6.2; 155 -6.1; 170 -5.8; 187 -5.4; 206 -5.0; 227 -4.9; 249 -4.7; 274 -4.6; 302 -4.4; 332 -4.1; 365 -3.6; 402 -3.0; 442 -2.4; 486 -1.9; 535 -1.4; 588 -0.9; 647 -0.4; 712 -0.2; 783 -0.3; 861 -0.4; 947 -0.2; 1042 -0.0; 1146 0.1; 1261 0.2; 1387 0.0; 1526 -0.5; 1678 -0.9; 1846 -1.0; 2031 -1.4; 2234 -1.3; 2457 -0.7; 2703 -1.3; 2973 -1.4; 3270 -0.5; 3597 -0.6; 3957 -2.2; 4353 -2.8; 4788 -1.1; 5267 2.3; 5793 4.0; 6373 2.8; 7010 -0.1; 7711 -2.6; 8482 -5.3; 9330 -6.3; 10263 -4.0; 11289 -0.1; 12418 0.0; 13660 0.0; 15026 -0.2; 16529 -4.1; 18182 -6.1; 20000 -3.1
```

### HeSuVi
HeSuVi 2.0 ships with most of the pre-processed results. If this model can't be found in HeSuVi add
`Bose SoundLink On-Ear GraphicEQ.txt` to `C:\Program Files\EqualizerAPO\config\HeSuVi\eq\custom\` folder.
Set volume attenuation in the Connection tab for both channels to **-42**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Bose SoundLink On-Ear ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-5.0dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of **-4.9dB**.

| Type    | Fc       |    Q | Gain    |
|:--------|:---------|:-----|:--------|
| Peaking | 39 Hz    | 0.19 | -7.2 dB |
| Peaking | 263 Hz   | 0.98 | -1.9 dB |
| Peaking | 5962 Hz  | 6.03 | 5.5 dB  |
| Peaking | 9032 Hz  | 3.36 | -6.9 dB |
| Peaking | 18284 Hz | 1.92 | -6.8 dB |
| Peaking | 1334 Hz  | 0.94 | 1.5 dB  |
| Peaking | 1936 Hz  | 1.09 | -2.1 dB |
| Peaking | 4335 Hz  | 4.71 | -3.1 dB |
| Peaking | 5279 Hz  | 7.92 | 2.1 dB  |
| Peaking | 12958 Hz | 2.48 | 1.4 dB  |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/rtings/sbaf-serious/Bose%20SoundLink%20On-Ear/Bose%20SoundLink%20On-Ear.png)