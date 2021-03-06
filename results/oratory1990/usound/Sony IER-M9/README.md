# Sony IER-M9
See [usage instructions](https://github.com/jaakkopasanen/AutoEq#usage) for more options and info.

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
GraphicEQ: 21 -6.6; 23 -6.7; 25 -6.8; 28 -7.0; 31 -7.1; 34 -7.2; 37 -7.3; 41 -7.4; 45 -7.5; 49 -7.6; 54 -7.7; 60 -7.9; 66 -8.0; 72 -8.2; 79 -8.4; 87 -8.6; 96 -8.7; 106 -8.9; 116 -9.0; 128 -9.0; 141 -9.0; 155 -9.0; 170 -8.9; 187 -8.7; 206 -8.5; 227 -8.3; 249 -8.0; 274 -7.8; 302 -7.5; 332 -7.3; 365 -7.1; 402 -6.8; 442 -6.6; 486 -6.3; 535 -6.0; 588 -5.7; 647 -5.4; 712 -5.0; 783 -4.8; 861 -4.6; 947 -4.6; 1042 -4.8; 1146 -5.2; 1261 -5.4; 1387 -5.5; 1526 -5.3; 1678 -4.9; 1846 -4.5; 2031 -4.0; 2234 -3.4; 2457 -2.3; 2703 -1.8; 2973 -3.2; 3270 -5.7; 3597 -5.6; 3957 -4.0; 4353 -4.1; 4788 -3.8; 5267 -1.9; 5793 -0.6; 6373 -0.5; 7010 -3.1; 7711 -5.4; 8482 -6.7; 9330 -8.5; 10263 -10.8; 11289 -11.7; 12418 -9.4; 13660 -8.1; 15026 -10.9; 16529 -13.1; 18182 -9.9; 20000 -5.7
```

### HeSuVi
HeSuVi 2.0 ships with most of the pre-processed results. If this model can't be found in HeSuVi add
`Sony IER-M9 GraphicEQ.txt` to `C:\Program Files\EqualizerAPO\config\HeSuVi\eq\custom\` folder.

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Sony IER-M9 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.1dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of **-5.7dB**.

| Type    | Fc       |    Q | Gain    |
|:--------|:---------|:-----|:--------|
| Peaking | 118 Hz   | 0.49 | -3.5 dB |
| Peaking | 2522 Hz  | 2.42 | 3.9 dB  |
| Peaking | 6135 Hz  | 1.96 | 8.3 dB  |
| Peaking | 13899 Hz | 0.33 | -5.5 dB |
| Peaking | 22050 Hz | 1.54 | -5.5 dB |
| Peaking | 719 Hz   | 0.44 | -0.7 dB |
| Peaking | 822 Hz   | 1.23 | 1.9 dB  |
| Peaking | 10777 Hz | 5.55 | -1.7 dB |
| Peaking | 11361 Hz | 3.97 | -0.7 dB |
| Peaking | 13367 Hz | 4.62 | 3.5 dB  |

### Fixed Band EQs
In case of using fixed band (also called graphic) equalizer, apply preamp of **-3.1dB** and set
gains manually with these parameters.

| Type    | Fc       |    Q | Gain    |
|:--------|:---------|:-----|:--------|
| Peaking | 31 Hz    | 1.41 | -1.2 dB |
| Peaking | 62 Hz    | 1.41 | -1.7 dB |
| Peaking | 125 Hz   | 1.41 | -3.0 dB |
| Peaking | 250 Hz   | 1.41 | -2.1 dB |
| Peaking | 500 Hz   | 1.41 | -0.0 dB |
| Peaking | 1000 Hz  | 1.41 | 0.5 dB  |
| Peaking | 2000 Hz  | 1.41 | 1.3 dB  |
| Peaking | 4000 Hz  | 1.41 | 2.4 dB  |
| Peaking | 8000 Hz  | 1.41 | 0.3 dB  |
| Peaking | 16000 Hz | 1.41 | -8.8 dB |

### Impulse Response
In case of using Viper4Android or other convolution engine select WAV file with correct sampling frequency.

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/oratory1990/usound/Sony%20IER-M9/Sony%20IER-M9.png)