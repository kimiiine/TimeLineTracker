# Daily Timeline Tracker Generator

A lightweight, zero-dependency web utility that generates printable 24-hour daily timeline trackers calibrated for standard A4 paper.

---

## Overview

| Attribute | Specification |
|---|---|
| **Tech Stack** | Vanilla HTML5, CSS3, JavaScript |
| **Dependencies** | None |
| **Print Target** | Standard A4 Portrait (10mm x 15mm margins) |
| **Capacity** | 30 days per page (up to 120 days total) |
| **Hosting** | Static file / GitHub Pages compatible |

---

## Features

* **Custom Date Range:** Select custom start and end dates with input validation.
* **Auto +30 Days:** Set a 30-day range starting from the selected start date with one click.
* **Time Formats:** Switch between 12-hour (`12 am` / `12 pm`) and 24-hour (`00` / `24`) notations.
* **A4 Print Engine:** Automatic page breaks and row-height scaling for 30 rows per sheet.
* **Theme Switching:** Dark and light mode interface with printer styles forced to black-and-white.
* **Print CSS Integration:** Uses native border rendering so ticks print without requiring background graphics enabled.
