# Yi-Ban_clock-in
<h1>易班校本化-健康自动打卡</h1>
<h2>简单配置</h2>
如果运行daka.py提示缺少requests，requests安装：pip install requests<br>
daka.py里面的中文都要url编码，不然可能出现乱码，url编码解码：http://tool.chinaz.com/tools/urlencode.aspx<br>
以及start中的daka.py的文件绝对路径要改成自己的daka.py文件绝对路径<br>
点击start.bat就ok了直接添加到windows的计划任务中每天早上，中午，晚上打开<br>
必须要保证windows不能关机否则计划任务无法执行，有服务器最好挂在服务器上一劳永逸<br>
最后要删除计划任务的运行delete.bat
![image](https://user-images.githubusercontent.com/54020830/197371223-57180a9c-1cdb-4bd8-8ddb-a2ad6bc4b518.png)
