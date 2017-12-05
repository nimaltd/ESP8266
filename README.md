# Esp8266 series library
<br />
This is old version. Wait for The new One,I hope use it and enjoy.
<br />
I use Stm32f103vc and Keil Compiler and Stm32CubeMX wizard.
 <br />
Please Do This ...
<br />
<br />
1) Enable FreeRTOS  
<br />
2) Config your usart and enable interrupt on CubeMX 
<br />
3) Select "General peripheral Initalizion as a pair of '.c/.h' file per peripheral" on project settings.
<br />
4) Config your WifiConfig.h file.
<br />
5) Add Wifi_RxCallBack() on usart interrupt routin.
<br />
6) call  Wifi_Init(osPriorityNormal) on your app.
<br />
7) Config your app on WifiUser.c.
