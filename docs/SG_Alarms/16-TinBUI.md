# 16-TinBUI die bonding alarm code

| ID   | Name   | description                                           | setEventID | clearEventID | alarm code | Text                                                   |
| ---- | ------ | ----------------------------------------------------- | ---------- | ------------ | ---------- | ------------------------------------------------------ |
| 1    | AC1601 | 你确定加卸载蓝膜吗？                                | 1001       | 2001         | 6          | Are you sure to load and unload the blue film?        |
| 2    | AC1602 | 输入非法参数！                                       | 1001       | 2001         | 6          | Illegal parameter input!                               |
| 3    | AC1603 | 提示&输入非法参数！                                 | 1001       | 2001         | 6          | Prompt& input illegal parameter!                      |
| 4    | AC1604 | 提示&整体修改设定了非法参数！                       | 1001       | 2001         | 6          | Prompt& the overall modification has set illegal parameters |
| 5    | AC1605 | 请初始化后在操作！                                   | 1001       | 2001         | 6          | Please initialize before proceeding!                  |
| 6    | AC1606 | 请停止后在操作！                                     | 1001       | 2001         | 6          | Please stop before proceeding!                        |
| 7    | AC1607 | 请选择坐标点！                                       | 1001       | 2001         | 6          | Please select a coordinate point!                     |
| 8    | AC1608 | 右点胶XY电机运动超时！                               | 1001       | 2001         | 6          | Right dispensing XY motor movement timeout!           |
| 9    | AC1609 | 提示&请暂停后在操作！                               | 1001       | 2001         | 6          | Prompt& please pause before proceeding!               |
| 10   | AC1610 | 提示&右点胶Z不在原位                                | 1001       | 2001         | 6          | Reminder& right dispensing Z is not in place          |
| 11   | AC1611 | 提示&窗口已打开&请勿重复操作                     | 1001       | 2001         | 6          | Prompt& the window is already open& please do not repeat the operation |
| 12   | AC1612 | 右点胶Z不在原位                                     | 1001       | 2001         | 6          | Right dispensing Z not in place                       |
| 13   | AC1613 | 右点胶测高信号异常！                                 | 1001       | 2001         | 6          | The right glue dispensing height measurement signal is abnormal! |
| 14   | AC1614 | 获取右点胶图像Mark点十字中心异常&标定失败！         | 1001       | 2001         | 6          | The center of the Mark dot cross in obtaining the right glue image is abnormal& calibration failed! |
| 15   | AC1615 | Z下降时间不能大于1000ms                            | 1001       | 2001         | 6          | Z descent time cannot exceed 1000ms                   |
| 16   | AC1616 | Z下降时间不能小于10ms                              | 1001       | 2001         | 6          | Z descent time cannot be less than 10ms               |
| 17   | AC1617 | Z上升时间不能大于1000ms                            | 1001       | 2001         | 6          | Z rise time cannot exceed 1000ms                      |
| 18   | AC1618 | Z上升时间不能小于10ms                              | 1001       | 2001         | 6          | Z rise time cannot be less than 10ms                  |
| 19   | AC1619 | XYZ数据整体修改设定了非法参数！                     | 1001       | 2001         | 6          | The overall modification of XYZ data has set illegal parameters! |
| 20   | AC1620 | 点胶1Z不在原位                                     | 1001       | 2001         | 6          | Dispensing 1Z is not in place                         |
| 21   | AC1621 | X偏移不能大于8mm                                   | 1001       | 2001         | 6          | X offset cannot be greater than 8mm                   |
| 22   | AC1622 | X偏移不能小于-8mm                                  | 1001       | 2001         | 6          | The X offset cannot be less than -8mm                 |
| 23   | AC1623 | Y偏移不能大于8mm                                   | 1001       | 2001         | 6          | Y offset cannot be greater than 8mm                   |
| 24   | AC1624 | Y偏移不能小于-8mm                                  | 1001       | 2001         | 6          | Y offset cannot be less than -8mm                     |
| 25   | AC1625 | X整体偏移不能大于8mm                               | 1001       | 2001         | 6          | The overall offset of X cannot be greater than 8mm    |
| 26   | AC1626 | X整体偏移不能小于-8mm                              | 1001       | 2001         | 6          | The overall offset of X cannot be less than -8mm      |
| 27   | AC1627 | Y整体偏移不能大于8mm                               | 1001       | 2001         | 6          | The overall offset of Y cannot be greater than 8mm    |
| 28   | AC1628 | Y整体偏移不能小于-8mm                              | 1001       | 2001         | 6          | The overall offset of Y cannot be less than -8mm      |
| 29   | AC1629 | Z整体偏移向上不能大于2mm                           | 1001       | 2001         | 6          | Z overall offset with a minimum upward offset of 0mm |
| 30   | AC1630 | Z整体偏移向上偏移最小0mm                           | 1001       | 2001         | 6          | Z overall offset with a minimum upward offset of 0mm |
| 31   | AC1631 | 窗口已打开&请勿重复操作                           | 1001       | 2001         | 6          | The window is already open& please do not repeat the operation |
| 32   | AC1632 | 夹角超出±10°&标定失败！                           | 1001       | 2001         | 6          | The included angle exceeds ± 10 °& calibration failed! |



```sh
9601=AC1601,Are you sure to load and unload the blue film?,Are you sure to load and unload the blue film?,1001,2001,6,
9602=AC1602,Illegal parameter input!,Illegal parameter input!,1001,2001,6,
9603=AC1603,Prompt& input illegal parameter!,Prompt& input illegal parameter!,1001,2001,6,
9604=AC1604,Prompt& the overall modification has set illegal parameters,Prompt& the overall modification has set illegal parameters,1001,2001,6,
9605=AC1605,Please initialize before proceeding!,Please initialize before proceeding!,1001,2001,6,
9606=AC1606,Please stop before proceeding!,Please stop before proceeding!,1001,2001,6,
9607=AC1607,Please select a coordinate point!,Please select a coordinate point!,1001,2001,6,
9608=AC1608,Right dispensing XY motor movement timeout!,Right dispensing XY motor movement timeout!,1001,2001,6,
9609=AC1609,Prompt& please pause before proceeding!,Prompt& please pause before proceeding!,1001,2001,6,
9610=AC1610,Reminder& right dispensing Z is not in place,Reminder& right dispensing Z is not in place,1001,2001,6,
9611=AC1611,Prompt& the window is already open& please do not repeat the operation,Prompt& the window is already open& please do not repeat the operation,1001,2001,6,
9612=AC1612,Right dispensing Z not in place,Right dispensing Z not in place,1001,2001,6,
9613=AC1613,The right glue dispensing height measurement signal is abnormal!,The right glue dispensing height measurement signal is abnormal!,1001,2001,6,
9614=AC1614,The center of the Mark dot cross in obtaining the right glue image is abnormal& calibration failed!,The center of the Mark dot cross in obtaining the right glue image is abnormal& calibration failed!,1001,2001,6,
9615=AC1615,Z descent time cannot exceed 1000ms,Z descent time cannot exceed 1000ms,1001,2001,6,
9616=AC1616,Z descent time cannot be less than 10ms,Z descent time cannot be less than 10ms,1001,2001,6,
9617=AC1617,Z rise time cannot exceed 1000ms,Z rise time cannot exceed 1000ms,1001,2001,6,
9618=AC1618,Z rise time cannot be less than 10ms,Z rise time cannot be less than 10ms,1001,2001,6,
9619=AC1619,The overall modification of XYZ data has set illegal parameters!,The overall modification of XYZ data has set illegal parameters!,1001,2001,6,
9620=AC1620,Dispensing 1Z is not in place,Dispensing 1Z is not in place,1001,2001,6,
9621=AC1621,X offset cannot be greater than 8mm,X offset cannot be greater than 8mm,1001,2001,6,
9622=AC1622,The X offset cannot be less than -8mm,The X offset cannot be less than -8mm,1001,2001,6,
9623=AC1623,Y offset cannot be greater than 8mm,Y offset cannot be greater than 8mm,1001,2001,6,
9624=AC1624,Y offset cannot be less than -8mm,Y offset cannot be less than -8mm,1001,2001,6,
9625=AC1625,The overall offset of X cannot be greater than 8mm,The overall offset of X cannot be greater than 8mm,1001,2001,6,
9626=AC1626,The overall offset of X cannot be less than -8mm,The overall offset of X cannot be less than -8mm,1001,2001,6,
9627=AC1627,The overall offset of Y cannot be greater than 8mm,The overall offset of Y cannot be greater than 8mm,1001,2001,6,
9628=AC1628,The overall offset of Y cannot be less than -8mm,The overall offset of Y cannot be less than -8mm,1001,2001,6,
9629=AC1629,Z overall offset with a minimum upward offset of 0mm,Z overall offset with a minimum upward offset of 0mm,1001,2001,6,
9630=AC1630,Z overall offset with a minimum upward offset of 0mm,Z overall offset with a minimum upward offset of 0mm,1001,2001,6,
9631=AC1631,The window is already open& please do not repeat the operation,The window is already open& please do not repeat the operation,1001,2001,6,
9632=AC1632,The included angle exceeds ± 10 °& calibration failed!,The included angle exceeds ± 10 °& calibration failed!,1001,2001,6,
```