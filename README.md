# Distinction_Project_Labesky
This project will produce an embedded device with the capability of serving as a way to recieve immediate, on the fly audio descriptions of the visual environment around the user. It will be able to take photographs on random intervals or when specified by the user. The images and text descriptions will be stored in a database on another device and can be viewed by the user. This is intended to serve the purpose of both helping a user understand the environment around them and creating an interesting visual journal that takes minimal effort but can provide interesting points of reflection.

## Overall functionality Requirements:
1. User will be able to turn the device on and off easily
2. Device will capture photographs on a set interval
3. Device will capture photographs on user input (button press)
4. Device will send captured photographs to an exterior device functioning as a brain
5. Device will recieve audio descriptions of the photographs
6. Device will output audio descriptions to the user
7. AI analysis should occur on an external device (brain)
8. Brain should store the photographs along with the descriptions
9. Brain should generate audio descriptions which it will send to the embedded device

## Required Physical Components:
1. Arduino prgorammer (uploads code to campers since ESP32 has no usb connectors
   - https://www.digikey.com/en/products/detail/sparkfun-electronics/15096/9817166?gclsrc=aw.ds&gad_source=1&gad_campaignid=20243136172&gbraid=0AAAAADrbLlghsDJIWygJ3vghWcIjA8Iiv&gclid=CjwKCAjw7_DEBhAeEiwAWKiCC8_Fwc5NlhB9kDuRv1M0VokEMeY2BACN866RezG0WgP7wLT0a8vI0hoCBC8QAvD_BwE
3. Small camera (should be connectable to breadboard and compatible with Arduino chip)
   - https://www.digikey.com/en/products/detail/universal-solder-electronics-ltd/ESP32-CAM%2520WIFI%2520BT%2520BLE/14319859
4. Audio ouptut device (should be connectable to breadboard and compatible with arduino chip)
   - Might end up just being played on the device or regular headphones rather than arduino audio (better quality audio, easier to implement real time audio output)
5. Button (should be connectable to breadboard and compatible with arduino chip)
   - https://www.digikey.com/en/products/detail/same-sky-formerly-cui-devices-/TS02-66-60-BK-100-LCR-D/15634327?gclsrc=aw.ds&gad_source=1&gad_campaignid=20243136172&gbraid=0AAAAADrbLlghsDJIWygJ3vghWcIjA8Iiv&gclid=CjwKCAjw7_DEBhAeEiwAWKiCC_DOnEW-3dy0wmrXaEOxe-G7r8vEZVz-m55cWJXIYPEPzcXNQ-  bZkBoChWsQAvD_BwE
7. Wires (should be connectable to breadboard)
   - https://www.amazon.com/California-JOS-Breadboard-Optional-Multicolored/dp/B0BRTHR2RL/ref=pd_lpo_d_sccl_2/133-7567229-1303851?pd_rd_w=72LQl&content-id=amzn1.sym.4c8c52db-06f8-4e42-8e56-912796f2ea6c&pf_rd_p=4c8c52db-06f8-4e42-8e56-912796f2ea6c&pf_rd_r=PZVVFN4XG1KSBJYMNNW4&pd_rd_wg=nYXit&pd_rd_r=d95502be-d935-4f9c-85e9-61638aa3d545&pd_rd_i=B0BRTHR2RL&th=1
9. Breadboard
    - https://www.digikey.com/en/products/detail/universal-solder-electronics-ltd/26058/16819785?gclsrc=aw.ds&gad_source=4&gad_campaignid=20232005509&gbraid=0AAAAADrbLljdSOYlhjxqqn0XzTN55z8qx&gclid=CjwKCAjw7_DEBhAeEiwAWKiCC4gdDU9Xznk2BkFAjjeIc9Da9L0qsVdd5jKPt5G4CrxLmlQv0vDXlhoC-lgQAvD_BwE
