# zmk-config-9981-air
This page contains zmk firmware config for 9981 keyboard air version(without trackpad)
<img width="605" height="728" alt="image" src="https://github.com/user-attachments/assets/85eaef58-6c47-44fa-afea-d303879ee429" />
### Use this repo to generate your own ZMK keymap for the 9981 Air keyboard.  
## Get started  
```Option1```   
**0. Register a github account if you don't have one.**  
**1. Fork this repo.**  
<img width="467" height="92" alt="image" src="https://github.com/user-attachments/assets/73fbcded-25c4-4208-91d0-c07d19170656" />  

**2. Open up `config/p9981.keymap` and edit the keymap to your liking.**  
**3. After editing the keymap, choose commit changes.**  
**and then check the Github Actions section.**  
**Your new firmware file should be available for download.**  
**5. Unzip the firmware.zip file. You should see one files: `p9981-zmk.uf2`.**  
**6. Flash the keyboard with your new firmware.**  

```Option2```  
**0. Register a github account if you don't have one.**  
**1. Fork this repo.**  
**2. Access the [keymap editor web](https://nickcoutsos.github.io/keymap-editor/)**  
**3. Login with your Github Account on the web**  
**4. Choose the right repository and you can edit the keymap more intuitivly**  
**5. After editting the keymap there will be another github action compiling and you will have the firmware.zip file**  
**6. Flash the keyboard with your new firmware.**  

**More Info about the web app please access this [github page](https://github.com/nickcoutsos/keymap-editor)**  

## Build your own driver
You can change the source code under the ```/config/boards/arm/p9981/custom_driver```
