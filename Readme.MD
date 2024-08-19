# NewLife.Melsec - 三菱PLC

三菱PLC协议  

## FxLinks协议
FxLinks协议常用指令：
1. ENQ05询问，BR位读取，BW字读取，BW位写入，WW字写入，以校验和结束
2. STX02读取响应，包括位读取和字读取的响应数据，以ETX03和校验和结束
3. ACK确认写入响应，包括位写入和字写入
4. NAK不确认写入响应，包括位写入和字写入
