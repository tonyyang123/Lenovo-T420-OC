Lenovo T420 installs hackintosh and supports sonoma. Lower system versions have not been tested and may be supported.<br />

CPU: i7 2670qm<br />
iGPU: HD3000<br />
Wireless: CF-WU810N (USB wireless card)<br />

1. First change the model to iMac19,1, then install the system. After the system installation is completed, change the model back to MacBookPro8,1<br />

2. Install kdk (https://github.com/dortania/KdkSupportPkg)<br />

3. Install patches using OCLP (https://github.com/dortania/OpenCore-Legacy-Patcher)<br />

4. [optional] USB wireless card driver (https://github.com/chris1111/Wireless-USB-OC-Big-Sur-Adapter) or (https://github.com/chris1111/Wireless-USB-Big-Sur-Adapter)<br />

_**Broadcom Wireless Card driver has been added, but has not been tested, may be supported**_<br />

![图片描述](img/img.png)
