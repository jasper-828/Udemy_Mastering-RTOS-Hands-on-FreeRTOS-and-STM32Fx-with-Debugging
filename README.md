# Udemy_Mastering-RTOS-Hands-on-FreeRTOS-and-STM32Fx-with-Debugging
This repo contains my practical exercises and assignments from the Udemy course “[Mastering RTOS: Hands-on FreeRTOS and STM32Fx with Debugging](https://www.udemy.com/share/101XDy3@7RkOhCgdwjftwfe3jKDCcnz2oBxUb1UiKwB60-x5yERVo8gtYnN2HKjBsMiBoAIB0w==/))”, covering FreeRTOS development, STM32Fx integration, and real-time debugging with SEGGER SystemView.

## Repository Structure

| Folder | Description |
|---------|-------------|
| **001Tasks** | Basic FreeRTOS task creation and scheduling. |
| **002LED_Tasks** | Blinking LEDs with separate tasks for timing and control. |
| **003LED_Block_Tasks** | Using blocking delays for efficient CPU utilization. |
| **005LED_Task_Notify** | Direct task notification to trigger LED actions. |
| **006LED_Btn_ISR** | Handling external button interrupts with ISR-safe APIs. |
| **007_Task_Priority** | Exploring task priority and preemption behavior. |
| **008Queues_n_times** | Implementing inter-task communication with queues. |
| **common/** | Shared headers, drivers, and utility files. |

---

## Setup & Requirements
- **Board:** STM32F4 Discovery (STM32F407VG)
- **IDE:** STM32CubeIDE
- **FreeRTOS:** v10.5.1
