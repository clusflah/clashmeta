# clashmeta
自用clash配置
配置文件使用proxy provider,未使用rule provider和rule set，因为现有支持rule set的配置较少，不如自寻rule加入配置文件。
使用时，只需将proxy provider的url部分，更改为自己的订阅链接，然后保存为yaml文件，导入clash使用。
策略组部分，分地区筛选策略组使用了正则筛选，仅meta内核支持，其余内核使用会显示所有节点。
