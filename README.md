
读取Excel表格将其中的数据通过Python脚本生成Json文件以及对应的C#实体类
===

## excel2json2C#文件夹<br>

* 其中是将Excel文件转换为Json的Python小工具<br>
* 件夹内包含一个Enemypropertytable.xlsx文件供测试<br>
* 将Enemypropertytable.xlsx文件拖拽到相同路径下的Change.bat批处理工具上即可生成相应的Json文件以及对应的C#实体类<br>


## ReadDataByJson文件夹<br>

* 这是一个Unity2017.3.1的实例项目，展示了如何在Unity中解析Json文件并获取需要的数据<br>
* 通过Python小工具生成的C#实体类需要放置到你的项目中，具体位置可自行选择<br>
* 这个实例项目中放在了DataTable文件夹下，其中InitGameDataFromJson脚本是主要解析类<br>
* 该项目使用的Newtonsoft.Json进行Json的解析<br>
* 将生成的Json文件需要放置在Unity的StreamingAssets文件夹下便于读取<br>
* 根目录下Main脚本就是对解析函数的调用并打印出获取的指定信息<br>
