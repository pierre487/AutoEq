# Grado GW100
See [usage instructions](https://github.com/jaakkopasanen/AutoEq#usage) for more options and info.

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
GraphicEQ: 21 -2.1; 23 -3.9; 25 -5.4; 28 -7.3; 31 -8.7; 34 -9.4; 37 -9.7; 41 -9.5; 45 -8.9; 49 -8.3; 54 -7.9; 60 -8.0; 66 -8.3; 72 -8.4; 79 -8.4; 87 -8.5; 96 -8.8; 106 -9.2; 116 -9.7; 128 -10.3; 141 -10.9; 155 -11.4; 170 -11.9; 187 -11.9; 206 -11.6; 227 -11.2; 249 -10.4; 274 -9.4; 302 -8.8; 332 -8.4; 365 -7.8; 402 -7.5; 442 -7.2; 486 -6.9; 535 -6.6; 588 -6.0; 647 -5.3; 712 -4.6; 783 -3.9; 861 -3.3; 947 -2.8; 1042 -2.4; 1146 -2.3; 1261 -2.6; 1387 -3.1; 1526 -4.2; 1678 -5.8; 1846 -9.4; 2031 -12.2; 2234 -11.3; 2457 -8.0; 2703 -5.2; 2973 -3.8; 3270 -3.1; 3597 -3.3; 3957 -3.6; 4353 -1.9; 4788 -0.5; 5267 -0.5; 5793 -0.5; 6373 -2.4; 7010 -4.1; 7711 -6.2; 8482 -10.5; 9330 -12.1; 10263 -7.1; 11289 -6.5; 12418 -6.5; 13660 -6.5; 15026 -6.5; 16529 -6.5; 18182 -6.5; 20000 -6.5
```

### HeSuVi
HeSuVi 2.0 ships with most of the pre-processed results. If this model can't be found in HeSuVi add
`Grado GW100 GraphicEQ.txt` to `C:\Program Files\EqualizerAPO\config\HeSuVi\eq\custom\` folder.

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Grado GW100 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.5dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of **-6.1dB**.

| Type    | Fc      |     Q | Gain     |
|:--------|:--------|:------|:---------|
| Peaking | 180 Hz  |  0.72 | -5.3 dB  |
| Peaking | 1244 Hz |  0.78 | 4.9 dB   |
| Peaking | 2062 Hz |  3.18 | -10.0 dB |
| Peaking | 5332 Hz |  1.1  | 6.1 dB   |
| Peaking | 8946 Hz |  3.72 | -8.3 dB  |
| Peaking | 38 Hz   |  3.1  | -3.1 dB  |
| Peaking | 106 Hz  |  3.44 | 0.6 dB   |
| Peaking | 546 Hz  |  5.66 | -0.5 dB  |
| Peaking | 3043 Hz |  5.79 | 1.2 dB   |
| Peaking | 4028 Hz | 10.51 | -1.7 dB  |

### Fixed Band EQs
In case of using fixed band (also called graphic) equalizer, apply preamp of **-6.5dB** and set
gains manually with these parameters.

| Type    | Fc       |    Q | Gain    |
|:--------|:---------|:-----|:--------|
| Peaking | 31 Hz    | 1.41 | -1.4 dB |
| Peaking | 62 Hz    | 1.41 | -0.7 dB |
| Peaking | 125 Hz   | 1.41 | -3.5 dB |
| Peaking | 250 Hz   | 1.41 | -3.9 dB |
| Peaking | 500 Hz   | 1.41 | -0.4 dB |
| Peaking | 1000 Hz  | 1.41 | 6.1 dB  |
| Peaking | 2000 Hz  | 1.41 | -5.4 dB |
| Peaking | 4000 Hz  | 1.41 | 6.9 dB  |
| Peaking | 8000 Hz  | 1.41 | -1.5 dB |
| Peaking | 16000 Hz | 1.41 | -0.1 dB |

### Impulse Response
In case of using Viper4Android or other convolution engine select WAV file with correct sampling frequency.

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/rtings/avg/Grado%20GW100/Grado%20GW100.png)