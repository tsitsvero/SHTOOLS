# PlmIndex

Compute the index of a array of Legendre functions corresponding to degree `l` and angular order `m`.

# Usage

`index` = PlmIndex (`l`, `m`)

# Returns

`index` : integer
:   Index of an array of associated Legendre functions corresponding to degree `l` and angular order `m`.

# Parameters

`l` : integer
:   The spherical harmonic degree.

`m` : integer
:   The angular order.

# Description

`PlmIndex` will calculate the index of an array of associated Legendre functions corresponding to degree `l` and angular order `m`. The input arrays are generated by routines such as `PlmBar`, `PlmBar_d1`, `PlmSchmidt`, `PlmSchmidt_d1`, `PlmON`, `PlmON_d1`, `PLegendreA`, and `PLegendreA_d1`. The array index in Python is equal to `l*(l+1)/2+m`.

# See also

[plmbar](pyplmbar.html), [plmbar_d1](pyplmbar_d1.html), [plmschmidt](pyplmschmidt.html), [plmschmidt_d1](pyplmschmidt_d1.html), [plmon](pyplmon.html), [plmon_d1](pyplmon_d1.html), [plegendrea](pyplegendrea.html), [plegendrea_d1](pyplegendrea_d1.html)