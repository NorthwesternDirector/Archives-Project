## 青岛市城建档案馆项目
* 该项目主要以 `档案数字化` 为目标，旨在解决纸质档案查询时带来的诸多时效性问题
#### 项目涉及技术
* `HTML` `CSS` `JS` `jQuery` `Bootstrap` `OpenLayers` `Tabulator` `ASP.NET MVC` `C#` `SQL Server`

> <font color=#DC143C size=4> 说明：由于项目内容涉密，所以无法上传代码与资源，以下主要以截图说明本人所涉及的开发内容</font> 

##### 档案文件的地理信息化

1. 根据档案挂接的地理坐标属性，将其表示的地理范围可视化在地图上，并添加点击响应事件
    <div align=center><img width=750px  src="https://github.com/NorthwesternDirector/Archives-Project/blob/master/captures/project%20(1).png"></div>
    <div align=center><img width=750px  src="https://github.com/NorthwesternDirector/Archives-Project/blob/master/captures/project%20(5).png"></div>
2. 地图缩放至某等级后可显示其档案序列编号，并可进行模糊搜索编号
    <div align=center><img width=750px  src="https://github.com/NorthwesternDirector/Archives-Project/blob/master/captures/project%20(4).png"></div>
3. 绘制坐标范围，并将其与工程挂接，可批量导入工程后等待挂接
    <div align=center><img width=750px  src="https://github.com/NorthwesternDirector/Archives-Project/blob/master/captures/project%20(7).png"></div>
    <div align=center><img width=750px  src="https://github.com/NorthwesternDirector/Archives-Project/blob/master/captures/project%20(9).png"></div>
4. 后期可根据提供的地理属性shp文件直接挂载系统内的档案数据，无需手动绘制（20190803）

##### 该模块为用户进行档案查询提供了另一个维度，之前用户仅可根据属性字段进行档案检索查询，该模块开发后，用户便可根据档案具体的地理位置进行查询。
