### Linux Kernel in each platform that supports DSM 7.2

Any recently released Synology NAS that uses a CPU arch that Synology had not previously used use kernel 5.10, like the SA6400, RS2825RP+, DS1825+, DS1525+, DS925+, DS725+, DS425+, DS225+, DS124, DS423, DS223j and DS223.

Any Synology with the following CPU architectures use kernel 4.4
- apollolake, armada37xx, broadwell, broadwellnk, broadwellnkv2, broadwellntbap, denverton, geminilake, kvmcloud, kvmx64, purley, r1000, rtd1296 and v1000

Synology's with older CPU architectures use kernel 3.10 or 2.6

### Kernel version per DSM version

| [Platform arch](https://kb.synology.com/en-global/DSM/tutorial/What_kind_of_CPU_does_my_NAS_have) | Kernel | Models |
|----------------|--------------|--------|
| v1000nk        | 5.10.x       | DS1825+, DS1525+, DS925+ and RS2825RP+ |
| r1000nk        | 5.10.x       | DS725+ |
| geminilakenk   | 5.10.x       | DS425+, DS225+ |
| epyc7002       | 5.10.x       | SA6400 |
| rtd1619b       | 5.10.x       | DS124, DS423, DS223j and DS223 |
| | | |
| apollolake     | 4.4.x        |
| armada37xx     | 4.4.x        |
| broadwell      | 4.4.x        | 3.10.x in DSM 6 DS3617xs |
| broadwellnk    | 4.4.x        |
| broadwellnkv2  | 4.4.x        |
| broadwellntbap | 4.4.x        |
| denverton      | 4.4.x        |
| geminilake     | 4.4.x        |
| kvmcloud       | 4.4.x        |
| kvmx64         | 4.4.x        |
| purley         | 4.4.x        |
| r1000          | 4.4.x        |
| rtd1296        | 4.4.x        |
| v1000          | 4.4.x        |
| | | |
| avoton         | 3.10.x       |
| braswell       | 3.10.x       |
| bromolow       | 3.10.x       |
| grantley       | 3.10.x       |
| | | |
| alpine         | 3.10.x-bsp   |
| alpine4k       | 3.10.x-bsp   |
| armada38x      | 3.10.x-bsp   |
| monaco         | 3.10.x-bsp   |

### Kernel version per DSM version

| [Platform arch](https://kb.synology.com/en-global/DSM/tutorial/What_kind_of_CPU_does_my_NAS_have) | DSM 6.2 Kernel | DSM 7.0-7.2 Kernel | DSM 7.3 Kernel |
|----------------|--------------|----------------|----------------|
| 88f6281        | 2.6.32.12    | -              | -              |
| 88f6282        | 2.6.32.12    | -              | -              |
| alpine         | -            | 3.10.108       | 3.10.108       |
| alpine4k       | -            | 3.10.108       | 3.10.108       |
| apollolake     | -            | 4.4.180+       | 4.4.302+       |
| armada370      | 3.2.40       | 3.2.101        | 3.2.101        |
| armada375      | -            | 3.2.101        | 3.2.101        |
| armada37xx     | -            | 4.4.180+       | 4.4.302+       |
| armada38x      | -            | 3.10.108       | 3.10.108       |
| armadaxp       | 3.2.40       | 3.2.101        | 3.2.101        |
| avoton         | 3.10.105     | 3.10.108       | 3.10.108       |
| braswell       | -            | 3.10.108       | 3.10.108       |
| broadwell      | 3.10.105     | 4.4.180+       | 4.4.302+       |
| broadwellnk    | -            | 4.4.180+       | 4.4.302+       |
| broadwellnkv2  | -            | 4.4.180+       | 4.4.302+       |
| broadwellntbap | -            | 4.4.180+       | 4.4.302+       |
| bromolow       | 3.10.105     | 3.10.108       | 3.10.108       |
| cedarview      | 3.10.105     | 3.10.108       | -              |
| comcerto2k     | -            | 3.2.101        | -              |
| denverton      | -            | 4.4.180+       | 4.4.302+       |
| epyc7002       | -            | 5.10.55+       | 5.10.55+       |
| evansport      | -            | 3.2.101        | -              |
| geminilake     | -            | 4.4.180+       | 4.4.302+       |
| geminilakenk   | -            | 5.10.55+       | 5.10.55+       |
| grantley       | -            | 3.10.108       | 3.10.108       |
| hi3535         | 3.4.35_hi353 | -              | -              |
| kvmx64         | -            | 4.4.180+       | 4.4.302+       |
| monaco         | -            | 3.10.108       | 3.10.108       |
| purley         | 4.4.59+      | 4.4.180+       | 4.4.302+       |
| qoriq          | 2.6.32.12    | -              | -              |
| r1000          | -            | 4.4.180+       | 4.4.302+       |
| r1000nk        | -            | 5.10.55+       | 5.10.55+       |
| rtd1296        | -            | 4.4.180+       | 4.4.302+       |
| rtd1619b       | -            | 5.10.55+       | 5.10.55+       |
| v1000          | 4.4.59+      | 4.4.180+       | 4.4.302+       |
| v1000nk        | -            | 5.10.55+       | 5.10.55+       |
| x86            | 3.10.105     | -              | -              |

