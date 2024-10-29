Lenovo T420 installs hackintosh<br />

_**2024.10.29**_:<br />
Updated OC 1.0.2 and some kexts. It may support sequoia, but my T420 is not around so I can't test it.<br />

_**2024.5.11**_:<br />
OC 1.0.0 and supports ventura and sonoma. Lower system versions have not been tested and may be supported.<br />

<br />

_**HARDWARE**_:<br />

&nbsp;&nbsp;&nbsp;&nbsp;CPU: i7 2670qm<br />
&nbsp;&nbsp;&nbsp;&nbsp;iGPU: HD3000<br />
&nbsp;&nbsp;&nbsp;&nbsp;Wireless: CF-WU810N (USB wireless card)<br />

<br />
STEP:<br />

1. First change the model to iMac19,1, then install the system. After the system installation is completed, change the model back to MacBookPro8,1<br />

2. Install kdk (https://github.com/dortania/KdkSupportPkg)<br />

3. Install patches using OCLP (https://github.com/dortania/OpenCore-Legacy-Patcher)<br />

4. [optional] USB wireless card driver (https://github.com/chris1111/Wireless-USB-OC-Big-Sur-Adapter) or (https://github.com/chris1111/Wireless-USB-Big-Sur-Adapter)<br />

<br />
<br />

_**Broadcom Wireless Card driver has been added, but has not been tested, may be supported**_<br />

<br />
<br />

![图片描述](img/img.png)
