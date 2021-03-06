# XFYRO xS2
See [usage instructions](https://github.com/jaakkopasanen/AutoEq#usage) for more options and info.

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
GraphicEQ: 21 -0.5; 23 -0.5; 25 -0.5; 28 -0.5; 31 -0.6; 34 -0.9; 37 -1.2; 41 -1.5; 45 -1.9; 49 -2.2; 54 -2.7; 60 -3.4; 66 -4.0; 72 -4.6; 79 -5.2; 87 -6.0; 96 -6.8; 106 -7.5; 116 -8.3; 128 -9.0; 141 -9.6; 155 -10.2; 170 -10.6; 187 -11.0; 206 -11.2; 227 -11.2; 249 -11.0; 274 -10.6; 302 -10.3; 332 -9.9; 365 -9.4; 402 -8.9; 442 -8.3; 486 -7.5; 535 -6.7; 588 -5.8; 647 -5.0; 712 -4.3; 783 -3.7; 861 -3.3; 947 -3.4; 1042 -3.7; 1146 -4.0; 1261 -3.3; 1387 -3.2; 1526 -2.9; 1678 -2.6; 1846 -2.2; 2031 -1.6; 2234 -0.7; 2457 -0.5; 2703 -0.5; 2973 -0.8; 3270 -2.7; 3597 -4.7; 3957 -6.5; 4353 -8.4; 4788 -9.9; 5267 -12.1; 5793 -12.1; 6373 -9.1; 7010 -5.7; 7711 -6.2; 8482 -7.3; 9330 -8.0; 10263 -6.5; 11289 -6.5; 12418 -6.5; 13660 -6.5; 15026 -12.1; 16529 -18.0; 18182 -16.6; 20000 -9.6
```

### HeSuVi
HeSuVi 2.0 ships with most of the pre-processed results. If this model can't be found in HeSuVi add
`XFYRO xS2 GraphicEQ.txt` to `C:\Program Files\EqualizerAPO\config\HeSuVi\eq\custom\` folder.

### Peace
In case of using Peace, click *Import* in Peace GUI and select `XFYRO xS2 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.8dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of **-6.2dB**.

| Type    | Fc       |    Q | Gain     |
|:--------|:---------|:-----|:---------|
| Peaking | 28 Hz    | 0.44 | 6.3 dB   |
| Peaking | 208 Hz   | 0.7  | -5.7 dB  |
| Peaking | 3667 Hz  | 0.34 | 8.4 dB   |
| Peaking | 5222 Hz  | 1.39 | -13.1 dB |
| Peaking | 17465 Hz | 1.14 | -13.2 dB |
| Peaking | 799 Hz   | 1.48 | 3.3 dB   |
| Peaking | 1017 Hz  | 0.59 | -2.2 dB  |
| Peaking | 2648 Hz  | 2.88 | 1.9 dB   |
| Peaking | 9070 Hz  | 7.32 | -2.9 dB  |
| Peaking | 13708 Hz | 5.91 | 2.9 dB   |

### Fixed Band EQs
In case of using fixed band (also called graphic) equalizer, apply preamp of **-7.5dB** and set
gains manually with these parameters.

| Type    | Fc       |    Q | Gain    |
|:--------|:---------|:-----|:--------|
| Peaking | 31 Hz    | 1.41 | 6.7 dB  |
| Peaking | 62 Hz    | 1.41 | 2.5 dB  |
| Peaking | 125 Hz   | 1.41 | -2.5 dB |
| Peaking | 250 Hz   | 1.41 | -5.1 dB |
| Peaking | 500 Hz   | 1.41 | -0.1 dB |
| Peaking | 1000 Hz  | 1.41 | 2.2 dB  |
| Peaking | 2000 Hz  | 1.41 | 6.3 dB  |
| Peaking | 4000 Hz  | 1.41 | -1.7 dB |
| Peaking | 8000 Hz  | 1.41 | -0.4 dB |
| Peaking | 16000 Hz | 1.41 | -9.7 dB |

### Impulse Response
In case of using Viper4Android or other convolution engine select WAV file with correct sampling frequency.

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/rtings/avg/XFYRO%20xS2/XFYRO%20xS2.png)