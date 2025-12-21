# ICM-20948 Pinout

| Pin # | Pin Name       | Pin Type (KiCad)       | Notes |
|-------|----------------|-----------------------|-------|
| 1     | NC             | Passive               | Do not connect |
| 2     | NC             | Passive               | Do not connect |
| 3     | NC             | Passive               | Do not connect |
| 4     | NC             | Passive               | Do not connect |
| 5     | NC             | Passive               | Do not connect |
| 6     | NC             | Passive               | Do not connect |
| 7     | AUX_CL         | Bidirectional         | I²C Master Clock for auxiliary sensor |
| 8     | VDDIO          | Power Input           | Digital I/O supply (1.71–1.95 V) |
| 9     | AD0 / SDO      | Bidirectional         | I²C address LSB / SPI data output |
| 10    | REGOUT         | Passive               | Regulator filter capacitor connection |
| 11    | FSYNC          | Input                 | Frame sync digital input; connect to GND if unused |
| 12    | INT1           | Output                | Interrupt 1 |
| 13    | VDD            | Power Input           | Main supply voltage (1.71–3.6 V) |
| 14    | NC             | Passive               | Do not connect |
| 15    | NC             | Passive               | Do not connect |
| 16    | NC             | Passive               | Do not connect |
| 17    | NC             | Passive               | Do not connect |
| 18    | GND            | Power Input           | Ground |
| 19    | RESV           | Passive               | Reserved, do not connect |
| 20    | RESV           | Passive               | Reserved, connect to GND |
| 21    | AUX_DA         | Bidirectional         | I²C Master Data for auxiliary sensor |
| 22    | nCS            | Bidirectional         | SPI chip select |
| 23    | SCL / SCLK     | Bidirectional         | I²C clock / SPI clock |
| 24    | SDA / SDI      | Bidirectional         | I²C data / SPI data input |

