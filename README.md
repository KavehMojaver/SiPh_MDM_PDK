# SiPh_MDM_PDK

## Introduction:
Silicon Photonics process design kit library for Mode-Division-Multiplexing components. Generated by Photonic DataCom Team, McGill University.
We are developing this library and will add more components soon.

For the complete list of recent publications on MDM components please visit:
<br />[Google Scholar Page](https://scholar.google.ca/citations?user=Eyx0xDgAAAAJ&hl=en&oi=ao)
<br /> [Photonic DataCom Team Website](http://erbium.ece.mcgill.ca/)

If you have any questions please feel free to contact:
<br />odile.liboiron-ladouceur@mcgill.ca
<br />hassan.rahbardarmojaver@mcgill.ca

## PDK components:

### 2x2 MMI 
![image](https://user-images.githubusercontent.com/44322134/200358517-d7abbe14-5e50-4899-b233-aefd332e7779.png)
layout in [MMI_2by2.gds](https://github.com/KavehMojaver/SiPh_MDM_PDK/blob/main/MMI_2by2.gds)
<br />Read more details @ [this paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9416583)
<br />Citing this work:
<br />A. Das, G. Zhang, H. R. Mojaver and O. Liboiron-Ladouceur, "Scalable Two-Mode 3-Port and 4-Port Mode Insensitive Silicon Photonic Switches," in IEEE Photonics Technology Letters, vol. 33, no. 11, pp. 557-560, June 2021.

### Mode insensitive thermo optic phase shifter for the first three TE modes (TE0, TE1, and TE2)
![image](https://user-images.githubusercontent.com/44322134/200358847-b0db2a3e-7326-4d45-8fc1-e9e1988b2bf6.png)
layout in [mode_insensitive_TOPS.gds](https://github.com/KavehMojaver/SiPh_MDM_PDK/blob/main/mode_insensitive_TOPS.gds)
<br />Read more details @ [this paper](https://opg.optica.org/ol/fulltext.cfm?uri=ol-45-4-811&id=426537)
<br />Citing this work:
<br />G. Zhang, H. Rahbardar Mojaver, A. Das, and O. Liboiron-Ladouceur, "Mode insensitive switch for on-chip interconnect mode division multiplexing systems," Optics Letters, vol. 45, no. 4, pp. 811-814, 2020.

### Mode multiplexer and demultiplexer for TE0 and TE1
![image](https://user-images.githubusercontent.com/44322134/200359072-fe8ca345-e58c-4da1-acf7-9f27487ba690.png)
layout in [Mux_deMux_2modes.gds](https://github.com/KavehMojaver/SiPh_MDM_PDK/blob/main/Mux_deMux_2modes.gds)
<br />Read more details @ [this paper](https://opg.optica.org/ol/fulltext.cfm?uri=ol-45-4-811&id=426537)
<br />Citing this work:
<br />G. Zhang, H. Rahbardar Mojaver, A. Das, and O. Liboiron-Ladouceur, "Mode insensitive switch for on-chip interconnect mode division multiplexing systems," Optics Letters, vol. 45, no. 4, pp. 811-814, 2020.

### Multimode Sbend for TE0, TE1, and TE2
![image](https://user-images.githubusercontent.com/44322134/200359218-7e4c2acf-9aa6-4bb1-9e28-36f040e620da.png)
layout in [Sbend_100um.gds](https://github.com/KavehMojaver/SiPh_MDM_PDK/blob/main/Sbend_100um.gds)
<br />Read more details @ [this paper](https://opg.optica.org/ol/fulltext.cfm?uri=ol-45-4-811&id=426537)
<br />Citing this work:
<br />G. Zhang, H. Rahbardar Mojaver, A. Das, and O. Liboiron-Ladouceur, "Mode insensitive switch for on-chip interconnect mode division multiplexing systems," Optics Letters, vol. 45, no. 4, pp. 811-814, 2020.

### Mode sensitive SWG-based thermo optic phase shifter for the first two TE modes (TE0 and TE1)
![image](https://user-images.githubusercontent.com/44322134/202222628-e84bacc9-829e-436c-b7ad-4fe8f0560d2d.png)
layout in [mode_sensitive_TOPS_SWG.GDS](https://github.com/KavehMojaver/SiPh_MDM_PDK/blob/main/mode_sensitive_TOPS_SWG.GDS)
<br />Read more details @ [this paper](http://rahbardar.research.mcgill.ca/Papers/IPC_2022.pdf)
<br />Citing this work:
<br /> Kaveh (Hassan) R. Mojaver , Guowu Zhang, and Odile Liboiron-Ladouceur, "Design of Silicon Photonic Mode-Sensitive Thermo-Optic Phase Shifter based on Subwavelength Grating Structures," IEEE Photonics Conference, 2022.

### Mode converter TE0-TE1
![image](https://user-images.githubusercontent.com/44322134/206734610-5e7f3ad5-e999-4546-a398-f5743076b5ed.png)
layout in [TE0_to_TE1.gds](https://github.com/KavehMojaver/SiPh_MDM_PDK/blob/main/TE0_to_TE1.gds)
<br />Read more details @ [this paper](https://opg.optica.org/oe/fulltext.cfm?uri=oe-30-14-25817&id=477533)
<br />Citing this work:
<br />Md Mahadi Masnad, Guowu Zhang, Dan-Xia Xu, Yuri Grinberg, and Odile Liboiron-Ladouceur, "Fabrication error tolerant broadband mode converters and their working principles," Opt. Express, vol. 30, no. 14, pp. 25817-25829, 2022.

### Mode converter TE0-TE2
![image](https://user-images.githubusercontent.com/44322134/206734685-ab379318-b2fe-477f-816b-6ee722afa1b1.png)
layout in [TE0_to_TE2.gds](https://github.com/KavehMojaver/SiPh_MDM_PDK/blob/main/TE0_to_TE2.gds)
<br />Read more details @ [this paper](https://opg.optica.org/oe/fulltext.cfm?uri=oe-30-14-25817&id=477533)
<br />Citing this work:
<br />Md Mahadi Masnad, Guowu Zhang, Dan-Xia Xu, Yuri Grinberg, and Odile Liboiron-Ladouceur, "Fabrication error tolerant broadband mode converters and their working principles," Opt. Express, vol. 30, no. 14, pp. 25817-25829, 2022.

### Mode converter TE1-TE3
![image](https://user-images.githubusercontent.com/44322134/206734758-edf0f6bb-1620-420f-904d-eb84bf86c03f.png)
layout in [TE1_to_TE3.gds](https://github.com/KavehMojaver/SiPh_MDM_PDK/blob/main/TE1_to_TE3.gds)
<br />Read more details @ [this paper](https://opg.optica.org/oe/fulltext.cfm?uri=oe-30-14-25817&id=477533)
<br />Citing this work:
<br />Md Mahadi Masnad, Guowu Zhang, Dan-Xia Xu, Yuri Grinberg, and Odile Liboiron-Ladouceur, "Fabrication error tolerant broadband mode converters and their working principles," Opt. Express, vol. 30, no. 14, pp. 25817-25829, 2022.

### 2x2 compact SWG-based MMI 
![image](https://github.com/KavehMojaver/SiPh_MDM_PDK/assets/44322134/ac72cd73-c64b-4781-8e81-068eb37bcd5e)
layout in [2Mode_SWG_MMI.gds](https://github.com/KavehMojaver/SiPh_MDM_PDK/blob/main/2Mode_SWG_MMI.GDS)
<br />Read more details @ [this paper](https://opg.optica.org/oe/fulltext.cfm?uri=oe-29-15-23864&id=453266)
<br />Citing this work:
<br />Hatef Shiran, Guowu zhang, and Odile Liboiron-Ladouceur, "Dual-mode broadband compact 2 × 2 optical power splitter using sub-wavelength metamaterial structures," Opt. Express, vol. 29, no. 15, pp. 23864-23876, 2021.

### Mode Exchanger 
![image](https://github.com/KavehMojaver/SiPh_MDM_PDK/assets/44322134/9e8673fc-c1f8-44ea-a96f-d29e67abfde8)
layout in [Mode_exchanger.gds](https://github.com/KavehMojaver/SiPh_MDM_PDK/blob/main/Mode_exchanger.GDS)
<br />Read more details @ [this paper](https://opg.optica.org/oe/fulltext.cfm?uri=oe-30-12-20543&id=473153)
<br />Citing this work:
<br />Guowu Zhang, Dan-Xia Xu, Yuri Grinberg, and Odile Liboiron-Ladouceur, "Efficient mode exchanger-based silicon photonic switch enabled by inverse design," Opt. Express vol. 30, no. 12, pp. 20543-20553, 2022.

