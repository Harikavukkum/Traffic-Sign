# DEEP LEARNING BASED FRAMEWORK FOR ROBUST TRAFFIC SIGN DETECTION UNDER CHALLENGING WEATHER CONDITIONS

**ABSTRACT**
Thanks to the rapid development of computer vision and deep learning technologies, advanced
driver assistance systems (ADAS) have recently become widespread. These systems aim to
increase driving safety and reduce the number of traffic accidents. Modern cars usually have
ADAS systems integrated into their electronics, but other vehicles do not have such an integrated
system. This paper presents a portable and image-based ADAS system for real-time detection of
traffic signs, vehicles, and pedestrians. To realize real-time detection, the developed system uses
the YOLO v5 algorithm. This single-stage detector is very popular as it has high detection speed
and accuracy. The model was trained on the study-specific datasets to analyze the developed
system. Then, the implementation metrics were calculated to evaluate the training and testing
performances of the model. In addition, the model was compared in low-power,
high-performance embedded platforms and in a computer to measure the real-time performance.
Considering the excellent accuracy and high speed, this study will guide researchers in
demonstrating the efficiency and suitability of real-time road object detection with YOLO v5 on
mobile platforms.
KEYWORDS: Deep Learning, LSTM, real-time, TSDR, ADAS, Neural Networks,
YOLOv5

**INTRODUCTION**
As the population continues to grow, the number of vehicles on the roads is increasing at a rapid pace. This
surge in traffic volume inevitably leads to a higher risk of accidents and fatalities. Various factors such as
drowsiness, fatigue, and road conditions contribute to these risks. To address this issue, numerous studies and
solutions have been developed over time to mitigate accident risks and enhance driving safety.
The advancements in technology have played a crucial role in the development of systems aimed at improving
driving safety. These technologies collectively form the infrastructure of Advanced Driver Assistance Systems
(ADAS) and autonomous driving systems. ADAS systems are designed to assist drivers and vehicles in
detecting and responding to dangerous traffic situations accurately and promptly. They have become a
significant area of research and development, driven by the need to enhance safety and comfort in the
automotive industry.
The development of ADAS systems incorporates various technologies. Among these, camera-based solutions
offer notable advantages, including cost-effectiveness. With the rapid advancements in computer vision
technologies, processing and analyzing images from cameras have become increasingly efficient and accurate.
Beyond the vehicle itself, ADAS systems also involve external environment sensing, which entails gathering
information about the surrounding driving environment. This information encompasses nearby vehicles,
pedestrians, traffic signs, traffic lights, and certain objects. However, the quality of environmental information
perception can be influenced by external factors such as weather conditions, road conditions, and lighting
conditions. Consequently, these factors need to be taken into consideration during the design and development
of ADAS systems.
In summary, the rising number of vehicles on the road poses increased risks of accidents and fatalities. ADAS
and autonomous driving systems have emerged as essential solutions to address these risks. Camera-based
solutions, leveraging computer vision technologies, offer cost advantages and efficient image processing
capabilities. Furthermore, the design of ADAS systems must account for external factors that affect the
perceptual quality of environmental information, such as weather, road conditions, and lighting
