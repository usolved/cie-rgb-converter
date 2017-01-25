# cie-rgb-converter

## Overview

This script provides two functions to convert the CIE (XYZ) color space to the RGB color space and vice versa.

The developer documentation for Philips Hue provides the formulas used in this script:
https://developers.meethue.com/documentation/color-conversions-rgb-xy

I've used the formulas and Objective-C example code and transfered it to JavaScript.

## Authors

Ricardo Klement ([www.usolved.net](http://usolved.net))

## Installation

Just include the cie_rgb_converter.js file to your HTML page:
```
<script src="cie_rgb_converter.js"></script>
```

## Examples

### Convert CIE to RGB

```
var rgb = cie_to_rgb(0.6611, 0.2936)
```

### Convert RGB to CIE

```
var cie = rgb_to_cie(255, 39, 60)
```