# How to modify TuYa TS0601 thermostat to use with external temperature sensor in Home Assistant

# Problem:
You can find many "external temperature sensor" automations templates that are using calibration method. But big problem with all of them, that current temperature measured on the device changing very often and you need to get it every time you want to send update for "external temperature sensor". Usually automations code looks like this:
1. Send 0.0 to local_temperature_calibration
2. Few seconds later we receive local_temperature from device.
3. Scripts takes local_temperature and subtract value of your external temperature sensor. Total amount(difference) send to local_temperature_calibration.

It is working method. But temperature jumps to much(look green line on picture)
<details>
<summary>View picture</summary>

![image](https://user-images.githubusercontent.com/64870895/144145174-813ef336-0e6b-4695-8d4c-85e00a0379a7.png)
</details>


# Device appearance:
<details>
<summary>Box view</summary>

![image](https://user-images.githubusercontent.com/64870895/143912651-9f778e33-1be8-4c9f-9c73-41b4c619933e.png)
</details>
<details>
<summary>Front view</summary>

![image](https://user-images.githubusercontent.com/64870895/143913054-e535ba87-4534-48a8-9498-143656be5e9d.png)
</details>
<details>
<summary>Top view</summary>

![image](https://user-images.githubusercontent.com/64870895/143913088-661a9c86-7a67-4d84-8b38-83e7813af34e.png)
</details>







