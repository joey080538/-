# -HW0-1/
├── Core/
│   ├── Inc/
│   │   ├── main.h
│   │   ├── stm32g4xx_hal_conf.h
│   │   ├── stm32g4xx_it.h
│   │   └── ...
│   └── Src/
│       ├── main.c          <-- 核心邏輯與周邊初始化
│       ├── stm32g4xx_it.c  <-- 中斷服務函式 (包含 EXTI 按鈕中斷)
│       └── system_stm32g4xx.c
└── Drivers/
    └── CMSIS/
        └── Device/
            └── ST/
                └── STM32G4xx/
