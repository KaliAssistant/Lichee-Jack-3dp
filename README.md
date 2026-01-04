# Lichee-Jack-3dp

3D‑printed enclosure designs for **Lichee‑Jack**.

This repository contains the printable case files (STL) and mechanical notes for assembling Lichee‑Jack. For detailed **assembly instructions**, **print settings**, and **photos**, please visit the official documentation:

**Lichee‑Jack Wiki**: [https://kaliassistant.github.io/Lichee-Jack-wiki/docs/hardware/2_3dp](https://kaliassistant.github.io/Lichee-Jack-wiki/docs/hardware/2_3dp)

---

## Contents


```
Lichee-Jack-3dp/
├─ accessories/     # Optional printed accessories
│  ├─ Lichee-Jack-badge.stl
│  ├─ Lichee-Jack-hat.stl
│  ├─ Lichee-Jack-header-baffle-nologo.stl
│  └─ Lichee-Jack-header-baffle-with-logo.stl
├─ cases/           # Main enclosure parts
│  ├─ Lichee-Jack-top.stl
│  ├─ Lichee-Jack-bottom.stl
│  └─ Lichee-Jack-switch.stl
├─ LICENSE
└─ README.md
```

> File names may include version tags (e.g. `v1`, `v2`) to indicate mechanical revisions.

---

## Supported Hardware

* Lichee‑Jack main board
* LicheeRV Nano SoC board
* External board (Ext‑Board)
* Internal Li‑Po battery
* Mode switch (SP3T)
* USB‑C connector
* Status LEDs & light pipes (if applicable)

All cut‑outs and tolerances are designed specifically for the **Lichee‑Jack** hardware stack.

---

## Printing Recommendations

These are **general guidelines**. Fine‑tuning may be required depending on your printer.

* **Material**: PLA (easy) / PETG (recommended for durability)
* **Nozzle**: 0.4 mm
* **Layer height**: 0.2 mm
* **Infill**: 15–25% (Gyroid or Grid)
* **Supports**: Not required (unless stated otherwise per part)
* **Orientation**: Print shells flat on the build plate

> For exact per‑part settings, see the Wiki page linked above.

---

## Assembly

Assembly instructions, screw sizes, and wiring guidance are maintained in the Wiki:

[https://kaliassistant.github.io/Lichee-Jack-wiki/docs/hardware/2_3dp](https://kaliassistant.github.io/Lichee-Jack-wiki/docs/hardware/2_3dp)

The documentation includes:

* Exploded view diagrams
* Assembly order
* Battery placement notes
* Ext‑board alignment tips

---

## Customization

You are encouraged to:

* Modify the STL files for your own hardware variants
* Add logos or labels
* Adjust tolerances for your printer

If you publish remixes, **please credit the original project** and keep the same license.

---

## License

This project is licensed under:

**Creative Commons Attribution‑ShareAlike 4.0 International (CC BY‑SA 4.0)**

You are free to:

* **Share** — copy and redistribute the material
* **Adapt** — remix, transform, and build upon the material

Under the following terms:

* **Attribution** — You must give appropriate credit
* **ShareAlike** — Derivatives must use the same license

Full license text:
[https://creativecommons.org/licenses/by-sa/4.0/](https://creativecommons.org/licenses/by-sa/4.0/)

---

## Related Projects

* Lichee‑Jack (main project)
* Lichee‑Jack Wiki
* Lichee‑Jack Utils

---

## Disclaimer

This is an open‑source hardware project intended for **educational and research purposes only**. The authors are not responsible for misuse, damage, or regulatory issues arising from the use of these designs.

