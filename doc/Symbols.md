# Symbol fields used in all parts

| field | description |
| --- | --- |
| MFC | Manufacturer |
| MPN | Manufacturer Part Number |
| VALUE | If component has a value (e.g. 10k) this value is placed here, otherwise the mpn (or abbreviated mpn) is placed in this field.|
| DISTRIBUTOR | Primary distributor (i.e. farnell) |
| ORDER_NUMBER | Specific order number for the distributor |
| COST | Rough estimate in component cost. Accuracy of 20% is fine. |
| DATASHEET | Relative path to a local copy of a datasheet. |
| DATASHEET_URL | URL from the datasheet can be downloaded |
| FOOTPRINT | Selected footprint for this specific mpn |
| FP_HINT | Abbreviated footprint (e.g. 0603) |
| DESCRIPTION | Readable description according to manufacturer |

## Optional Fields
| field | description |
| --- | --- |
| MFC_ALT | Alternative Manufacturer |
| MPN_ALT | Alternative Manufacturer Part Number |
| ON_DISTXY | Specific order number for the distributor (i.e. mouser, digikey etc.) |

# Part Specific Fields
These fields are additionally set to the generic fields listed above.

## Resistors
| field | description |
| --- | --- |
| V_MAX | rated nominal voltage (NOT absolute maximum rating!) |
| P_MAX | rated nominal power dissipation (NOT absolute maximum rating!) |

## Capacitors
| field | description |
| --- | --- |
| V_MAX | rated nominal voltage (NOT absolute maximum rating!) |
| DIELECTRIC | material of the dielectric (e.g. X7R) |

## Inductors
| field | description |
| --- | --- |
| I_SAT | saturation current |
| I_MAX | max rated current |

## Diodes
| field | description |
| --- | --- |
| I_MAX | saturation current |
| V_REV_MAX | max rated reverse voltage |

## Zener Diodes
| field | description |
| --- | --- |
| I_MAX | saturation current |
| V_ZENER | zener voltage |
