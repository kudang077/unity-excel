# unity-excel
excel创建脚本和数据
Excel工具
数据类型int,float,bool,double,string,List,字典



第一行为名称
第二行为数据类型
第三行为key，key所在的列，为该表字典的索引
第四行是描述

程序    ExcelExample场景里有示例，程序运行时需先调用BinaryDateMG.Instance.InitData();
        获取表数据调用BinaryDateMG.Instance.GetTable<T>();
