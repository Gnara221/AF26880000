#  AF\_26880000

This is the latest version of our team and we may never update this project.

## Description
### Hardware
The main hardware we used are as follows:

| Device/               | Usage                    |
| --------------------- | ------------------------ |
| F450                  | frame                    |
| XXD-A2212-1000KV      | motor                    |
| FS-i6                 | controller               |
| FS-iA6B               | receiver                 |
| paddles               | paddles                  |
| STM32F401RET6         | main compute chip        |
| GY-86                 | sensors                  |
| HM-10/HC-05           | BLE                      |
| 0.96 inch OLED screen | display debug parameters |
| CH32V307XX            | download program         |
| VG2392S240X0M2        | wireless-corresponding   |


## Software
see more details in [[keil5/AF_26880000/map|map]]

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