主要为vrchat跳舞房(pypydance,wannadance,vrdancing)准备的clash规则  
能直连的直连,节约流量

更新记录  
25.07.27  
原music.yaml拆分为直连和代理两个  
因pypydance使用cloudflare服务,pypy在国内部分地区必须走代理.   
wannadance和vrdancing在我这里可以直连  

部分浏览器(edge/chrome)默认强制https,可能导致pypydance歌曲链接在浏览器出现cloudflare 525错误  
需要关闭强制https功能才能正确观察歌曲连接性  
edge:  
设置 - cookie和网站权限 - 不安全的内容  
"允许"中添加pypy的歌曲链接和cdn链接,例如"jd.pypy.moe"和"cdn.pypy.dance"  
chrome:  
菜单“设置”-“隐私和安全”-右侧“安全”点进去  
将“一律使用安全连接”选项关闭即可  

26.01.10  
补充一些vrchat内容相关的域名,适合blacklist模式下附加规则  

26.02.04  
更新pypy和wannadance的规则  

26.03.22
合并三大舞蹈房的歌曲链接，并且建议在插件的覆写设置中使用  
