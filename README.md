# Lewd-poses-for-Stable-Diffusion

Please, if you find any issues, open an issue, and I'll try to help as much as I can.  

---

## Quick-start Guide  

1. Download the workflow and install all missing nodes.  
2. Download this repo into the (Input) directory.  
3. Enjoy!  

---

## Basic List Usage  

First, we are going to teach you how to use list iteration.  

1. The **top left node** can have an Integer value equal to the number of lines in the document used.  
2. The **bottom left node** is the reset node. The output of it should be connected to `reset_bool` in the right node if you want to restart the node counting. This is important for iteration in the list.  
3. The **number counter node** (the right one) takes care of the counting mechanism.  

![image](https://github.com/user-attachments/assets/4ff3c202-8319-43e5-913f-a410c21d6c50)  

---

## Basic Single Mode Usage  

Maybe you want to try a pose, and you do not wish to switch workflows. You can just switch the node **Switch Any** to off:  

- If it is **false**, it runs in **single mode**.  
- If it is **true**, it runs in **list mode**.  

![image](https://github.com/user-attachments/assets/45d1bf4a-deac-4e9a-ae2d-1e7baf4118cf)  
