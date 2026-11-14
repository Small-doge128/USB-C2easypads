# about
A really small, compact and simple USB-C PCB with 2 output pads and of course USB-C (16pin). It's for 12V (47k resistor), but if you want higher voltage, buy a different Rset resistor, TVS diodes and fuse. [onshape](https://cad.onshape.com/documents/7232de9fd70225e34f9573ad/w/c2cc3483bf6da956bf569f6e/e/ac040c47bc44097746a4bcaa)

## Verified Real-World Testing
- **5V Non-PD Fallback:** Outputs a steady 5V on standard legacy USB-A/USB-C bricks.
- **12V USB-C PD Negotiation:** Reliably negotiates 12V on PD-capable chargers.
- **Over-Current Load Test:** Tested on a variable electronic load/discharger—held steady up to **26W at 12V** (~2.17A), tripped the polyfuse right above that threshold, and recovered cleanly once cooled.

# features
USB-C 16 pin, 2 output pads, 4 resistors, 1 poly fuse, CH221K for higher voltage, 2 capacitors. **for more informations, check my BOM**. All bundled up on a small PCB that I designed in Kicad. If you want you can have higher voltage or lower, all you need to do is change the fuse, TVS diodes and Rset resistor. The target voltage can be easily set by a table on the back of the PCB and a arrow pointing to the Rset resistor.

# dimensions
**PCB** - 22.75 mm x 10.75 mm

# why did I create it
I wanted a way to convert my soldering iron to USB-C for better usability, so I thought why not make it for more use and for more people, so that's how it was created. After building it I even added a *XT60 connector* for even better usability.

# demo video:


# pictures

<img width="2776" height="1530" alt="20261114_132252_6986626984988926070" src="https://github.com/user-attachments/assets/876fed0e-09fe-4245-ae04-8a8c9b66d817" />

<img width="1261" height="879" alt="image" src="https://github.com/user-attachments/assets/f12188bb-0779-4ecc-a658-1339ba561b68" />

<img width="1226" height="727" alt="image" src="https://github.com/user-attachments/assets/ba081022-f2e9-4e5a-bcca-b2597453d1db" />

I even added a XT60 for it.
<img width="4096" height="909" alt="Beeper_20261114_150407" src="https://github.com/user-attachments/assets/f21054c7-2322-4706-bce5-efe259e63a78" />

<img width="3646" height="1181" alt="IMG_20261114_150017210" src="https://github.com/user-attachments/assets/900becb3-44d3-4aa0-802e-fc1767a93152" />

<img width="1010" height="517" alt="image" src="https://github.com/user-attachments/assets/2e2a9f0c-5fdb-4ab4-b054-8e882c296c54" />

<img width="1184" height="676" alt="image" src="https://github.com/user-attachments/assets/249026ae-5c2d-4a4f-b372-2f6a4339eaeb" />

# BOM

| Name | Purpose | Qty | Price (USD) | Distributor | Link |
| :--- | :--- | :---: | :---: | :--- | :--- |
| 1kΩ resistor | protection | 100 | already at home | LCSC | [Link](https://www.lcsc.com/product-detail/C84375.html) |
| 5.1kΩ resistor | protection | 200 | already at home | LCSC | [Link](https://www.lcsc.com/product-detail/C95781.html) |
| 10uf capacitor | protection | 100 | already at home | LCSC | [Link](https://www.lcsc.com/product-detail/C13585.html) |
| 100nf capacitor | protection | 100 | already at home | LCSC | [Link](https://www.lcsc.com/product-detail/C49678.html) |
| USB-C receptacle (16 pin)| to bring the power| 5 | already at home | LCSC | [Link]() |
| PCB | for conecting all of the parts | 5 | $ 5 | PCBWAY | [Link](https://pcbway.com) |
| CH221K chip | for drawing more power from the USB-C | 5 | $ 1.65 | LCSC | [Link](https://www.lcsc.com/product-detail/C5125736.html) |
| TVS diode | for protection | 10 | $ 0.06 | LCSC | [Link](https://www.lcsc.com/product-detail/C7018346.html) |
| polyfuse | for protecting all of the parts from over-current / short circuits | 20 | $ 0.69 | LCSC | [Link](https://www.lcsc.com/product-detail/C42449089.html) |
| 47kΩ resistor | for drawing the requested voltage | 100 | $ 1.31 | LCSC | [Link](https://www.lcsc.com/product-detail/C17713.html) |
| **TOTAL without shipping and taxes** | | | **$ 8.71** | | |
| **TOTAL with shipping and taxes** | | | **$ 43** | | |
