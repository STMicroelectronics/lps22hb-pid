---
pagetitle: Release Notes for LPS22HB Component
lang: en
header-includes: <link rel="icon" type="image/x-icon" href="_htmresc/favicon.png" />
---

::: {.row}
::: {.col-sm-12 .col-lg-4}

<center>
# Release Notes for LPS22HB Component Driver
Copyright &copy; 2021 STMicroelectronics\

[![ST logo](_htmresc/st_logo_2020.png)](https://www.st.com){.logo}
</center>

# License

This software component is licensed by ST under BSD 3-Clause license, the "License".
You may not use this component except in compliance with the License. You may obtain a copy of the License at:

[BSD 3-Clause license](https://opensource.org/licenses/BSD-3-Clause)

# Purpose

This directory contains the LPS22HB component drivers.
:::

::: {.col-sm-12 .col-lg-8}
# Update history

::: {.collapse}
<input type="checkbox" id="collapse-section1" aria-hidden="true">
<label for="collapse-section1" aria-hidden="true">V1.0.0 / 18-June-2021</label>
<div>

## Main changes

### First release

- First official release [ref. DS v6.0]

##

</div>

<input type="checkbox" id="collapse-section2" aria-hidden="true">
<label for="collapse-section2" aria-hidden="true">V1.1.0 / 01-June-2023</label>
<div>

## Main changes

- Add __weak directive to read/write registers routines
- Extend stmdev_ctx_t structure with mdelay callback
- repo name changed adding '-pid' extension

##

</div>

<input type="checkbox" id="collapse-section3" aria-hidden="true">
<label for="collapse-section3" aria-hidden="true">V2.0.0 / 20-Mar-2024</label>
<div>

## Main changes

- Fixed code style (Artistic Style Version 3.4.13)
- Add "const" to ctx arg for all APIs
- [IMPROVEMENT] Adding method to get pressure and temperature data ready in one call. (More efficient)
- [IMPROVEMENT] Allow forward declaration of stmdev_ctx_t and lps22hb_fifo_output_data_t structs.
- [IMPROVEMENT][lps22hb_fifo_output_data_burst_get] Added burst FIFO read method.
- [FIX][lps22hb_from_lsb_to_hpa] Fixed raw pressure data to hPa calculation.i
- [IMPROVEMENT][lps22hb_from_lsb_to_...] Added a few more engineering units.

##

</div>

<input type="checkbox" id="collapse-section4" aria-hidden="true">
<label for="collapse-section4" aria-hidden="true">V2.0.1 / 20-Jun-2024</label>
<div>

## Main changes

- updated README.md file with tag reference and mdelay description

##

</div>

<input type="checkbox" id="collapse-section5" checked aria-hidden="true">
<label for="collapse-section5" aria-hidden="true">V2.0.2 / 07-Apr-2025</label>
<div>

## Main changes

- Fix lsb_to_hpa conversion
- Fix build warning about float/int64

##

</div>
:::

:::
:::

<footer class="sticky">
::: {.columns}
::: {.column width="95%"}
For complete documentation on LPS22HB,
visit:
[LPS22HB](https://www.st.com/content/st_com/en/products/mems-and-sensors/pressure-sensors/lps22hb.html)
:::
::: {.column width="5%"}
<abbr title="Based on template cx566953 version 2.0">Info</abbr>
:::
:::
</footer>
