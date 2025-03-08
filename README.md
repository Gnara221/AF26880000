# AF_26880000

This is the latest version of our team's quadcopter project. The project focuses on designing and implementing a quadcopter with advanced flight control algorithms, sensor integration, and real-time operating system support. This repository may not be updated in the future.

## Project Overview
- **Objective**: To design a quadcopter capable of stable flight using advanced control algorithms and sensor fusion.
- **Key Features**:
  - Real-time operating system (RTOS) support.
  - Sensor integration (GY-86 for IMU data).
  - Wireless debugging and programming.
  - PID control for flight stability.

## Description
## Hardware

The main hardware components used in this project are as follows:

| Device/Component       | Usage                          |
|------------------------|--------------------------------|
| F450                   | Frame                          |
| XXD-A2212-1000KV       | Motor                          |
| FS-i6                  | Controller                     |
| FS-iA6B                | Receiver                       |
| Paddles                | Paddles                        |
| STM32F401RET6          | Main compute chip              |
| GY-86                  | Sensors (IMU)                  |
| HM-10/HC-05            | BLE (Bluetooth Low Energy)     |
| 0.96 inch OLED screen  | Display debug parameters       |
| CH32V307XX             | Program download               |
| VG2392S240X0M2         | Wireless communication         |

- **PCB Tools**: LCEDA
- **PCB Layout**: [View on OSHWHub](https://oshwhub.com/mawentao/stm32f4-fei-kong-ban)
[^1]: Because of some problems, the Hardware design needs to be published after adjustment.


## Software
The software structure are as follows: 

```
AF_26880000
├─ .startup_stm32f401xe.s@2.6.8
├─ app
│  └─ main.c
├─ DebugConfig
├─ EventRecorderStub.scvd
├─ hardware
│  ├─ GY86.c
│  ├─ GY86.h
│  ├─ led.c
│  ├─ led.h
│  ├─ MyDelay.c
│  ├─ MyDelay.h
│  ├─ MyI2C.c
│  ├─ MyI2C.h
│  ├─ oled.c
│  ├─ oled.h
│  ├─ oled.S
│  ├─ oled_bak.c
│  ├─ oled_bak.h
│  ├─ OLED_Font.h
│  ├─ usart.c
│  └─ usart.h
├─ Listings
├─ map.md
├─ Objects
├─ os_cpu_c.c
├─ README.md
├─ RTE
│  ├─ Device
│  │  └─ STM32F401RETx
│  │     ├─ .startup_stm32f401xe.s@2.6.8
│  │     ├─ .system_stm32f4xx.c@2.6.8
│  │     ├─ startup_stm32f401xe.s
│  │     ├─ startup_stm32f401xe.s.0000
│  │     ├─ system_stm32f4xx.c
│  │     └─ system_stm32f4xx.c.0000
│  └─ _Target_1
│     └─ RTE_Components.h
├─ start.c
├─ start.h
├─ startup.s
├─ ucos2.uvguix.Gnara
├─ ucos2.uvprojx
└─ ucosii
   ├─ Cfg
   │  └─ Template
   │     ├─ app_cfg.h
   │     ├─ app_hooks.c
   │     └─ os_cfg.h
   ├─ LICENSE
   ├─ NOTICE
   ├─ Ports
   │  ├─ os_cpu.h
   │  ├─ os_cpu_a.asm
   │  └─ os_cpu_c.c
   ├─ Ports_official
   │  ├─ os_cpu.h
   │  ├─ os_cpu_a.asm
   │  └─ os_cpu_c.c
   ├─ README.rst
   ├─ Source
   │  ├─ os.h
   │  ├─ os_core.c
   │  ├─ os_dbg_r.c
   │  ├─ os_flag.c
   │  ├─ os_mbox.c
   │  ├─ os_mem.c
   │  ├─ os_mutex.c
   │  ├─ os_q.c
   │  ├─ os_sem.c
   │  ├─ os_task.c
   │  ├─ os_time.c
   │  ├─ os_tmr.c
   │  ├─ os_trace.h
   │  ├─ ucos_ii.c
   │  └─ ucos_ii.h
   └─ Trace
      └─ readme.txt

```
For the more details, see [map]<https://github.com/Gnara221/AF26880000/blob/main/map.md>
## Acknowledgments
- Special thanks to our instructor for his guidance and support throughout the project.
- Thanks to all team members @Guystone, @Poscape,@ZihengQiu for their hard work and collaboration.