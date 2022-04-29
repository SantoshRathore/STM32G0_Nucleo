# STM32G0_Nucleo
STM32G031K8 Nucleo Board Programming with C++ STL
Project List
  1. Led Blinking
      -> Simple Project to blink on board led 
  2. Uart
      -> In this project, for uart transmission one function "uart_tx" is added which will send the different types of data from uart without considering the buffer 
         length, Also uart_tx function can transmit integer and float type variable by simply passing the variable as argument like
            uart_tx(123);
            uart_tx(456.897);
            int i = 5672;
            uart_tx(i);
            float f = 6785.156
            uart_tx(f);
            uart_tx("Sample Text");
  
