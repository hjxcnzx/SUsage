## 由于试运行阶段没有达到KPI,同时开发团队工作紧张，该项目已暂停维护并即将重置。
#### 离开不一定代表结束，也许会是新的开始。

<b>Zhixin StudentUnion OA System #Codename"SUsage" </b>

<b>执信中学学生会信息化在线办公系统 开源项目 #代号"SUsage" </b>

<b>目前总体开发进度：100%，第二版本正在规划中。当前Build:2C03 (0803)</b>

<b>项目总阶段：1.0-Release1 #Project SUsage 1.0（开发代号Young）</b>

<p>TaskSYS V1.5 pre Release Candidate RC1</p>
<p>UCenter V1.5 beta B2</p>
<p>BillSYS V1.0 RC1</p>
<p>MCenter V1.5 RC</p>
<p>FileTour V0.4-milestone6 【未来project】</p>
<p><b>Latest update：2016.9.25 12:50</b></p>
<b>©2016 执信学生会 电脑部</b>
<br>
<b>Created By @yyl99311 | @df7c5117 | @GhostShadowTan | @橡胶人AS | @SmallOyster</b>
<br>
<b>特别鸣谢：@SmallOyster</b>
<br>
<b>Everyone can modified it except for the already existing codes </b>
<br>
<br>
<h4>本Repo迁移自原zhxsuwebgroup/SUsage<br>在登陆后界面按某个组合键有彩蛋哦~<s>才不会告诉你是alt+shift+g呢</s></h4>
<br>
<h3>这是个啥w</h3>
  <p>嗯，执信学生会的网上办公平台。</p>
  <p>一个神秘的系统，完全由37th SUPC自主研制开发。</p><a href="https://github.com/zhxsu/SUsage/wiki/Susage-%7C-%E6%A6%82%E8%BF%B0" target="_blank">详情请戳这里</a>

<h3>为啥叫这个名字w</h3>
  <p>StudentUnion简写“SU”和Message的组合自造词。<s>让人酥酥的公告系统</s></p>
  <p><s>雅号香肠</s></p>
<h3>好处都有啥w</h3>
  <s>有了SUsage，不流失不蒸发</s>
  <p>可以发布公告、下载文件、布置任务，省时又省力！</p>
  <p>界面美观又漂亮,【咦有语病</p>
<h3>配置</h3>
  <h4><p>本地可以使用<b>XAMPP1.8.2+</b>调试，服务器端建议最低配置PHP5+, Apache 2.4.17+, phpMyAdmin 4.5.1+</p></h4>
  <p>You can use <b>XAMPP1.8.2+</b> for local debugging.The recommend requirement for Server-side is PHP5+, Apache 2.4.17+, phpMyAdmin 4.5.1+</p>
  <h4><p>请将此文件包放在网站根目录</b></p></h4>
  <h4><p>环境配置完成后，请在PhpMyAdmin中新建susage数据库后导入susage.sql文件。</p></h4>
  <h4><p>并在<b>functions/to_sql.php、Admin/Includes/to_pdo.php</b>中按照提示填写您的数据库登录账户和密码</p></h4>
  <h4><p>测试账户1：Enatsu 密码：123456（角色：管理员+组长）</p></h4>
  <h4><p>测试账户2：Super 密码：123456（角色：超级管理员+根用户）</p></h4>
  <h4><p><b>若忘记密码可打开/SUsage/sha1.php按照提示输入密码</b></p></h4>
  <h4><p><b>点击确认后将inDB复制，粘帖进数据库中“pw”即可。</b></p></h4>
<h3>近期的事情</h3>
<p><b>----2016.8.29（Beta 2）----</b></p>
  <p>众多重大Bug修复</p>
  <p>修改用户密码算法（SHA1）</p>
  <p>SUsage管理中心（MCenter）新增WFD修复模块</p>
  <p>后端新增多个函数包</p>
  <p>优化代码可读性，解决代码累赘问题</p>
  <p>CSS优化</p>
  <p>注入代码注释</p>
  <p>数据库重构，修改用户权限储存方式</p>
  <p>全站启用响应式，支持移动端</p>
<p><b>----2016.8.1----</b></p>
  <p>Bug修复</p>
  <p>新增“账务系统”</p>
  <p>SUsage管理中心（MCenter）支持移动端</p>
  <p>新增“完成任务”功能</p>
  <p>优化代码</p>
  <p>CSS优化</p>
<p><b>----2016.7.29----</b></p>
  <p>Bug修复</p>
  <p>functions路径修改</p>
  <p>新增“删除任务”功能</p>
  <p>完成UCenter个人中心的“修改密码”“修改用户名”功能</p>
  <p>使用TXT代替数据库来储存全局通知</p>
  <p>各种CSS优化</p>
<p><b>----2016.7.25----</b></p>
  <p>完成“发布任务”功能</p>
  <p>新增“完成任务”功能（未建设完毕）</p>
  <p>登录时使用cookie记住用户名</p>
  <p>大改数据库结构</p>
  <p>全局公告开始部署</p>
<p><b>----2016.7.18----</b></p>
  <p>bug修复</p>
  <p>使用JS获取系统代码版本</p>
<p><b>----2016.7.13----</b></p>
  <p>移除VegeChat</p>
  <p>bug修复以及各种CSS优化</p>
<p><b>----2016.7.8----</b></p>
  <p>全新界面定名为S interface</p>
  <p>新增实验性版块：SUsage FileTour</p>
  <s>bug一个都没补</s>
<p><b>----2016.7.1----</b></p>
  <p>界面改版，全新视觉体验</p>
  <p>新增实验性功能：Auto NightShift</p>
  <p>UCenter功能升级</p>
  <p>数十项bug解决<s>及新bug产生</s></p>

<h3>注意事项</h3>
  <p>按照<s>基本法</s>wiki里的提示写就好啦</p>
  <a href="https://github.com/zhxsu/susage/wiki" target="_blank">修改时，欢迎参看我们的wiki</a>
<hr></hr>
<h3>开源声明及感谢</h3>
  <p>本项目目前基于以下几个开源项目开发：</p>
* <a href="https://jquery.org/" target="_blank">John Resig</a>的`jQuery`，遵循`MIT`协议
* <a href="http://www.bootcss.com" target="_blank">`Bootstrap 3.0`，遵循`MIT`协议</a>
* <a href="https://github.com/nt1m/material-framework/" target="_blank">nt1m</a>的`material-framework`，遵循`Apache`协议版本`2.0`
* <a href="http://wangeditor.github.io/">wangfupeng1988</a>的`WangEditor`，遵循`MIT`协议，新版本采用了SU精简化版本，体积更小，效率更高
* <a href="https://github.com/fengyuanchen/cropper">fengyuanchen</a>的`cropper.js`，遵循`MIT`协议
* <a href="https://github.com/daneden/animate.css">daneden</a>的`animate.css`，遵循`MIT`协议
* Github提供的免费代码仓库


**`GNU General Public Licence `版本`3.0`**
