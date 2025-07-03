# HIT-MHAD
## Introduction
HIT-MHAD数据集是一个包含采集自kinect azure相机的数据和拉伸传感器的数据的多模态人体活动数据集，包含来自10位实验员的24种动作。该数据集提供时间同步的深度视频数据、红外视频数据、骨骼坐标时序数据和拉伸传感器时序数据。
## Sensors
<div style="text-align:center">
  <img src="https://github.com/ZhouPJ411/HIT-MHAD/blob/main/img/kinect.png" alt="Kinect Azure camera" style="width:50%; max-width:400px; display:block; margin:0 auto;">
</div>

Kinect Azure camera. This device records multimodal data (including depth, infrared, and skeleton streams) in MKV format   
Kinect检测的各骨骼关节点如下图所示

<div style="text-align:center">
  <img src="https://github.com/ZhouPJ411/HIT-MHAD/blob/main/img/kinect_skeletion.png" alt="Kinect skeleton points" style="width:50%; max-width:400px; display:block; margin:0 auto;">
</div>

下图为部署了24维拉伸传感器的智能服装，传感器分布情况如下图所示：
<div style="text-align:center">
  <img src="https://github.com/ZhouPJ411/HIT-MHAD/blob/main/img/suit.png" alt="Smart suit with sensors" style="width:50%; max-width:400px; display:block; margin:0 auto;">
</div>  

拉伸传感器部署位置与对应的传感器编号如下图所示：  

| 传感器编号 | 传感器位置          | 传感器编号 | 传感器位置           |
|------------|--------------------|------------|---------------------|
| Sensor 1   | Right middle shoulder | Sensor 2   | Right anterior shoulder |
| Sensor 3   | Left underarm      | Sensor 4   | Left shoulder back  |
| Sensor 5   | Left anterior lumbar | Sensor 6   | Left elbow          |
| Sensor 7   | Right shoulder back | Sensor 8   | Mid-abdomen         |
| Sensor 9   | Right elbow        | Sensor 10  | Back waist          |
| Sensor 11  | Left thigh         | Sensor 12  | Right underarm      |
| Sensor 13  | Left middle shoulder | Sensor 14  | Left hip            |
| Sensor 15  | Left knee          | Sensor 16  | Left posterior lumbar |
| Sensor 17  | Right crotch       | Sensor 18  | Left crotch         |
| Sensor 19  | Right hip          | Sensor 20  | Right knee          |
| Sensor 21  | Right posterior lumbar | Sensor 22  | Right anterior lumbar |
| Sensor 23  | Left shoulder front | Sensor 24  | Right thigh         |  

Sensor Layout of the 24-Sensor Smart Garment.
## Information of HIT-MHAD dataset
HIT-MHAD包含24个动作类别，其中包括16个日常动作和8个训练动作。
以下是动作和对应标签名：
| ID | Action Name                  | ID | Action Name                     | ID | Action Name           |
|----|------------------------------|----|---------------------------------|----|-----------------------|
| 01 | arm curl                     | 02 | bowling                        | 03 | basketball            |
| 04 | boxing                       | 05 | catch                          | 06 | clap                  |
| 07 | draw circle clockwise        | 08 | draw circle counter clockwise  | 09 | draw triangle         |
| 10 | draw X                       | 11 | jogging                        | 12 | knock                 |
| 13 | lunge                        | 14 | pickup and throw               | 15 | push                  |
| 16 | sit to stand                 | 17 | stand to sit                   | 18 | swipe left            |
| 19 | swipe right                  | 20 | tennis serve                   | 21 | tennis swing          |
| 22 | throw                        | 23 | walk                           | 24 | wave                  |  

每位受试者需要完成以上全部24个动作，每个动作10 遍，他们会被提前告知动作的完成方式，但是不会具体规范动作的细节和幅度，以保证数据集的多样性，增强使用该数据集训练模型的鲁棒性。

## Dataset download link:
https://pan.baidu.com/s/1Umf6nokTmGM3qahP816y-g?pwd=HITD password: HITD 
