# 01-Avaline_D die bonding alarm code

| ID   | Alarm code | Information  English                                         | Information  Chinese                    |
| ---- | ---------- | ------------------------------------------------------------ | --------------------------------------- |
| 1    | AC0101     | Please stop the device before proceeding!                    | 请停止设备后在操作！                    |
| 2    | AC0102     | Entering illegal parameters                                  | 输入非法参数                            |
| 3    | AC0103     | Camera initialization failed, program cannot start....       | 相机初始化失败，程序无法启动.....       |
| 4    | AC0104     | The initialization of the motion control card failed, and the program cannot start.... | 运动控制卡初始化失败，程序无法启动..... |
| 5    | AC0105     | Failed to link ACS drive, program cannot start....           | 链接ACS驱动器失败，程序无法启动.....    |
| 6    | AC0106     | Door switch abnormal, device paused!                         | 门开关异常，设备暂停！                  |
| 7    | AC0107     | Abnormal temperature of welding head Y motor, equipment paused! | 焊头Y马达温度异常，设备暂停！           |
| 8    | AC0108     | Please close the door before starting!                       | 请关闭门后在启动！                      |
| 10   | AC0110     | Start failed, clearing the track!                            | 启动失败，在清轨道！                    |
| 11   | AC0111     | Startup failed, please reset before restarting!              | 启动失败，请复位后再启动！              |
| 12   | AC0112     | The window is already open, there is no need to open it again | 窗口已打开,无需重复打开                 |
| 13   | AC0113     | Failed to create PR, the detection module is not initialized! | 创建PR失败，检测模块未初始化！          |
| 14   | AC0114     | Feed Y-axis not in safe position                             | 入料Y轴不在安全位                       |
| 15   | AC0115     | Please bind the header first for initialization              | 请先绑头初始化                          |
| 16   | AC0116     | Please initialize the stripe first                           | 请先条带初始化                          |
| 17   | AC0117     | Please close the door before proceeding!                     | 请关闭门后在操作！                      |
| 18   | AC0118     | Pause button pressed!                                        | 暂停按钮按下！                          |
| 19   | AC0119     | Servo motor enable, please wait!                             | 伺服电机加使能中，请稍等！              |
| 20   | AC0120     | Reset failed!                                                | 复位失败！                              |
| 21   | AC0121     | Please stop before resetting!                                | 请停止后再复位！                        |
| 22   | AC0122     | Please log in first                                          | 请先登录                                |
| 23   | AC0123     | No permissions                                               | 无权限                                  |


## LimitP

- 因为这部分绑定了硬件，所以这样设计
  
| ID   | Alarm code | Information  English                    | Information  Chinese |
| ---- | ---------- | --------------------------------------- | -------------------- |
| 1    | LimitP1    | Left dispensing X positive limit        | 左点胶X正限位        |
| 2    | LimitP2    | Left dispensing Y positive limit        | 左点胶Y正限位        |
| 3    | LimitP3    | Left dispensing Z positive limit        | 左点胶Z正限位        |
| 4    | LimitP4    | Positive limit of feeding Y-axis        | 入料Y轴正限位        |
| 5    | LimitP5    | null                                    | null                 |
| 6    | LimitP6    | null                                    | null                 |
| 7    | LimitP7    | null                                    | null                 |
| 8    | LimitP8    | Finger B motor positive limit           | 手指B电机正限位      |
| 9    | LimitP9    | Finger C motor positive limit           | 手指C电机正限位      |
| 10   | LimitP10   | Finger D motor positive limit           | 手指D电机正限位      |
| 11   | LimitP11   | null                                    | null                 |
| 12   | LimitP12   | null                                    | null                 |
| 13   | LimitP13   | Right dispensing X positive limit       | 右点胶X正限位        |
| 14   | LimitP14   | Right dispensing Y positive limit       | 右点胶Y正限位        |
| 15   | LimitP15   | Right dispensing Z positive limit       | 右点胶Z正限位        |
| 16   | LimitP16   | null                                    | null                 |
| 17   | LimitP17   | null                                    | null                 |
| 18   | LimitP18   | Positive limit of feeding and pushing   | 入料推料正限位       |
| 19   | LimitP19   | Wafer expansion positive limit          | Wafer扩片正限位      |
| 20   | LimitP20   | Positive limit of crystal disc rotation | 晶圆盘旋转正限位     |
| 21   | LimitP21   | null                                    | null                 |
| 22   | LimitP22   | Wafer loading frame Z positive limit    | Wafer加载料框Z正限位 |
| 23   | LimitP23   | null                                    | null                 |
| 24   | LimitP24   | null                                    | null                 |



## LimitN

- 因为这部分绑定了硬件，所以这样设计

| ID   | Alarm code | Information  English                    | Information  Chinese |
| ---- | ---------- | --------------------------------------- | -------------------- |
| 1    | LimitN1    | Left dispensing X negative limit        | 左点胶X负限位        |
| 2    | LimitN2    | Left dispensing Y negative limit        | 左点胶Y负限位        |
| 3    | LimitN3    | Left dispensing Z negative limit        | 左点胶Z负限位        |
| 4    | LimitN4    | Negative limit of feeding Y-axis        | 入料Y轴负限位        |
| 5    | LimitN5    | null                                    | null                 |
| 6    | LimitN6    | null                                    | null                 |
| 7    | LimitN7    | null                                    | null                 |
| 8    | LimitN8    | Finger B motor negative limit           | 手指B电机负限位      |
| 9    | LimitN9    | Finger C motor negative limit           | 手指C电机负限位      |
| 10   | LimitN10   | Finger D motor negative limit           | 手指D电机负限位      |
| 11   | LimitN11   | null                                    | null                 |
| 12   | LimitN12   | null                                    | null                 |
| 13   | LimitN13   | Right dispensing X negative limit       | 右点胶X负限位        |
| 14   | LimitN14   | Right dispensing Y negative limit       | 右点胶Y负限位        |
| 15   | LimitN15   | Right dispensing Z negative limit       | 右点胶Z负限位        |
| 16   | LimitN16   | null                                    | null                 |
| 17   | LimitN17   | null                                    | null                 |
| 18   | LimitN18   | Negative limit for feeding and pushing  | 入料推料负限位       |
| 19   | LimitN19   | Wafer expansion negative limit          | Wafer扩片负限位      |
| 20   | LimitN20   | Negative limit of crystal disc rotation | 晶圆盘旋转负限位     |
| 21   | LimitN21   | null                                    | null                 |
| 22   | LimitN22   | Wafer loading frame Z negative limit    | Wafer加载料框Z负限位 |
| 23   | LimitN23   | null                                    | null                 |
| 24   | LimitN24   | null                                    | null                 |



## Alm

- 因为这部分绑定了硬件，所以这样设计

| ID   | Alarm code | Information  English           | Information  Chinese |
| ---- | ---------- | ------------------------------ | -------------------- |
| 1    | Alm1       | Left dispensing X malfunction  | 左点胶X故障          |
| 2    | Alm2       | Left dispensing Y malfunction  | 左点胶Y故障          |
| 3    | Alm3       | Left dispensing Z malfunction  | 左点胶Z故障          |
| 4    | Alm4       | null                           | null                 |
| 5    | Alm5       | null                           | null                 |
| 6    | Alm6       | null                           | null                 |
| 7    | Alm7       | Finger A motor malfunction     | 手指A电机故障        |
| 8    | Alm8       | Finger B motor malfunction     | 手指B电机故障        |
| 9    | Alm9       | Finger C motor malfunction     | 手指C电机故障        |
| 10   | Alm10      | Finger D motor malfunction     | 手指D电机故障        |
| 11   | Alm11      | null                           | null                 |
| 12   | Alm12      | null                           | null                 |
| 13   | Alm13      | Right dispensing X malfunction | 右点胶X故障          |
| 14   | Alm14      | Right dispensing Y malfunction | 右点胶Y故障          |
| 15   | Alm15      | Right dispensing Z malfunction | 右点胶Z故障          |
| 16   | Alm16      | null                           | null                 |
| 17   | Alm17      | null                           | null                 |
| 18   | Alm18      | null                           | null                 |
| 19   | Alm19      | null                           | null                 |
| 20   | Alm20      | null                           | null                 |
| 21   | Alm21      | null                           | null                 |
| 22   | Alm22      | Wafer loading frame Z fault    | Wafer加载料框Z故障   |
| 23   | Alm23      | null                           | null                 |
| 24   | Alm24      | null                           | null                 |



## ALimitP（程序下标错误）

![](https://easyimage1.ghuang.top/i/2024/04/18/214146-1.webp)

- 因为这部分绑定了硬件，所以这样设计

| ID   | Alarm code | Information  English                    | Information  Chinese |
| ---- | ---------- | --------------------------------------- | -------------------- |
| 1    | ALimitP1   | Welding head Z motor positive limit     | 焊头Z电机正限位      |
| 2    | ALimitP2   | Welding head Y motor positive limit     | 焊头Y电机正限位      |
| 3    | ALimitP3   | Camera Y motor positive limit           | 相机Y电机正限位      |
| 4    | ALimitP4   | Welding head X motor positive limit     | 焊头X电机正限位      |
| 5    | ALimitP5   | Pushing motor positive limit            | 推顶电机正限位       |
| 6    | ALimitP6   | null                                    | null                 |
| 7    | ALimitP7   | Welding head A motor positive limit     | 焊头A电机正限位      |
| 8    | ALimitP8   | null                                    | null                 |
| 9    | ALimitP9   | Crystal disc X motor positive limit     | 晶圆盘X电机正限位    |
| 10   | ALimitP10  | null                                    | null                 |
| 11   | ALimitP11  | Positive limit of Y-motor on wafer disc | 晶圆盘Y电机正限位    |
| 12   | ALimitP12  | null                                    | null                 |



## ALimitN（程序下标错误）

![](https://easyimage1.ghuang.top/i/2024/04/18/214146-1.webp)

- 因为这部分绑定了硬件，所以这样设计

| ID   | Alarm code | Information  English                   | Information  Chinese |
| ---- | ---------- | -------------------------------------- | -------------------- |
| 1    | ALimitN1   | Crystal disc X motor positive limit    | 焊头Z电机负限位      |
| 2    | ALimitN2   | Welding head Y motor negative limit    | 焊头Y电机负限位      |
| 3    | ALimitN3   | Camera Y motor negative limit          | 相机Y电机负限位      |
| 4    | ALimitN4   | Welding head X motor negative limit    | 焊头X电机负限位      |
| 5    | ALimitN5   | Pushing motor negative limit           | 推顶电机负限位       |
| 6    | ALimitN6   | null                                   | null                 |
| 7    | ALimitN7   | Welding head A motor negative limit    | 焊头A电机负限位      |
| 8    | ALimitN8   | null                                   | null                 |
| 9    | ALimitN9   | Negative limit of crystal disc X motor | 晶圆盘X电机负限位    |
| 10   | ALimitN10  | null                                   | null                 |
| 11   | ALimitN11  | Negative limit of Y motor on wafer     | 晶圆盘Y电机负限位    |
| 12   | ALimitN12  | null                                   | null                 |



## AAlm（程序下标错误）

![](https://easyimage1.ghuang.top/i/2024/04/18/214146-1.webp)

- 因为这部分绑定了硬件，所以这样设计

| ID   | Alarm code | Information  English              | Information  Chinese |
| ---- | ---------- | --------------------------------- | -------------------- |
| 1    | AAlm1      | Welding head Z motor fault        | 焊头Z电机故障        |
| 2    | AAlm2      | Welding head Y motor failure      | 焊头Y电机故障        |
| 3    | AAlm3      | Camera Y motor fault              | 相机Y电机故障        |
| 4    | AAlm4      | Welding head X motor failure      | 焊头X电机故障        |
| 5    | AAlm5      | Pushing motor fault               | 推顶电机故障         |
| 6    | AAlm6      | Welding head torque motor failure | 焊头力扭电机故障     |
| 7    | AAlm7      | Welding head A motor failure      | 焊头A电机故障        |
| 8    | AAlm8      | null                              | null                 |
| 9    | AAlm9      | Crystal disc X motor failure      | 晶圆盘X电机故障      |
| 10   | AAlm10     | null                              | null                 |
| 11   | AAlm11     | Wafer disk Y motor failure        | 晶圆盘Y电机故障      |
| 12   | AAlm12     | null                              | null                 |

