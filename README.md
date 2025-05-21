# Sound Patches

Develop and store multi-effects module and software sound processing patches in XML and other formats

## Folder Structure

```
./
├── device1/
│   ├── instrument1/
│   │   ├── style1/
│   │   │   ├── patch1.dev1
│   │   │   └── patch2.dev1
│   │   └── style2/
│   │       └── patch3.dev1
│   └── instrument2/
│       ├── style1/
│       │   └── patch4.dev1
│       └── style2/
│           └── patch5.dev1
├── device2/
│   └── instrument1/
│       └── style1/
│           └── patch6.dev2
└── tools/
    ├── scripts/
    │   └── batch-script1
    └── apps/
        └── app1
```

### Devices

The hardware device or software processing package (e.g. DigiTech RP500, [Rackarrack](https://rakarrack.sourceforge.net/), etc.)

### Instrument

Physical instrument (i.e. an electric guitar or bass)

### Style

The music style subcategory the patch is intended for (e.g. "metal", "funk", "jazz")

### Patch File

Patch files with meaningful names with the correct file extension for the device or program if needed. Consider organizing these into banks if the device supports banks, or giving them numbers to match the intended patch location on the device.

### Tools

A place to keep shell, node, or python programs for managing devices and patches, such as bulk organize, bulk rename, bulk dump, bulk push, etc. Lots to explore here.

