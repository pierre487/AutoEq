# Stax SR-507 SE1-1049
See [usage instructions](https://github.com/jaakkopasanen/AutoEq#usage) for more options and info.

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
GraphicEQ: 21 -0.5; 23 -1.4; 25 -2.1; 28 -2.8; 31 -3.1; 34 -3.2; 37 -3.1; 41 -2.8; 45 -2.5; 49 -2.3; 54 -2.1; 60 -2.0; 66 -2.0; 72 -2.2; 79 -2.5; 87 -2.8; 96 -3.0; 106 -3.4; 116 -3.5; 128 -3.7; 141 -3.8; 155 -4.0; 170 -4.0; 187 -4.1; 206 -4.2; 227 -4.0; 249 -4.1; 274 -4.0; 302 -4.2; 332 -4.3; 365 -4.2; 402 -4.3; 442 -4.1; 486 -4.2; 535 -4.3; 588 -4.3; 647 -4.6; 712 -4.9; 783 -4.9; 861 -5.4; 947 -5.6; 1042 -6.0; 1146 -6.6; 1261 -7.6; 1387 -8.4; 1526 -8.9; 1678 -9.0; 1846 -8.2; 2031 -4.8; 2234 -2.4; 2457 -2.6; 2703 -4.1; 2973 -5.0; 3270 -5.5; 3597 -4.6; 3957 -4.0; 4353 -5.9; 4788 -6.7; 5267 -4.5; 5793 -6.3; 6373 -4.5; 7010 -2.8; 7711 -5.0; 8482 -8.8; 9330 -10.1; 10263 -8.1; 11289 -5.2; 12418 -5.1; 13660 -5.1; 15026 -5.1; 16529 -5.1; 18182 -5.5; 20000 -6.9
```

### HeSuVi
HeSuVi 2.0 ships with most of the pre-processed results. If this model can't be found in HeSuVi add
`Stax SR-507 SE1-1049 GraphicEQ.txt` to `C:\Program Files\EqualizerAPO\config\HeSuVi\eq\custom\` folder.

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Stax SR-507 SE1-1049 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-5.2dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of **-4.8dB**.

| Type    | Fc      |    Q | Gain    |
|:--------|:--------|:-----|:--------|
| Peaking | 17 Hz   | 2.6  | 4.4 dB  |
| Peaking | 42 Hz   | 0.17 | 2.3 dB  |
| Peaking | 1623 Hz | 2    | -4.8 dB |
| Peaking | 2298 Hz | 4.07 | 4.9 dB  |
| Peaking | 9285 Hz | 4.86 | -5.8 dB |
| Peaking | 63 Hz   | 2.79 | 1.0 dB  |
| Peaking | 143 Hz  | 1.75 | -0.6 dB |
| Peaking | 3923 Hz | 8.2  | 1.8 dB  |
| Peaking | 5752 Hz | 1.08 | -1.1 dB |
| Peaking | 6898 Hz | 6    | 4.1 dB  |

### Fixed Band EQs
In case of using fixed band (also called graphic) equalizer, apply preamp of **-3.7dB** and set
gains manually with these parameters.

| Type    | Fc       |    Q | Gain    |
|:--------|:---------|:-----|:--------|
| Peaking | 31 Hz    | 1.41 | 2.3 dB  |
| Peaking | 62 Hz    | 1.41 | 2.6 dB  |
| Peaking | 125 Hz   | 1.41 | 0.9 dB  |
| Peaking | 250 Hz   | 1.41 | 0.5 dB  |
| Peaking | 500 Hz   | 1.41 | 1.4 dB  |
| Peaking | 1000 Hz  | 1.41 | -1.8 dB |
| Peaking | 2000 Hz  | 1.41 | -0.8 dB |
| Peaking | 4000 Hz  | 1.41 | 1.0 dB  |
| Peaking | 8000 Hz  | 1.41 | -2.0 dB |
| Peaking | 16000 Hz | 1.41 | -0.1 dB |

### Impulse Response
In case of using Viper4Android or other convolution engine select WAV file with correct sampling frequency.

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/Stax%20SR-507%20SE1-1049/Stax%20SR-507%20SE1-1049.png)