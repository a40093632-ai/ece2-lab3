# ECE2 LAB3 FPGA 응용회로 실습

전자전기컴퓨터설계실험II LAB3의 실험 19~25 RTL, 테스트벤치, XDC 및 시뮬레이션 증빙을 정리한 저장소이다.

## 개발 환경

- FPGA Board: Combo II-DLD S75
- FPGA Part: xc7s75fgga484-1
- System Clock: 50 MHz
- Vivado: 2026.1
- Simulator: Icarus Verilog 13.0
- Waveform Viewer: VaporView

## 실험 목록

| 실험 | 회로 | 소스 | VS Code 증빙 |
|---|---|---|---|
| 19 | PWM LED 밝기 | [소스](lab3_19_led_pwm/) | [증빙](evidence/19/vscode/) |
| 20 | RGB LED PWM | [소스](lab3_20_rgb_pwm/) | [증빙](evidence/20/vscode/) |
| 21 | 피에조 단일 음 | [소스](lab3_21_piezo/) | [증빙](evidence/21/vscode/) |
| 22 | 스텝모터 위상 제어 | [소스](lab3_22_stepper/) | [증빙](evidence/22/vscode/) |
| 23 | MM:SS 시계 | [소스](lab3_23_mmss_clock/) | [증빙](evidence/23/vscode/) |
| 24 | 문자 LCD 제어 | [소스](lab3_24_character_lcd/) | [증빙](evidence/24/vscode/) |
| 25 | PC-FPGA UART 에코 | [소스](lab3_25_uart_echo/) | [증빙](evidence/25/vscode/) |

## 보고서

- [LAB3 실험 전 보고서](<reports/pre/LAB3_실험전보고서_2023440129_조성현.pdf>)

## 제출 기준

- 실험 전 태그: [lab3-pre-v1](https://github.com/a40093632-ai/ece2-lab3/tree/lab3-pre-v1)
- 실험 전 기준 커밋: [26acfe878b6d7e0b0355c3be7cb1d638fb124d1c](https://github.com/a40093632-ai/ece2-lab3/commit/26acfe878b6d7e0b0355c3be7cb1d638fb124d1c)
- 실험 후 태그: [lab3-post-v1](https://github.com/a40093632-ai/ece2-lab3/tree/lab3-post-v1)
- 실험 후 기준 커밋: [02e15bf67cdef273fe04e3bc0ae515ed288e87ef](https://github.com/a40093632-ai/ece2-lab3/commit/02e15bf67cdef273fe04e3bc0ae515ed288e87ef)

Vivado 결과, bitstream 및 실제 보드 증빙은 아래 Post-lab Evidence 표에 정리하였다.

## Post-lab Evidence

| Experiment | Source | Vivado evidence | Bitstream | Board photo | Board video |
|---|---|---|---|---|---|
| 19. LED PWM | [Source](lab3_19_led_pwm/) | [Vivado](evidence/19/vivado/) | [BIT](artifacts/bit/lab3_19_led_pwm.bit) | [Photo](<evidence/19/board/photos/실험19 시연 사진.png>) | [Video](<evidence/19/board/videos/실험19 시연 영상.mp4>) |
| 20. RGB PWM | [Source](lab3_20_rgb_pwm/) | [Vivado](evidence/20/vivado/) | [BIT](artifacts/bit/lab3_20_rgb_pwm.bit) | [Photo](<evidence/20/board/photos/실험20 시연 사진.png>) | [Video](<evidence/20/board/videos/실험20 시연 영상.mp4>) |
| 21. Piezo | [Source](lab3_21_piezo/) | [Vivado](evidence/21/vivado/) | [BIT](artifacts/bit/lab3_21_piezo.bit) | [Photo](<evidence/21/board/photos/실험21 시연 사진.png>) | [Video](<evidence/21/board/videos/실험21 시연 영상.mp4>) |
| 22. Stepper | [Source](lab3_22_stepper/) | [Vivado](evidence/22/vivado/) | [BIT](artifacts/bit/lab3_22_stepper.bit) | [Photo](<evidence/22/board/photos/실험22 시연 사진.png>) | [Video](<evidence/22/board/videos/실험22 시연 영상.mp4>) |
| 23. MMSS Clock | [Source](lab3_23_mmss_clock/) | [Vivado](evidence/23/vivado/) | [BIT](artifacts/bit/lab3_23_mmss_clock.bit) | [Photo](<evidence/23/board/photos/실험23 시연 사진.png>) | [Video](<evidence/23/board/videos/실험23 시연 영상.mp4>) |
| 24. Character LCD | [Source](lab3_24_character_lcd/) | [Vivado](evidence/24/vivado/) | [BIT](artifacts/bit/lab3_24_character_lcd.bit) | [Photo](<evidence/24/board/photos/실험24 시연 사진.png>) | [Video](<evidence/24/board/videos/실험24 시연 영상.mp4>) |
| 25. UART Echo | [Source](lab3_25_uart_echo/) | [Vivado](evidence/25/vivado/) | [BIT](artifacts/bit/lab3_25_uart_echo.bit) | [Photo 1](<evidence/25/board/photos/실험25 시연 사진(1).png>) · [Photo 2](<evidence/25/board/photos/실험25 시연 사진(2).jpg>) | [Video](<evidence/25/board/videos/실험25 시연 영상.mp4>) 