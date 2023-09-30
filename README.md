# DinoGame-Arduino
This is an Arduino based dino game. Created by DeadSOUL Studios.

## Dinosaur game using Arduino UNO:
Dinosaur game that we used to play in Google Chrome when we run out of internet is now available for Arduino UNO as well. This Arduino project is good for schools and colleges and is very cheap to build as well. The game looks fascinating and lovely.

## Gameplay (Working):

[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/tdUTZlMm6pM/0.jpg)](https://www.youtube.com/watch?v=tdUTZlMm6pM)

## Components Required:
### Arduino UNO: [Amazon](https://www.amazon.in/dp/B08LN5LWTG/ref=sspa_dk_detail_1?psc=1&pd_rd_i=B08LN5LWTG&pd_rd_w=RYw72&content-id=amzn1.sym.2575ab02-73ff-40ca-8d3a-4fbe87c5a28d&pf_rd_p=2575ab02-73ff-40ca-8d3a-4fbe87c5a28d&pf_rd_r=QF59JDNBB7ZXM873HPSN&pd_rd_wg=kEsCp&pd_rd_r=56bac653-803c-48e0-979f-5b7003f9f364&s=industrial&sp_csd=d2lkZ2V0TmFtZT1zcF9kZXRhaWw), [QuartzComponents](https://quartzcomponents.com/products/arduino-uno?variant=31898093846663&currency=INR&utm_medium=product_sync&utm_source=google&utm_content=sag_organic&utm_campaign=sag_organic?utm_source=google&utm_medium=FreeListings&gclid=CjwKCAjwkLCkBhA9EiwAka9QRvdM_YpoLcSXXT9PDwWRoJATXrAE0LHDImitXtRVdGojGD4X54aGPxoCRRMQAvD_BwE)
### 16x2 LCD Display: [Amazon](https://www.amazon.in/Generic-JCE-16X2-Lcd-Display/dp/B00OVY28M4), [QuartzComponents](https://quartzcomponents.com/products/16x2-lcd-display-module-green?utm_source=google&utm_medium=FreeListings&gclid=CjwKCAjwkLCkBhA9EiwAka9QRnC83mjHbOml0jVsiQBRHQyfxt8DteOAzI8LDsD-E7vNuGLl-3sRHBoCOoUQAvD_BwE)
### i2c Serial Interface LCD Adapter Module: [Amazon](https://www.amazon.in/REES52-Display-Interface-Address-Changeable/dp/B01IKT5RVY), [QuartzComponents](https://quartzcomponents.com/products/i2c-serial-interface-adapter-module?utm_source=google&utm_medium=FreeListings&gclid=CjwKCAjwkLCkBhA9EiwAka9QRmpkvsi6zY1CxTIMdZZt9RDHpMKosenN12Pqp6fLEY2oaFj8eLooSBoCL0YQAvD_BwE)
### Push Button: [Amazon](https://www.amazon.in/switch-11x11x4-3MM-Tactile-Button-Self-Reset/dp/B07MDH66DN/ref=sr_1_9?keywords=Push+Button+Switch&qid=1686931304&sr=8-9), [QuartzComponents](https://quartzcomponents.com/products/push-button-2-pin-tactile-micro-switch?variant=31898086113415&currency=INR&utm_medium=product_sync&utm_source=google&utm_content=sag_organic&utm_campaign=sag_organic?utm_source=google&utm_medium=FreeListings&gclid=CjwKCAjwkLCkBhA9EiwAka9QRoOMbWZ83mGRU1Lj7d9wBOXWN6IDMcOZHd6SFJ5VNzIvT6h3S6PulRoCt4UQAvD_BwE)
### Buzzer: [Amazon](https://www.amazon.in/Passive-Acoustic-Component-Speaker-electronic/dp/B07MR2KN97/ref=d_pd_sbs_sccl_3_5/261-6750068-0442035?pd_rd_w=5xtlZ&content-id=amzn1.sym.fa697102-547e-425b-bc67-26478c036f29&pf_rd_p=fa697102-547e-425b-bc67-26478c036f29&pf_rd_r=2Z81GX4HTKH0CANAK6FC&pd_rd_wg=g8s0N&pd_rd_r=a83e6ef5-df14-49ef-8c5e-8a763d3bda8a&pd_rd_i=B07MR2KN97&psc=1), [QuartzComponents](https://quartzcomponents.com/products/small-piezoelectric-buzzer-5v-passive-buzzer?utm_source=google&utm_medium=FreeListings&utm_campaign=gs-2020-12-29&utm_source=google&utm_medium=smart_campaign&gclid=CjwKCAjwkLCkBhA9EiwAka9QRtYkZBBi9ImpM3X0AR3Fr7uzFMoq7lZ4KrVi_cl8Lp3m5HCimewjTBoCxJkQAvD_BwE)

## Required Libraries:
### LiquidCrystal I2C by Frank de Brabander
![Screenshot from 2023-06-16 21-50-30](https://github.com/DeadSOUL-Studios/DinoGame-Arduino/assets/119154806/1781bb7f-e1cb-430d-90a8-2a0d07851fee)

## Circuit Diagram:
![Screenshot from 2023-06-16 21-44-38](https://github.com/DeadSOUL-Studios/DinoGame-Arduino/assets/119154806/9e160e9a-de07-4d15-92a4-7602c6df9885)

(i2c module is not shown as it is attached with the LCD Display)

## Code:
Code is given in the attached .ino file with this project. Simply download that .ino file, open it using Arduino IDE and upload the code to your Arduino board. Note that you have to change the display address (0x27) in the code if your display's address is different and you also have to adjust the brightness of the display using the potentiometer given in the i2c module.

## Credits:
Code: [Max Imagination](https://www.youtube.com/@MaxImagination)
