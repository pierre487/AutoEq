# Turtle Beach Stealth 600
See [usage instructions](https://github.com/jaakkopasanen/AutoEq#usage) for more options and info.

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
GraphicEQ: 21 -5.2; 23 -5.6; 25 -6.0; 28 -6.5; 31 -6.9; 34 -7.2; 37 -7.3; 41 -7.5; 45 -7.6; 49 -7.6; 54 -7.7; 60 -7.7; 66 -7.8; 72 -7.8; 79 -7.8; 87 -7.8; 96 -7.8; 106 -7.8; 116 -7.8; 128 -7.8; 141 -7.6; 155 -7.5; 170 -7.2; 187 -6.9; 206 -6.6; 227 -6.2; 249 -5.7; 274 -5.5; 302 -5.2; 332 -5.0; 365 -4.6; 402 -4.1; 442 -3.8; 486 -3.9; 535 -4.1; 588 -4.2; 647 -4.3; 712 -4.3; 783 -4.6; 861 -5.1; 947 -5.9; 1042 -6.3; 1146 -6.4; 1261 -6.1; 1387 -5.8; 1526 -5.0; 1678 -4.1; 1846 -3.4; 2031 -3.1; 2234 -2.1; 2457 -1.9; 2703 -1.8; 2973 -0.5; 3270 -1.2; 3597 -2.5; 3957 -6.2; 4353 -6.2; 4788 -4.8; 5267 -2.7; 5793 -2.1; 6373 -5.4; 7010 -5.2; 7711 -4.5; 8482 -4.8; 9330 -4.8; 10263 -4.8; 11289 -4.8; 12418 -5.7; 13660 -4.8; 15026 -4.8; 16529 -4.8; 18182 -4.8; 20000 -4.8
```

### HeSuVi
HeSuVi 2.0 ships with most of the pre-processed results. If this model can't be found in HeSuVi add
`Turtle Beach Stealth 600 GraphicEQ.txt` to `C:\Program Files\EqualizerAPO\config\HeSuVi\eq\custom\` folder.

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Turtle Beach Stealth 600 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-4.6dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of **-4.2dB**.

| Type    | Fc       |     Q | Gain    |
|:--------|:---------|:------|:--------|
| Peaking | 75 Hz    |  0.5  | -3.4 dB |
| Peaking | 1192 Hz  |  3.06 | -2.2 dB |
| Peaking | 3142 Hz  |  1.42 | 5.2 dB  |
| Peaking | 4118 Hz  |  3.01 | -4.9 dB |
| Peaking | 5500 Hz  |  6.38 | 2.7 dB  |
| Peaking | 166 Hz   |  2.27 | -0.7 dB |
| Peaking | 459 Hz   |  1.81 | 1.4 dB  |
| Peaking | 6638 Hz  | 13.24 | -2.5 dB |
| Peaking | 12485 Hz |  6.26 | -1.0 dB |

### Fixed Band EQs
In case of using fixed band (also called graphic) equalizer, apply preamp of **-2.8dB** and set
gains manually with these parameters.

| Type    | Fc       |    Q | Gain    |
|:--------|:---------|:-----|:--------|
| Peaking | 31 Hz    | 1.41 | -1.7 dB |
| Peaking | 62 Hz    | 1.41 | -2.5 dB |
| Peaking | 125 Hz   | 1.41 | -2.7 dB |
| Peaking | 250 Hz   | 1.41 | -0.9 dB |
| Peaking | 500 Hz   | 1.41 | 1.9 dB  |
| Peaking | 1000 Hz  | 1.41 | -2.3 dB |
| Peaking | 2000 Hz  | 1.41 | 2.5 dB  |
| Peaking | 4000 Hz  | 1.41 | 1.0 dB  |
| Peaking | 8000 Hz  | 1.41 | -0.2 dB |
| Peaking | 16000 Hz | 1.41 | -0.1 dB |

### Impulse Response
In case of using Viper4Android or other convolution engine select WAV file with correct sampling frequency.

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/rtings/avg/Turtle%20Beach%20Stealth%20600/Turtle%20Beach%20Stealth%20600.png)