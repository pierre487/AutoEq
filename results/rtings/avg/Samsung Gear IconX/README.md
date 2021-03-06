# Samsung Gear IconX
See [usage instructions](https://github.com/jaakkopasanen/AutoEq#usage) for more options and info.

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
GraphicEQ: 21 -0.5; 23 -0.6; 25 -0.7; 28 -1.0; 31 -1.3; 34 -1.5; 37 -1.8; 41 -2.0; 45 -2.3; 49 -2.5; 54 -2.8; 60 -3.2; 66 -3.7; 72 -4.1; 79 -4.4; 87 -4.9; 96 -5.5; 106 -6.0; 116 -6.5; 128 -6.9; 141 -7.3; 155 -7.5; 170 -7.7; 187 -7.9; 206 -8.0; 227 -7.7; 249 -7.3; 274 -6.9; 302 -6.5; 332 -6.1; 365 -5.7; 402 -5.3; 442 -4.9; 486 -4.4; 535 -3.9; 588 -3.3; 647 -2.8; 712 -2.2; 783 -2.0; 861 -2.3; 947 -3.2; 1042 -4.0; 1146 -4.8; 1261 -5.4; 1387 -5.7; 1526 -5.8; 1678 -5.9; 1846 -6.0; 2031 -5.9; 2234 -5.1; 2457 -4.3; 2703 -4.2; 2973 -4.6; 3270 -5.1; 3597 -5.3; 3957 -5.1; 4353 -4.8; 4788 -3.8; 5267 -2.9; 5793 -2.3; 6373 -3.3; 7010 -3.7; 7711 -4.9; 8482 -6.5; 9330 -8.4; 10263 -7.2; 11289 -5.2; 12418 -5.2; 13660 -5.2; 15026 -5.2; 16529 -8.8; 18182 -11.9; 20000 -6.3
```

### HeSuVi
HeSuVi 2.0 ships with most of the pre-processed results. If this model can't be found in HeSuVi add
`Samsung Gear IconX GraphicEQ.txt` to `C:\Program Files\EqualizerAPO\config\HeSuVi\eq\custom\` folder.

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Samsung Gear IconX ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-5.2dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of **-4.8dB**.

| Type    | Fc       |    Q | Gain    |
|:--------|:---------|:-----|:--------|
| Peaking | 18 Hz    | 0.33 | 4.8 dB  |
| Peaking | 176 Hz   | 0.88 | -3.3 dB |
| Peaking | 728 Hz   | 1.93 | 3.6 dB  |
| Peaking | 5726 Hz  | 3.58 | 3.2 dB  |
| Peaking | 18243 Hz | 1.46 | -7.4 dB |
| Peaking | 1772 Hz  | 1.88 | -1.2 dB |
| Peaking | 2587 Hz  | 4.22 | 1.4 dB  |
| Peaking | 7087 Hz  | 5    | 1.0 dB  |
| Peaking | 9375 Hz  | 4.39 | -3.7 dB |
| Peaking | 14258 Hz | 1.88 | 1.3 dB  |

### Fixed Band EQs
In case of using fixed band (also called graphic) equalizer, apply preamp of **-5.4dB** and set
gains manually with these parameters.

| Type    | Fc       |    Q | Gain    |
|:--------|:---------|:-----|:--------|
| Peaking | 31 Hz    | 1.41 | 4.6 dB  |
| Peaking | 62 Hz    | 1.41 | 1.5 dB  |
| Peaking | 125 Hz   | 1.41 | -1.9 dB |
| Peaking | 250 Hz   | 1.41 | -2.7 dB |
| Peaking | 500 Hz   | 1.41 | 1.8 dB  |
| Peaking | 1000 Hz  | 1.41 | 1.8 dB  |
| Peaking | 2000 Hz  | 1.41 | -1.3 dB |
| Peaking | 4000 Hz  | 1.41 | 1.5 dB  |
| Peaking | 8000 Hz  | 1.41 | -0.1 dB |
| Peaking | 16000 Hz | 1.41 | -3.1 dB |

### Impulse Response
In case of using Viper4Android or other convolution engine select WAV file with correct sampling frequency.

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/rtings/avg/Samsung%20Gear%20IconX/Samsung%20Gear%20IconX.png)