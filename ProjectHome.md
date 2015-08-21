Bi-directional tool for bridging an IBM MQSeries and Microsoft MSMQ queue.
This utility could be used for pseudo-realtime communication from WMQ to MSQM (or from MSMQ to WMQ).

Requirements:
  * [Windows 7 or Windows 2008 R2](http://windows.microsoft.com/en-us/windows/home)
  * [IBM Websphere MQ Client For .Net](http://www-01.ibm.com/software/integration/wmq/clients/)
  * [MSMQ](http://msdn.microsoft.com/en-us/library/aa967729.aspx)
  * [Visual Studio 2010 Express Edition](http://www.microsoft.com/visualstudio/eng/products/visual-studio-2010-express)
  * Visual C# .Net

Features:
  * From WMQ to MSMQ
  * From MSMQ to WMQ
  * It uses a two-phase-commit mechanism to simulate an atomic queue operation (get/put)

![http://bridge-wmq-msmq.googlecode.com/svn/wiki/inbound.png](http://bridge-wmq-msmq.googlecode.com/svn/wiki/inbound.png)

![http://bridge-wmq-msmq.googlecode.com/svn/wiki/outbound.png](http://bridge-wmq-msmq.googlecode.com/svn/wiki/outbound.png)

[![](http://www4.clustrmaps.com/stats/maps-no_clusters/code.google.com-p-bridge-wmq-msmq--thumb.jpg)](http://www4.clustrmaps.com/user/59f108703)