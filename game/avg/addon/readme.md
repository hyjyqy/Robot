# AVG插件Addon说明  
  
**需要的DLL函数**  
  
`_Start`  
**启动时调用，无参数，无返回**  
  
`_End`  
**关闭时调用，无参数，无返回**   
  
`_Text`  
**处理时调用，返回处理后的内容**  
  
参数一，文本型，待处理游戏文本  
参数二，文本型，QQ号  
参数三，文本型，群号（没有为空文本）  
参数四，文本型，当前进行游戏  
参数五，文本型，QQ发送的消息  
参数六，文本型，触发参数  
  
----
**附加DLL请放在本插件数据目录\Addon\下**