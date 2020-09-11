# OpenHarmony轻内核文件系统<a name="ZH-CN_TOPIC_0000001051611726"></a>

OpenHarmony轻内核支持的文件系统有：VFS（虚拟文件系统）、NFS、RAMFS、FAT、JFFS2。

**各个文件系统功能概述：**

**表 1**  文件系统功能概述

<a name="table6330194819415"></a>
<table><thead align="left"><tr id="row6331184864111"><th class="cellrowborder" valign="top" width="11.559999999999999%" id="mcps1.2.3.1.1"><p id="p17644161411438"><a name="p17644161411438"></a><a name="p17644161411438"></a>文件系统</p>
</th>
<th class="cellrowborder" valign="top" width="88.44%" id="mcps1.2.3.1.2"><p id="p116441414184312"><a name="p116441414184312"></a><a name="p116441414184312"></a>功能特点概述</p>
</th>
</tr>
</thead>
<tbody><tr id="row371213562318"><td class="cellrowborder" valign="top" width="11.559999999999999%" headers="mcps1.2.3.1.1 "><p id="p37130569316"><a name="p37130569316"></a><a name="p37130569316"></a>VFS</p>
</td>
<td class="cellrowborder" valign="top" width="88.44%" headers="mcps1.2.3.1.2 "><p id="p1771335615316"><a name="p1771335615316"></a><a name="p1771335615316"></a>VFS是Virtual File System（虚拟文件系统）的缩写，它不是一个实际的文件系统，而是一个异构文件系统之上的软件粘合层，为用户提供统一的类Unix文件操作接口。</p>
</td>
</tr>
<tr id="row189255844219"><td class="cellrowborder" valign="top" width="11.559999999999999%" headers="mcps1.2.3.1.1 "><p id="p1564481494319"><a name="p1564481494319"></a><a name="p1564481494319"></a>NFS</p>
</td>
<td class="cellrowborder" valign="top" width="88.44%" headers="mcps1.2.3.1.2 "><p id="p764561414434"><a name="p764561414434"></a><a name="p764561414434"></a>NFS是Network File System（网络文件系统）的缩写。它最大的功能是可以通过网络，让不同的机器、不同的操作系统彼此分享其他用户的文件。</p>
</td>
</tr>
<tr id="row17332194820411"><td class="cellrowborder" valign="top" width="11.559999999999999%" headers="mcps1.2.3.1.1 "><p id="p2064561415435"><a name="p2064561415435"></a><a name="p2064561415435"></a>RAMFS</p>
</td>
<td class="cellrowborder" valign="top" width="88.44%" headers="mcps1.2.3.1.2 "><p id="p12646614204320"><a name="p12646614204320"></a><a name="p12646614204320"></a>RAMFS是一种基于RAM的文件系统。RAMFS文件系统把所有的文件都放在RAM中，所以读/写操作发生在RAM中，避免了对存储器的读写损耗，也提高了数据读写速度。RAMFS是基于RAM的动态文件系统的一种存储缓冲机制。</p>
</td>
</tr>
<tr id="row16332174894116"><td class="cellrowborder" valign="top" width="11.559999999999999%" headers="mcps1.2.3.1.1 "><p id="p1864571410433"><a name="p1864571410433"></a><a name="p1864571410433"></a>FAT</p>
</td>
<td class="cellrowborder" valign="top" width="88.44%" headers="mcps1.2.3.1.2 "><p id="p364511141434"><a name="p364511141434"></a><a name="p364511141434"></a>FAT文件系统是File Allocation Table（文件配置表）的简称，有FAT12、FAT16、FAT32。在可移动存储介质(U盘、SD卡、移动硬盘等)上多使用FAT文件系统，使设备与Windows、Linux等桌面系统之间保持很好的兼容性。</p>
</td>
</tr>
<tr id="row1880218157414"><td class="cellrowborder" valign="top" width="11.559999999999999%" headers="mcps1.2.3.1.1 "><p id="p19645814144312"><a name="p19645814144312"></a><a name="p19645814144312"></a>JFFS2</p>
</td>
<td class="cellrowborder" valign="top" width="88.44%" headers="mcps1.2.3.1.2 "><p id="p8645161454314"><a name="p8645161454314"></a><a name="p8645161454314"></a>JFFS2是Journalling Flash File System Version 2（日志文件系统）的缩写，是MTD设备上的日志型文件系统。主要应用于对NOR_FLASH闪存的文件管理。<span id="text236315521580"><a name="text236315521580"></a><a name="text236315521580"></a>OpenHarmony</span>内核的JFFS2支持多分区。</p>
</td>
</tr>
</tbody>
</table>

-   **[VFS](VFS.md)**  

-   **[NFS](NFS.md)**  

-   **[RAMFS](RAMFS.md)**  

-   **[FAT](FAT.md)**  

-   **[JFFS2](JFFS2.md)**  


