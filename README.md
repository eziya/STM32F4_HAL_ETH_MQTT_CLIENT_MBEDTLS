# STM32F4_HAL_ETH_MQTT_CLIENT_MBEDTLS
STM32F4 + MQTT + mbedTLS example
 
1. Reference <br>
- https://www.eclipse.org/paho/ <br>
- https://github.com/eclipse/paho.mqtt.embedded-c <br>
- https://www.instructables.com/id/How-to-implement-embedded-Mqtt-Client-using-W5500-/ <br>
- http://blog.naver.com/pcppcp454/221380882726 <br>
- https://engschool.tistory.com/entry/SSLTLS-embedded-for-IoT-8 <br>
- https://cxemotexnika.org/2018/10/primer-zashhishhennogo-https-soedineniya-s-ispolzovaniem-mbed-tls/ <br>
- https://github.com/PetroShevchenko/cxemotexnika/tree/master/Examples/NUCLEO_F429ZI/nucleo_f429zi_https_client <br>
- https://www.st.com/resource/en/user_manual/dm00470937-getting-started-with-xcubecldgen-iot-cloud-generic-software-expansion-for-stm32cube-stmicroelectronics.pdf <br>

2. Implementation
- Added MQTTInerface.c/h files to port paho MQTT library for STM32 HAL + FREERTOS + LWIP
- Added mbedTLS library to MQTTInterface.c/h

3. Tutorial & Videos (Written in Korean) <br>
https://blog.naver.com/eziya76/221976226378 <br>
https://youtu.be/bJi3Q6a76Yk <br>

