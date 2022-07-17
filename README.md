# c_7809
2022一套最新纯代付系统源码安全可抗高并发后台功能丰富自动回调代付系统源码
<br/></br>
[下载地址](https://www.uuid2.com/7809.html "下载地址")
<br/></br>
<h3>源码简介：</h3>
<p>1、环境：<p>
<p>Nginx 1.20.2<p>
<p>MySQL 5.6.50<p>
<p>PHP-5.6<p>
<p>phpMyAdmin 4.4<p>
<p>2、安装php拓展：<p>
<p>ZendGuardLoader<p>
<p>Redis<p>
<p>redis未设置密码，默认端口6379<p>
<p>安装好后记得要重启一下php，让拓展生效。<p>
<p>添加域名后，运行目录指向Public   设置伪静态为thinkPHP默认伪静态或复制下方伪静态内容填写，下方为Nginx伪静态规则。<p>
<p>location / {<p>
<p>if (!-e $request_filename){<p>
<p>rewrite  ^(.*)$  /index.php?s=$1  last;   break;<p>
<p>}<p>
<p>}<p>
<p>导入数据库：chudaifu.sql<p>
<p>配置数据库：<p>
<p>/config/databese.php中配置数据库账号密码等内容<p>
<p>银行卡归属地等信息查询API<p>
<p>Api在api.kazhiguo.com注册账号，购买银行卡归属地验证的api，100元可查询2万次<p>
<p>如果不想使用API，可以让商户传值<p>
<p>bank_name=中国某某银行<p>
<p> 即可不使用Api查询，省去一些api费用。<p>
<p>/修改：<p>
<p>extend/xuncheng/C43.php  文件中修改api密钥<p>
<p>后台地址：http://域名/admin/login/index   admin   123456<p>
<p>代理地址：http://域名/agent/login/index<p>
<p>商户地址：http://域名/mch/login/index<p>
<p>Api下单地址：http://域名/api/pay/createOrder<p>
<p>Api查单地址：http://域名/api/Query/queryOrder<p>
<p>余额查询地址：http://域名/api/Query/queryBalance<p>
<p>后台可以编辑代理是否有权限来处理他下面商户的订单。<p>
<p>后台和代理手动操作出款完成为勾选订单，点击订单列表左上角的同步完成，该订单既等于完成，系统会自动发回调给商户。(不是在订单后面的转账按钮那里操作的哦)<p>
<p>该代码仅供研究测试学习使用，禁止用于非法用途，否则后果自负，开源代码，作者及二次开发人员不负任何责任。<p>
<h3>截图：</h3>
<img src="https://www.uuid2.com/wp-content/uploads/img/pro/20220430/16512872051680.png" alt="2022一套最新纯代付系统源码安全可抗高并发后台功能丰富自动回调代付系统源码"><img src="https://www.uuid2.com/wp-content/uploads/img/pro/20220430/16512872064089.png" alt="2022一套最新纯代付系统源码安全可抗高并发后台功能丰富自动回调代付系统源码"><img src="https://www.uuid2.com/wp-content/uploads/img/pro/20220430/16512872089229.png" alt="2022一套最新纯代付系统源码安全可抗高并发后台功能丰富自动回调代付系统源码"><img src="https://www.uuid2.com/wp-content/uploads/img/pro/20220430/16512872095708.png" alt="2022一套最新纯代付系统源码安全可抗高并发后台功能丰富自动回调代付系统源码"><img src="https://www.uuid2.com/wp-content/uploads/img/pro/20220430/16512872102385.png" alt="2022一套最新纯代付系统源码安全可抗高并发后台功能丰富自动回调代付系统源码"><img src="https://www.uuid2.com/wp-content/uploads/img/pro/20220430/1651287211992.png" alt="2022一套最新纯代付系统源码安全可抗高并发后台功能丰富自动回调代付系统源码"><img src="https://www.uuid2.com/wp-content/uploads/img/pro/20220430/16512872133612.png" alt="2022一套最新纯代付系统源码安全可抗高并发后台功能丰富自动回调代付系统源码"><img src="https://www.uuid2.com/wp-content/uploads/img/pro/20220430/16512872145096.png" alt="2022一套最新纯代付系统源码安全可抗高并发后台功能丰富自动回调代付系统源码"><img src="https://www.uuid2.com/wp-content/uploads/img/pro/20220430/16512872152577.png" alt="2022一套最新纯代付系统源码安全可抗高并发后台功能丰富自动回调代付系统源码">
