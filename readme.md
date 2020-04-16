# [Onewheel Charger](https://tomashubelbauer.github.io/onewheel-charger)

## Onewheel Pint Home Charger

63 V NMC battery charger

- Input: 100-240 Vac, 50/60 Hz, 1 A, 100 VA
- Output: 63 Vdc, 1.3 A

Connector (2 pin female Mini-DIN) pinout:

![](pint.svg)

Voltage measurements across pairs of leads:

| - | + |         |
|---|---|---------|
| 1 | 2 | -63 Vdc |
| 2 | 1 | +63 Vdc |

Found polarity:

1. 63 Vdc
2. Ground

## Onewheel+ XR Home Charger

63 V NMC battery charger

- Input: 100-240 Vac, 50/60 Hz, 300 VA
- Output: 63 Vdc, 3 A

Connector (3 pin female XLR) pinout:

![](xr.svg)

Voltage measurements across pairs of leads:

| - | + | Result  |
|---|---|---------|
| 1 | 2 | 63 Vdc  |
| 1 | 3 | 63 Vdc  |
| 2 | 1 | -63 Vdc |
| 2 | 3 | 0 Vdc   |
| 3 | 1 | -63 Vdc |
| 3 | 2 | 0 Vdc   |

Found polarity:

1. Gound
2. 63 Vdc
3. 63 Vdc

## Other Models

The Onewheel+ is not NMC I don't think and the charger specs are
58 Vdc / 3.5 A I think, the Onewheel+ XR ultracharger is probably
63 Vdc / 5 A, but I don't know either of these, so I cannot verify
these numbers.

## To-Do

### Add a guide on how to wire an XR to Pint charger adapter
