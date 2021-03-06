# Westone 2
See [usage instructions](https://github.com/jaakkopasanen/AutoEq#usage) for more options and info.

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
GraphicEQ: 21 -6.5; 23 -6.9; 25 -7.2; 28 -7.5; 31 -7.9; 34 -8.1; 37 -8.3; 41 -8.5; 45 -8.7; 49 -8.8; 54 -8.9; 60 -9.1; 66 -9.3; 72 -9.3; 79 -9.4; 87 -9.6; 96 -9.6; 106 -9.6; 116 -9.6; 128 -9.9; 141 -9.9; 155 -9.9; 170 -9.9; 187 -9.9; 206 -10.0; 227 -10.2; 249 -10.3; 274 -10.3; 302 -10.3; 332 -10.1; 365 -9.9; 402 -9.9; 442 -9.7; 486 -9.6; 535 -9.6; 588 -9.5; 647 -9.2; 712 -9.0; 783 -8.8; 861 -8.6; 947 -8.4; 1042 -8.2; 1146 -8.0; 1261 -8.0; 1387 -8.0; 1526 -8.2; 1678 -8.4; 1846 -8.7; 2031 -9.2; 2234 -9.3; 2457 -9.1; 2703 -7.8; 2973 -6.2; 3270 -5.2; 3597 -4.2; 3957 -1.9; 4353 -0.5; 4788 -1.4; 5267 -1.7; 5793 -0.5; 6373 -1.0; 7010 -4.0; 7711 -6.2; 8482 -6.5; 9330 -6.5; 10263 -6.5; 11289 -6.5; 12418 -6.5; 13660 -6.5; 15026 -6.5; 16529 -6.5; 18182 -6.5; 20000 -6.5
```

### HeSuVi
HeSuVi 2.0 ships with most of the pre-processed results. If this model can't be found in HeSuVi add
`Westone 2 GraphicEQ.txt` to `C:\Program Files\EqualizerAPO\config\HeSuVi\eq\custom\` folder.

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Westone 2 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.6dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of **-6.2dB**.

| Type    | Fc      |    Q | Gain    |
|:--------|:--------|:-----|:--------|
| Peaking | 50 Hz   | 0.95 | -0.9 dB |
| Peaking | 111 Hz  | 0.44 | -2.1 dB |
| Peaking | 406 Hz  | 0.43 | -2.8 dB |
| Peaking | 2288 Hz | 1.85 | -3.5 dB |
| Peaking | 4826 Hz | 1.4  | 6.5 dB  |
| Peaking | 4225 Hz | 7.86 | 1.4 dB  |
| Peaking | 5032 Hz | 6.07 | -2.0 dB |
| Peaking | 6325 Hz | 3.12 | 4.4 dB  |
| Peaking | 7388 Hz | 1.71 | -2.9 dB |

### Fixed Band EQs
In case of using fixed band (also called graphic) equalizer, apply preamp of **-5.6dB** and set
gains manually with these parameters.

| Type    | Fc       |    Q | Gain    |
|:--------|:---------|:-----|:--------|
| Peaking | 31 Hz    | 1.41 | -0.9 dB |
| Peaking | 62 Hz    | 1.41 | -2.3 dB |
| Peaking | 125 Hz   | 1.41 | -2.5 dB |
| Peaking | 250 Hz   | 1.41 | -3.0 dB |
| Peaking | 500 Hz   | 1.41 | -2.7 dB |
| Peaking | 1000 Hz  | 1.41 | -0.5 dB |
| Peaking | 2000 Hz  | 1.41 | -4.0 dB |
| Peaking | 4000 Hz  | 1.41 | 5.7 dB  |
| Peaking | 8000 Hz  | 1.41 | 1.0 dB  |
| Peaking | 16000 Hz | 1.41 | -0.3 dB |

### Impulse Response
In case of using Viper4Android or other convolution engine select WAV file with correct sampling frequency.

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/referenceaudioanalyzer/zero/Westone%202/Westone%202.png)