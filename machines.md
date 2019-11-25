# Machines

<!-- TOC -->

- [Machines](#machines)
  - [Render Machines](#render-machines)
    - [Asrock Rack AMD Build](#asrock-rack-amd-build)
  - [Capture Machines](#capture-machines)
    - [IO Victorems Asrock Rack AMD Build](#io-victorems-asrock-rack-amd-build)
    - [USB Grasshopper Cameras Asrock Rack AMD Build](#usb-grasshopper-cameras-asrock-rack-amd-build)

<!-- /TOC -->

## Render Machines

### Asrock Rack AMD Build

- This has 2 GPUs right now, but can be expanded to 3 GPUs with a 24 Core CPU (AMD Ryzen Threadripper 2970WX (24-Core/48-Thread) Processor 4.2 GHz Max Boost 76MB Cache (YD297XAZAFWOF)) could be a suitable candidate, unless we go with the Epyc series.
- Twice the ram the capture machines have
- A very large PSU to handle 3 GPUs and a higher specced CPU than a capture machine
- Less storage since it does hold complete captures
- 2-3 GPUs allowed

| Build                 | Item Type     | Component                                                  | # |
| --------------------- | ------------- | ---------------------------------------------------------- | - |
| Asrock Rack AMD Build | Chassis       | Rosewill 4U Server Chassis/Server                          | 1 |
| Asrock Rack AMD Build | Mother        | X399D8A-2T (Chipset: AMD X399/TR4 409P)                    | 1 |
| Asrock Rack AMD Build | CPU           | AMD Ryzen Threadripper 2950X Processor (YD295XA8AFWOF)     | 1 |
| Asrock Rack AMD Build | Ram           | 128GB, DDR4 UDIMM DDR4 ECC and non-ECC, Un-buffered Memory | 8 |
| Asrock Rack AMD Build | GPU           | NVIDIA RTX 2080Ti - **Change to 32 thread CPU w/ 3GPU**    | 2 |
| Asrock Rack AMD Build | NIC           | 10G RJ-45 Builtin                                          | 2 |
| Asrock Rack AMD Build | PSU           | EVGA 1600G2 GOLD                                           | 1 |
| Asrock Rack AMD Build | Misc          | HDMI Display Port Emulator Plugs                           | 1 |
| Asrock Rack AMD Build | Drive OS      | Samsung 500GB SSD Red Series                               | 1 |
| Asrock Rack AMD Build | Drive Storage | 500GB NVME                                                 | 1 |
| Asrock Rack AMD Build | Cool CPU      | Noctua 4U compliant cooler for TR4                         | 1 |
| Asrock Rack AMD Build | Capture       | Frame Grabber Bitflow Cyton                                | 0 |
| Asrock Rack AMD Build | Capture       | USB Flir 4X                                                | 0 |
| Asrock Rack AMD Build | Labor         | Assembly & Test                                            | 1 |

## Capture Machines

### IO Victorems Asrock Rack AMD Build

>**NOT VETTED YET**

- This build has a bitflow capture card to be used with IO Victorem cameras
- Half the ram the render machines have
- Smaller PSU than a render machine
- large storage for storing daily captures
- 1 GPU only - 1 more GPU can be added to increase render capacity

| Build                 | Item Type     | Component                                                  | # |
| --------------------- | ------------- | ---------------------------------------------------------- | - |
| Asrock Rack AMD Build | Chassis       | Rosewill 4U Server Chassis/Server                          | 1 |
| Asrock Rack AMD Build | Mother        | X399D8A-2T (Chipset: AMD X399/TR4 409P)                    | 1 |
| Asrock Rack AMD Build | CPU           | AMD Ryzen Threadripper 2950X Processor (YD295XA8AFWOF)     | 1 |
| Asrock Rack AMD Build | Ram           | 128GB, DDR4 UDIMM DDR4 ECC and non-ECC, Un-buffered Memory | 4 |
| Asrock Rack AMD Build | GPU           | NVIDIA RTX 2080Ti D6 11GB                                  | 1 |
| Asrock Rack AMD Build | NIC           | 10G RJ-45 Builtin                                          | 2 |
| Asrock Rack AMD Build | PSU           | EVGA 850 P2                                                | 1 |
| Asrock Rack AMD Build | Misc          | HDMI Display Port Emulator Plugs                           | 1 |
| Asrock Rack AMD Build | Drive OS      | Samsung 500GB SSD Red Series                               | 1 |
| Asrock Rack AMD Build | Drive Storage | 2TB NVME                                                   | 1 |
| Asrock Rack AMD Build | Cool CPU      | Noctua 4U compliant cooler for TR4                         | 1 |
| Asrock Rack AMD Build | Capture       | **Frame Grabber Bitflow Cyton**                            | 1 |
| Asrock Rack AMD Build | Capture       | USB Flir 4X Host Controller                                | 0 |
| Asrock Rack AMD Build | Labor         | Build Labor and Cabling                                    | 1 |

### USB Grasshopper Cameras Asrock Rack AMD Build

- This build a 4 channel Flir USB Host Controller to be used with Grasshopper cameras
- Half the ram the render machines have
- Smaller PSU than a render machine
- large storage for storing daily captures
- 1 GPU only - 1 more GPU can be added to increase render capacity

| Build                 | Item Type     | Component                                                  | # |
| --------------------- | ------------- | ---------------------------------------------------------- | - |
| Asrock Rack AMD Build | Chassis       | Rosewill 4U Server Chassis/Server                          | 1 |
| Asrock Rack AMD Build | Mother        | X399D8A-2T (Chipset: AMD X399/TR4 409P)                    | 1 |
| Asrock Rack AMD Build | CPU           | AMD Ryzen Threadripper 2950X Processor (YD295XA8AFWOF)     | 1 |
| Asrock Rack AMD Build | Ram           | 128GB, DDR4 UDIMM DDR4 ECC and non-ECC, Un-buffered Memory | 4 |
| Asrock Rack AMD Build | GPU           | NVIDIA RTX 2080Ti D6 11GB                                  | 1 |
| Asrock Rack AMD Build | NIC           | 10G RJ-45 Builtin                                          | 2 |
| Asrock Rack AMD Build | PSU           | EVGA 850 P2                                                | 1 |
| Asrock Rack AMD Build | Misc          | HDMI Display Port Emulator Plugs                           | 1 |
| Asrock Rack AMD Build | Drive OS      | Samsung 500GB SSD Red Series                               | 1 |
| Asrock Rack AMD Build | Drive Storage | 2TB NVME                                                   | 1 |
| Asrock Rack AMD Build | Cool CPU      | Noctua 4U compliant cooler for TR4                         | 1 |
| Asrock Rack AMD Build | Capture       | Frame Grabber Bitflow Cyton                                | 0 |
| Asrock Rack AMD Build | Capture       | **USB Flir 4X Host Controller**                            | 1 |
| Asrock Rack AMD Build | Labor         | Build Labor and Cabling                                    | 1 |
