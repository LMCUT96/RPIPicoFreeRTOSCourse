Blink Assigmemet
1.//LED PAD to use
#define LED_PAD				2
#define LED1_PAD			3
#define LED2_PAD			4
2.int main( void )
{
	//Setup serial over USB and give a few seconds to settle before we start
    stdio_init_all();
    sleep_ms(3000);
    printf("GO\n");

    //Start tasks and scheduler
    const char *rtos_name = "FreeRTOS";
    printf("Starting %s on core 0:\n", rtos_name);
	printf("YABA-LEY Leyson");
	printf("F14128811");
    vLaunch();


    return 0;
}

