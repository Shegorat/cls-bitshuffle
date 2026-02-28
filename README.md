# cls-bitshuffle

**cls-bitshuffle** is a compression filter for **FreeArc** designed to improve compression ratio for structured data.

This filter is based on the original **bitshuffle** source code:  
https://github.com/kiyo-masui/bitshuffle

---

## Parameters

| Parameter | Description |
| ---------- | ------------ |
| `b=[N]` | Block size (default: 4 MB) |
| `es=[N]` | Element size in bytes (e.g. 1, 2, 4, etc.) (default: 4) |

---

## Example

```cmd
arc.exe a -ep1 -dses --dirs -s; -lc- -di -i2 -r -m=bitshuffle+lzma data.arc packeddata\*
```

---

## Support the Project

[![Support on Patreon](https://c5.patreon.com/external/logo/become_a_patron_button.png)](https://www.patreon.com/Shegorat)

If you find this project useful, consider supporting development on Patreon.
