# OPi_GPIO_LedBlink
Always blink led by GPIO on Orange Pi Win Plus

# Orignal code blink
http://wiringpi.com/examples/blink/

#include <wiringPi.h>
int main (void)
{
  wiringPiSetup () ;
  pinMode (0, OUTPUT) ;
  for (;;)
  {
    digitalWrite (0, HIGH) ; delay (500) ;
    digitalWrite (0,  LOW) ; delay (500) ;
  }
  return 0 ;
}

# Flow topic to build on Windows OS (Windows 10)

1. Topic:
http://www.instructables.com/id/Orange-PI-HowTo-GPIO-Led-Blink-Application-by-Cros/

2. OS Pi:
Armbian
https://www.armbian.com/orange-pi-win/

3. Toolchain:
http://releases.linaro.org/archive/14.07/components/toolchain/binaries/gcc-linaro-aarch64-linux-gnu-4.9-2014.07-20140730_win32.exe

Note: Toolchain change flowing with GNU GCC of each OS Pi

4. WiringPi:
https://github.com/CockDeveloper/WiringPi_CodeBlocks/tree/CodeBlocks
