# uart-hil-regression-bot
An open-source HIL regression bot for embedded UART firmware testing, powered by Devin.

## Architecture
- **MCU**: STM32
- **UART driver**: DMA ring buffer for high-speed receive/transmit
- **Protocol**: CRC16 for data integrity check
- **CI**: GitHub Actions workflow to run automated HIL stress tests

## Function
Devin will trigger serial UART test cases, verify error recovery logic, capture logs, and post test results on firmware pull requests.
