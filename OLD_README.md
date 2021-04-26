## Products and Environment: Hardware RF|Wireless
## Software: LabVIEW  Driver/NI RF Device Drivers  
## Operating System: Windows 10  
## Programming Language: .NET/C Sharp/LabVIEW 2020


**此示例演示如何使用Windows 10 BLE本机库与BLE设备(智能手表、灯泡或任何支持BLE的设备)通信。 这不需要任何BLE加密狗来与BLE设备通信。 它使用windows10蓝牙堆栈及其本地库与BLE设备通信。** 
>Description This example demonstrate on how to use the windows 10 BLE native library to communicate with BLE devices (Smart watch, bulb or any device which support BLE). This does not need any BLE dongle to communicate with BLE devices. It uses the windows 10 bluetooth stack and its native library to communicate with BLE devices. 

**在C#平台上开发了与Windows10BLE库交互的动态链接库，并利用.Net构造函数节点将动态链接库集成到LabVIEW中。** 
> Developed the DLL to interact with windows 10 BLE library in C# platform and integrated the dll into LabVIEW by using .Net constructor node. 

**下面演示了通用Windows平台(UWP)的蓝牙通用属性(GATT)客户端API的用法，以及常见GATT客户端任务的示例代码：查询附近设备连接到设备枚举设备支持的服务和特征特征值更改时读取和写入特征订阅通知**
> Here demonstrates usage of the Bluetooth Generic Attribute (GATT) Client APIs for Universal Windows Platform (UWP), along with sample code for common GATT client tasks: Query for nearby devices Connect to device Enumerate the supported services and characteristics of the device Read and write to a characteristic Subscribe for notifications when characteristic value change

**使用BLE库中提供的方法如下：** 
> How to Use Following are the methods available in BLE library:  

**1. BLE_Initialize.vi-初始化DLL
2. BLE_StartWatcher.vi-收听附近的BLE设备广播 
3. BLE_Get_WatcherResponse.vi-从BLE广播中获取制造商数据、BLE地址 
4. BLE_Get_WatcherReceivedData.vi-解码WatcherResponse得到的数据 
5. BLE_StopWatcher.vi-停止从附近的BLE设备获取广播
6. BLE_Request_Connect.vi-启动到BLE设备的连接，并从BLE设备返回连接状态和GATT服务列表的响应
7. BLE_Get_ServicesUUIDs_Property.vi-从BLE设备获取GATT服务UUIDs和属性UUIDs
8. BLE_Notify.vi-从BLE设备启动UUID的BLE通知
9. BLE_Notify_Listener.vi-从BLE设备获取UUID通知 
10. BLE_Read_Characteristic.vi-读取BLE设备的UUID 
11. BLE_Read_CharacteristicArray.vi-读取BLE设备的UUIDs数组 
12. BLE_Request_ServiceUUIDs.vi-获取服务UUIDs
13. BLE_Write.vi-写入BLE设备的UUIDs
14. BLE_Write_Without_Response.vi-写入BLE设备的无响应UUIDs，不返回响应** 
> BLE_Initialize.vi - Initialize the DLL  > BLE_StartWatcher.vi - listening advertisement of near by BLE devices  > BLE_Get_WatcherResponse.vi - Gets the manufacture data, BLE address from BLE advertisement  > BLE_Get_WatcherReceivedData.vi - Decodes the watcher response  > BLE_StopWatcher.vi - Stop getting advertisement from near by BLE devices  > BLE_Request_Connect.vi - Initiates the connection to BLE device and returns with response of connection status and GATT Services list from BLE device  > BLE_Get_ServicesUUIDs_Property.vi - Gets the GATT service UUIDs and Property UUIDS from BLE device  > BLE_Notify.vi - Initiate the BLE notification of UUIDs from BLE device  > BLE_Notify_Listener.vi - Gets the notification of UUIDs from BLE device  > BLE_Read_Characteristic.vi - Reads the UUIDs of BLE device  > BLE_Read_CharacteristicArray.vi - Reads the array of UUIDs of BLE device > BLE device BLE_Request_ServiceUUIDs.vi - Get the Service UUIDs  > BLE_Write.vi - Write the UUIDs of BLE device  > BLE_Write_Without_Response.vi - Write the without response UUIDs of BLE device and not return response 

**附加:信息将调试日志设置为TRUE时，C#库在C盘下创建了BLE日志文件** 
> Additional Information When setting the debug logs to true, C# library created the BLE log files under C drive

**开发环境：LabVIEW 2020 32位、 操作系统：Win 10 64位** 
> Development Environment: LabVIEW 2020 32 Bit | OS: Win 10 64 bit

**在HLD中添加了示例代码，其中用户在运行之前必须更改BLE地址。 运行监视器后可以获取BLE地址**
> Added the Example code in HLD where user has to change the BLE address before run. The BLE address can be get after running the watcher.