#Software Instructions {#Software Instructions}

### HFlight connection method {#hflight-connection method}

---

**HFlight** Android mobile phone ground station is a mobile ground station officially promoted by **Leixun (CUAV)**. It is perfectly compatible with all products of the company and is welcome to download and use. Software download link: [HFlight](http://fw.cuav.net/apk/HFlight.apk).

For PW-Link wireless data transmission module, HFlight acquires and displays flight control information as follows:

1. Make sure that the PW-Link and Pix flight controllers are connected properly.

2. The mobile phone searches for the WiFi network, the connection name is: **CUAVWTR\_XXXXXX**, the default password: cuavwtr666.

3. Open HFlight mobile software, select **UDP** connection mode, operation as shown in figure;

![Untitled](../../assets/Untitled.jpg)

4. Confirm the UDP server communication port and check if the port is **14550**;

![](/assets/1.jpg)

5. Finally, click on the **Connect** button. After successfully obtaining the flight control information, the data interface will be displayed.

### HFIight Modify Configuration

---

HFlight provides a window to modify the PW-Link network configuration, allowing you to modify the network's **name**,**password**,**channel**, and**for version information**. The specific operation method is to first open the HFlight mobile phone software side menu, click the system button, enter the system settings interface, long press the network settings icon. The operation is shown in the figure:

![WTR1](../../assets/WTR1.jpg) The specific procedure for the PW-Link configuration window is to first click on the query button to obtain the network information of the PW-Link module. After the success, modify the corresponding options. The operation is shown in the figure:

### ![](/assets/WTR.jpg) Mission Planner connection

---

The computer-side ground station software is operated by Mission Planner. Specific steps are as follows:

1. The computer uses a wireless network card to connect to the network **CUAVWlink\_XXXXXX**, password **cuavwlink**;

2. Open the Mission Planner software, select the option **UDP** in the upper right corner, and click the Connect button;

3. Finally, enter **14550** in the popup port edit field and click OK;

4. Wait for data reception to complete;

> Note: Some users report that the computer is connected to the PW-Link network, but the Mission Planner cannot receive data. The reason for this problem is because you have disabled network permissions.
>
> Workaround: Open the **Control Panel**&gt;**Windows Firewall**&gt;**Allow apps to communicate through the firewall**&gt;**Open MP All Network Permission**.