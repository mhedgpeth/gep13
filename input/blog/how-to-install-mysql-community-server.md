---
Title: How to install MySQL Community Server
Published: 4/1/2013
Tags:
- chocolatey
- database
- mysql
- Series
---

# What is MySQL Community Server?

>MySQL Community Edition is the freely downloadable version of the world's most popular open source database. It is available under the GPL license and is supported by a huge and active community of open source developers.

If you want to find out more information about MySQL Community Server, you can find it [here](http://www.mysql.com/products/community/).

# Installation Steps

**NOTE: **The following installation steps and screenshots were taken from a virtual machine   with Windows Server 2008 R2 Service Pack 1, running in Hyper-V on a Windows 8 Host Machine.

1. [Install chocolatey nuget](http://gep13.me/S8ZnDT)
1. Open PowerShell as an Administrator
1. Hit the Start button
1. Type "PowerShell"
1. Right click on the "Windows PowerShell" icon
1. Click "Run as administrator"
1. Type "cinst mysql" and press the "Enter" key
1. The installation of MySQL Community Server will begin
1. The installation will complete

You can see screenshots of each of these steps in the galley at the bottom of this blog post.

# Post Installation Checks

The installation of MySQL Community Server will have added a new Windows Service, you can verify that this is there, and started by doing the following:

1. Hit the Start button
1. Type "services.msc" and press enter
1. In the window that opens up, scroll until to see MySQL
1. Verify that this service is started.

# Installation Screenshots

[gallery ids="1746,1747,1748,1749,1745,1744"]