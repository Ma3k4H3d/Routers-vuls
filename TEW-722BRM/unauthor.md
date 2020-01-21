#### Vulnerability Detail
There are several pages in TrendNet TEW-722BRM can be accessed without authorization, which could lead to the leak of vital private information.These pages are "status/status_statistic.shtml", "status/traffic_log.shtml", "status/status_vdsl_statistic.shtml". When processed, it exposes the statistic, traffic log and DSL statistic of router.

#### PoC
http://targetip/status/status_statistic.shtml

![poc](https://github.com/dahua966/Routers-vuls/blob/master/TEW-722BRM/status_statistic.jpg)

http://targetip/status/traffic_log.shtml

![poc](https://github.com/dahua966/Routers-vuls/blob/master/TEW-722BRM/traffic_log.jpg)

http://targetip/status/status_vdsl_statistic.shtml

![poc](https://github.com/dahua966/Routers-vuls/blob/master/TEW-722BRM/DSL_statistic.jpg)

#### Acknowledgement
Thanks to the partners who discovered the vulnerability together：

Wei Xie

Zhen-hua Wang

En-Ze Wang
