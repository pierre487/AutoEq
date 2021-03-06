# Meelectronics Air-Fi Matrix2 AF62 Wired
See [usage instructions](https://github.com/jaakkopasanen/AutoEq#usage) for more options and info.

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
GraphicEQ: 21 -0.5; 23 -1.7; 25 -2.8; 28 -4.2; 31 -5.5; 34 -6.6; 37 -7.5; 41 -8.4; 45 -9.1; 49 -9.5; 54 -9.9; 60 -10.1; 66 -10.1; 72 -10.1; 79 -10.0; 87 -10.0; 96 -9.9; 106 -9.8; 116 -9.6; 128 -9.4; 141 -9.5; 155 -9.7; 170 -9.4; 187 -9.5; 206 -9.5; 227 -9.3; 249 -9.1; 274 -9.4; 302 -9.5; 332 -9.5; 365 -9.6; 402 -9.6; 442 -9.3; 486 -9.5; 535 -9.6; 588 -9.4; 647 -9.3; 712 -9.2; 783 -8.3; 861 -7.7; 947 -7.2; 1042 -7.2; 1146 -7.1; 1261 -7.2; 1387 -7.3; 1526 -6.9; 1678 -6.2; 1846 -4.9; 2031 -4.2; 2234 -3.8; 2457 -3.6; 2703 -3.2; 2973 -3.8; 3270 -4.3; 3597 -3.4; 3957 -2.3; 4353 -1.5; 4788 -0.8; 5267 -2.8; 5793 -3.0; 6373 -2.2; 7010 -4.3; 7711 -6.9; 8482 -8.2; 9330 -6.9; 10263 -6.8; 11289 -6.8; 12418 -6.8; 13660 -6.8; 15026 -6.8; 16529 -6.8; 18182 -6.8; 20000 -6.8
```

### HeSuVi
HeSuVi 2.0 ships with most of the pre-processed results. If this model can't be found in HeSuVi add
`Meelectronics Air-Fi Matrix2 AF62 Wired GraphicEQ.txt` to `C:\Program Files\EqualizerAPO\config\HeSuVi\eq\custom\` folder.

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Meelectronics Air-Fi Matrix2 AF62 Wired ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-7.0dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of **-6.6dB**.

| Type    | Fc      |    Q | Gain    |
|:--------|:--------|:-----|:--------|
| Peaking | 20 Hz   | 1.02 | 9.1 dB  |
| Peaking | 51 Hz   | 0.38 | -4.2 dB |
| Peaking | 448 Hz  | 0.64 | -2.5 dB |
| Peaking | 2385 Hz | 1.88 | 3.1 dB  |
| Peaking | 4768 Hz | 1.76 | 5.6 dB  |
| Peaking | 701 Hz  | 2.86 | -1.4 dB |
| Peaking | 839 Hz  | 1.43 | 1.1 dB  |
| Peaking | 1412 Hz | 4.15 | -0.9 dB |
| Peaking | 6569 Hz | 7.64 | 3.0 dB  |
| Peaking | 8220 Hz | 3.69 | -2.3 dB |

### Fixed Band EQs
In case of using fixed band (also called graphic) equalizer, apply preamp of **-6.0dB** and set
gains manually with these parameters.

| Type    | Fc       |    Q | Gain    |
|:--------|:---------|:-----|:--------|
| Peaking | 31 Hz    | 1.41 | 2.8 dB  |
| Peaking | 62 Hz    | 1.41 | -4.0 dB |
| Peaking | 125 Hz   | 1.41 | -1.9 dB |
| Peaking | 250 Hz   | 1.41 | -1.8 dB |
| Peaking | 500 Hz   | 1.41 | -2.6 dB |
| Peaking | 1000 Hz  | 1.41 | -0.8 dB |
| Peaking | 2000 Hz  | 1.41 | 1.4 dB  |
| Peaking | 4000 Hz  | 1.41 | 5.3 dB  |
| Peaking | 8000 Hz  | 1.41 | 0.1 dB  |
| Peaking | 16000 Hz | 1.41 | -0.2 dB |

### Impulse Response
In case of using Viper4Android or other convolution engine select WAV file with correct sampling frequency.

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/Meelectronics%20Air-Fi%20Matrix2%20AF62%20Wired/Meelectronics%20Air-Fi%20Matrix2%20AF62%20Wired.png)