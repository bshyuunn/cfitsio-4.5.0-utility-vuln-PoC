# cfitsio-4.5.0-utility-vuln-PoC
This repository provides a PoC for vulnerabilities uncovered in the NASA-CFITSIO utility tool (4.5.0) via fuzzing.

- **Utility Tool Heap Buffer Overflow Vulnerability**: Triggers a DoS by overflowing the heap buffer in the utility tool.  
- **Utility Tool Negative Size Parameter Vulnerability**: Causes a DoS due to improper handling of negative size parameters in the utility tool.

### Details
- Library: [NASA-CFITSIO]([https://kr.bandisoft.com/bandiview/](https://heasarc.gsfc.nasa.gov/fitsio/))
- Version: v4.5.0 (2024/8)

### Credit
- SongHyun Bae (@bshyuunn) of TeamH4C
- GeonWoo Lee (@Cheshire) of TeamH4C
- SungJin Park(@oulth) of TeamH4C, LIGNex1
- DongHyun Kim (@longlong64bit) of TeamH4C
- JunOhLee (@IceTream) of TeamH4C
