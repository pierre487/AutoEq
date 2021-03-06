# HiFiMAN Edition X V2
See [usage instructions](https://github.com/jaakkopasanen/AutoEq#usage) for more options and info.

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
GraphicEQ: 21 -1.0; 23 -1.4; 25 -1.7; 28 -2.0; 31 -2.2; 34 -2.4; 37 -2.4; 41 -2.5; 45 -2.3; 49 -2.3; 54 -2.7; 60 -3.6; 66 -4.2; 72 -4.5; 79 -4.6; 87 -4.8; 96 -5.1; 106 -5.3; 116 -5.5; 128 -5.8; 141 -5.9; 155 -6.1; 170 -6.3; 187 -6.4; 206 -6.6; 227 -6.8; 249 -7.1; 274 -7.3; 302 -7.1; 332 -5.9; 365 -5.4; 402 -5.7; 442 -6.1; 486 -7.2; 535 -8.3; 588 -5.0; 647 -7.3; 712 -3.9; 783 -4.9; 861 -3.9; 947 -5.7; 1042 -2.2; 1146 -1.9; 1261 -2.4; 1387 -0.5; 1526 -1.0; 1678 -0.7; 1846 -0.9; 2031 -2.1; 2234 -3.1; 2457 -4.0; 2703 -4.9; 2973 -4.5; 3270 -4.5; 3597 -4.0; 3957 -3.9; 4353 -5.1; 4788 -4.5; 5267 -2.9; 5793 -1.4; 6373 -5.4; 7010 -5.1; 7711 -4.3; 8482 -4.6; 9330 -4.6; 10263 -4.6; 11289 -4.6; 12418 -4.6; 13660 -4.6; 15026 -4.6; 16529 -4.6; 18182 -7.2; 20000 -9.1
```

### HeSuVi
HeSuVi 2.0 ships with most of the pre-processed results. If this model can't be found in HeSuVi add
`HiFiMAN Edition X V2 GraphicEQ.txt` to `C:\Program Files\EqualizerAPO\config\HeSuVi\eq\custom\` folder.

### Peace
In case of using Peace, click *Import* in Peace GUI and select `HiFiMAN Edition X V2 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-4.9dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of **-4.5dB**.

| Type    | Fc      |     Q | Gain    |
|:--------|:--------|:------|:--------|
| Peaking | 16 Hz   |  0.34 | 3.5 dB  |
| Peaking | 216 Hz  |  0.6  | -2.3 dB |
| Peaking | 524 Hz  |  5.83 | -2.8 dB |
| Peaking | 1544 Hz |  1.82 | 4.6 dB  |
| Peaking | 5661 Hz |  9.94 | 3.7 dB  |
| Peaking | 285 Hz  | 10.7  | -1.1 dB |
| Peaking | 379 Hz  | 12.23 | 1.5 dB  |
| Peaking | 1090 Hz | 19.19 | 2.7 dB  |
| Peaking | 2749 Hz |  7.83 | -1.2 dB |
| Peaking | 6607 Hz | 13.38 | -2.2 dB |

### Fixed Band EQs
In case of using fixed band (also called graphic) equalizer, apply preamp of **-3.8dB** and set
gains manually with these parameters.

| Type    | Fc       |    Q | Gain    |
|:--------|:---------|:-----|:--------|
| Peaking | 31 Hz    | 1.41 | 3.2 dB  |
| Peaking | 62 Hz    | 1.41 | 0.6 dB  |
| Peaking | 125 Hz   | 1.41 | -1.1 dB |
| Peaking | 250 Hz   | 1.41 | -1.8 dB |
| Peaking | 500 Hz   | 1.41 | -2.3 dB |
| Peaking | 1000 Hz  | 1.41 | 1.7 dB  |
| Peaking | 2000 Hz  | 1.41 | 2.9 dB  |
| Peaking | 4000 Hz  | 1.41 | -0.4 dB |
| Peaking | 8000 Hz  | 1.41 | 0.3 dB  |
| Peaking | 16000 Hz | 1.41 | -0.6 dB |

### Impulse Response
In case of using Viper4Android or other convolution engine select WAV file with correct sampling frequency.

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/HiFiMAN%20Edition%20X%20V2/HiFiMAN%20Edition%20X%20V2.png)