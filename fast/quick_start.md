# 快速入门

&emsp;&emsp;优睿达UReach可以为客户提供快速、便捷、高效、合规的跨境专线网络加速方案，解决公网网络延迟较大、丢包率较高，稳定性较差的问题。轻松实现跨国团队实时协作，全球业务高效进行。

## **步骤一：申请UReach智能网关**

智能网关硬件暂不支持线上申请，如需申请请联系客户经理。

## **步骤二：UReach智能网关初始化配置**

1. 从UCloud控制台进入到UReach产品页面在智能网关管理页面找到需要进行配置的设备，点击详情进入详情页。

![quick_start1](/images/quick_start1.png)

2. 从详情页中分别对WAN、LAN、Wi-Fi进行初始化配置。
![quick_start2](/images/quick_start2.png)

3.  进行WAN口网络配置，配置完成后点击“确定”按钮保存配置。

![quick_start3](/images/quick_start3.png)

| 字段名称  | 字段说明                                       |
| :-------- | ---------------------------------------------- |
| 设备WAN口 | 选择物理WAN口                                  |
| MTU       | 最大运输单元，范围为 [512,1500]                |
| 接入方式  | 接入云上网络的方式                             |
| 连接类型  | WAN口接入网络的方式                            |
| SNAT      | 开启后可以将UCPE局域网的内网地址转换成公网地址 |

4. 进行LAN口网络配置，配置完成后点击“确定”按钮保存配置。

![quick_start4](/images/quick_start4.png)

| 字段名称  | 字段说明                                       |
| :------------ | ------------------------------------------------------------ |
| MTU           | 最大运输单元，范围为 [512,1500]                              |
| LAN侧网关配置 | UCPE网关的LAN口网络配置，生效于UCPE全部LAN口                 |
| DHCP-Server   | 开启后UCPE下游设备可通过 DHCP 协议动态获取 IP 地址           |
| DHCP地址池    | 期望为UCPE下游设备DHCP分配的IP地址池，该地址池范围应与LAN侧网关配置同段 |
| 地址租期      | DHCP为某一设备分配的IP地址过期时间，超过此时间未续租则需要重新分配IP地址 |

5. 进行Wi-Fi网络配置，配置完成后点击“确定”按钮保存配置。

![quick_start5](/images/quick_start5.png)

![quick_start6](/images/quick_start6.png)

## **步骤三：创建UReach加速线路**

1. 从UCloud控制台进入到UReach产品页面点击加速线路管理，创建加速线路。

![quick_start7](/images/quick_start7.png)

2. 按需选择加速线路配置，并将加速线路绑定到UReach智能网关硬件上（必选），点击立即购买，并确定订单。

![quick_start8](/images/quick_start8.png)

3. 返回智能网关管理和加速线路管理页面，确认线路和网关绑定关系，确认无误之后即可将智能网关通电并部署到本地网络中实现UReach网络加速。

![quick_start9](/images/quick_start9.png)

![quick_start10](/images/quick_start10.png)
