# Xilinx-PYNQ-Z2-Project

https://pynq.readthedocs.io/en/v2.2.1/getting_started.html

## 需先準備的東西

網路線*1

SD卡*1 (SD卡建議選擇32G以上)

micro USB *1 + 一般的變壓器 / 或者 5~12V的DC變壓器 

### 電腦上須裝的東西
Jupyter Notebook 

Vivado 

#### Jupyter 安裝過程
1. 安裝Python
2. 打開 CMD / powershell / Python 
3. 執行 python -m pip install --upgrade pip
4. 執行 pip install notebook
5. 重開電腦，之後就會出現在開始列表內
## 基本設定

1.先進[官網](https://pynq.readthedocs.io/en/v2.2.1/getting_started/pynq_image.html) 載.image 

2.使用 [win32 disk imager](https://win32diskimager.download/) 將上方仔下來的image燒進SD卡上

3.依照下方圖片順序操作即可開機
![圖片](https://user-images.githubusercontent.com/67036239/130071424-2d2ad13d-cd3e-4ba5-a7dc-fd725454bccc.png)

如果正常開機的話會跟下方圖片一樣
![圖片](https://cdn.discordapp.com/attachments/701994693717917757/877882049170636861/20210819_194443.jpg)

## 如何使用

前面步驟完成的話

可以在檔案總管打\\pynq即可讀到內容

如果要編輯檔案的話 在一般瀏覽器上打 http://pynq 即可讀取

如果要控制腳位或者GPIO可能會需要使用Vivado (有待考證，檔案實在太大40G多


## 參考資料
http://xilinx.eetrend.com/d6-xilinx/article/2018-12/13964.html

https://pynq.readthedocs.io/en/v2.2.1/getting_started/pynq_z1_setup.html

https://github.com/ntubiolin/xcos?fbclid=IwAR2rKhh1QeVnAWFDA3uB6nTXroSoG9dCk06ipiiwihkTVNGz8WXp8pIdQFc

