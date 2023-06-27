This project aims to implement Real-Time Appearance-Based Mapping (RTAB Mapping) using the ZED Mini camera. The implementation will involve integrating April Tag detection, collecting relevant data, conducting qualitative analysis, and finally performing RTAB Mapping. Additionally, an iPhone app will be developed to visualize and interact with the generated maps.

**Software Tools used:**
- ROS noetic
-  PYTHON3
- RVIZ
- RTAB Map
- C++
- OpenCV
- apriltag_ros wrapper
- rtabmap_ros
- zed_ros_wrapper

**Quantitative Analysis:**
![image](https://github.com/KshamaDhaduti/RTAB-Mapping-ZED-Mini/assets/103454385/985b701a-ad60-4341-804c-14da7a542bce)
![image](https://github.com/KshamaDhaduti/RTAB-Mapping-ZED-Mini/assets/103454385/af86830a-1901-4995-ad41-a84683d7fbb8)
![image](https://github.com/KshamaDhaduti/RTAB-Mapping-ZED-Mini/assets/103454385/abf61563-9fef-4149-8df3-66ad0e965cc8)
![image](https://github.com/KshamaDhaduti/RTAB-Mapping-ZED-Mini/assets/103454385/db61c83f-036a-437d-beac-88d6758ab319)
![image](https://github.com/KshamaDhaduti/RTAB-Mapping-ZED-Mini/assets/103454385/bbb2d81a-b7ca-47a0-81fb-62e33acdac40)
![image](https://github.com/KshamaDhaduti/RTAB-Mapping-ZED-Mini/assets/103454385/0dfd6bfc-bf89-4919-a565-14ad10980067)
![image](https://github.com/KshamaDhaduti/RTAB-Mapping-ZED-Mini/assets/103454385/d9c51ddd-2e02-46cb-8884-234e18cb2393)


**Conclusion and Future Scope:**
- RTAB-Map demonstrated successful implementation for SLAM and standalone localization within a prebuilt map, with frequent observations of loop closures indicating good performance.
- Challenges were encountered with glass windows and doors, as RTAB-Map struggled to achieve accurate 3D reconstruction due to detecting and registering features from the other side of the glass.
- Illumination effects had a notable impact on RTAB-Map's performance, with excessive or insufficient lighting leading to poor quality 3D reconstructions.
- As a future scope, integrating April tag detection with RTAB-SLAM can enhance the system's capabilities, and implementing path planning on autonomous platforms can enable efficient navigation based on the generated maps.


