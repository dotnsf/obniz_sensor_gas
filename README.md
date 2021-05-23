# obniz_sensor_gas

## Overview

Sample application for **Obniz**, **HC-SR501**, and **GAS(Google App Script)**.


## Pre-requisites

- Obniz

  - https://amzn.to/3uep4Fq

- HC-SR501

  - https://amzn.to/34awX4s

- Jumper pins

  - Male-Female * 3

- Google Spreadsheet



## Setup

- Google Spreadsheet

  - Generate one new spreadsheet

  - From menu, select **Tool** - **Script Editor**, and copy&paste script in **spreadsheet_code.txt**.

  - From menu, select **publish** - **deploy as web application**. Enter your favorite project name, when asked.

  - Set version as **1**, set your google account email address, set **Anyone, even anonymous** as access, and click **deploy** button.

  - Authorize and give permission to your application.

  - At last, you can see **web app URL**. You shoulde copy this URL for later use.

- Connect HC-SR501 into Obniz with jumper-pins

  - Obniz io0 <-- VCC: HC-SR501

  - Obniz io1 <-- OUT: HC-SR501

  - Obniz io2 <-- GND: HC-SR501

- Turn on your Obniz, and connect to WiFi


## How to run

- Edit your **index.html** with your **obniz ID** and **GAS URL**.

- Access to **Obniz - developer's console**.

  - Go http://obniz.com/ja/console/program

  - Set your obniz ID, and open editor.

  - Copy&Paste HTML contents in **index.html**.

  - Run !

- Walk in front of HC-SR501, and check your Goodle spreadsheet.


## References

https://www.youtube.com/watch?v=x8JJEQi-Y18


## Licensing

This code islicensed under MIT.


## Copyright

2021 K.Kimura @ Juge.Me all rights reserved.
