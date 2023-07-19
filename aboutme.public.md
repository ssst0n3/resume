<style>
a, a:link, a:hover, a:visited, a:active {
    color: black;
    text-decoration:underline;
}
h3 {
    /* color: red; */
    color: brown;
}
body {
    /* width: 100% !important; */
    max-width: none;
    margin: 0px !important;
    display: flex !important;
}
h1 {
    margin-block-start: 0.2em;
    margin-block-end: 0.8em;
    /* border-bottom: none !important; */
}
h3, h4, h5 {
    margin-block-start: 0.8em;
    margin-block-end: 0.8em;
}
ul {
    margin-block-start: 0;
    margin-block-end: 0;
    /* margin-bottom: 0px !important; */
}
.markdown-body, .markdown-theme {
    top: 0;
    /* padding-top: 0 !important; */
    max-width: 1200px;
    margin: auto;
}
.inline-vertical-url{
    display: inline-block; 
    vertical-align:top;
}
#name, #job {
    text-align: center;
}
#job {
    color: brown;
    /* color: orangered !important; */
}
h4 {
    color: brown !important;
    font-weight: normal !important;
}
@media print {
   /* Print CSS here */
   .markdown-body, .markdown-theme {
        font-size: 12px !important; 
        border: none !important;
        /* padding: 5px; */
        padding: 32px;
        padding-top: 0px !important;
    }
    #name {
        border-bottom: none !important;
    }
    #name, #job, #contact {
        padding: 0px !important;
        margin-top: 12px !important;
        margin-bottom: 0px !important;
    }
    h3, h4, h5 {
        padding: 0px !important;
        margin-bottom: 0px !important;
    }
    h3 {
        font-size: 1.5em !important;
        margin-top: 12px !important;
    }
    h4 {
        font-size: 1.2em !important;
        margin-top: 10px !important;
    }
    h5 {
        margin-top: 8px !important;
    }
    ul {
        padding-top: 0px !important;
        padding-bottom: 0px !important;
        margin-top: 8px !important;
        margin-bottom: 0px !important;
    }
    li>ul {
        margin-top: 0px !important;
    }
}
</style>
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.11.2/css/all.css">
<h1 id="name" >王磊</h1>
<h5 id="job" >安全工程师</h5>
<div id="contact" style="text-align: center">
    <i class="fas fa-phone"></i> ****
    <i class="fas fa-envelope"></i> ssst0n3@gmail.com
    <i class="fas fa-home"></i> <a target="_blank" href="https://ssst0n3.github.io">ssst0n3.github.io</a>
    <i class="fab fa-github"></i> <a target="_blank" href="https://github.com/ssst0n3"> ssst0n3 </a>
    <i class="fab fa-gitlab"></i> <a target="_blank" href="https://gitlab.com/st0n3"> st0n3 </a>
</div>

### 基本信息

* **个人信息：** 王磊/男/1995年
* **教育经历：** 本科/中山大学 `****`学院 `****`专业/2017届
* **英语水平：** CET-6
* **日语水平：** JLPT-N4

### 工作经历
#### **云 安全研究(2020.4-至今)
##### 容器安全研究
* 挖掘原创性容器安全漏洞, 并在现网渗透。

#### ** 安全解决方案部 安全测试(2017.9-2020.4)
##### 产品版本安全验收
* 主导或参与多个产品的安全测试，累计发现**150**余个安全漏洞。工作内容主要包括白盒代码审计、黑盒fuzz测试、安全基线设计与执行、安全工具落地, 验收产品涉及Go/Java/C语言。

##### 安全培训
* 主导产品线自研训战平台的设计和核心功能开发，引入容器技术实现20台4U6G虚拟机支撑**1000**人同时申请实验环境。
* 独立设计和开发Go/Java/C/sudo等类型共计**24**门实战课程，培训方案累计访问**57000**余次。

##### go语言安全研究
* 主导go语言安全测试方案研究，发现10个维度的go语言独有安全问题，在产品线落地，累计发现30余个问题。
* 在产品线推广落地go-fuzz工具，累计发现10余个问题。

##### 容器(docker)安全研究
* 主导docker安全测试方案研究，输出11个维度共计102条测试用例的测试方案。覆盖业界标杆的CIS docker基线全部内容，且新增约**30**%内容。
* 在产品线落地，累计发现**70**余个严重/致命问题。

### 个人项目
* <a href="https://gitlab.com/st0n3/st0n3_pdb">st0n3_pdb:</a>官方pdb仅支持python代码级别的调试，我基于pdb开发了一个字节码级别的python debugger，类似c语言的汇编级别调试，未发现有类似工具能实现同样的功能。技术栈: python/c。
* <a href="https://gitlab.com/sysucsa/waterdrop/waterdropctf">waterdropctf:</a>基于容器技术实现的ctf队内训练平台，支持在线awd功能。技术栈: docker/go/vue。
* <a href="https://gitlab.com/st0n3/hackerbot">hackerbot</a>: 个人开源威胁情报平台，基于rss/爬虫收集安全技术信息。技术栈: docker/go/vue。
* ctf项目:
    * <a href="https://gitlab.com/sysucsa/waterdrop/php_defense">php_defense</a>: 支持php的ctf流量记录及waf工具，支持黑白名单流量基于hash过滤，流量转发等功能。
    * <a href="https://gitlab.com/sysucsa/waterdrop/auto_submit">auto_submit</a>: 自动提交工具。
    * <a href="https://gitlab.com/sysucsa/waterdrop/flask_defense">flask_defense</a>: 支持python flask框架的ctf流量记录及waf工具。

### 技能清单
<div class="inline-vertical-url" style="width: 60%;">

* 安全技能
    * 精通容器安全, 熟悉Go语言安全/Web安全/linux主机安全，了解二进制安全
    * 安全工具: 熟悉sqlmap/IDA/Ghidra/awvs等主流安全工具使用
    * 代码审计: 精通python,熟悉Go/Java,了解C语言
* CTF: web/crypto
* 开发:  go/python/java/vue

</div>
<div class="inline-vertical-url" style="width: 39%; margin-top: 8px;'">
完整的个人技能树参见: <a href="https://ssst0n3.github.io/skill_tree/#/">https://ssst0n3.github.io/skill_tree/#/</a>
<br>
<img style="width: 15%; vertical-align: text-bottom" src="skilltree_qr.png" alt="扫描查看">
</div>

### 荣誉
<div class="inline-vertical-url" style="width: 15%;">
    <ul>
        <li>CVE-2021-21979</li>
        <li>CVE-2021-31856</li>
    </ul>
</div>
<div class="inline-vertical-url" style="width: 42%;">
    <ul>
        <li>中山大学网络安全协会创始人，waterdrop战队队长</li>
        <li>2019年西湖论剑杯二等奖、可信众测优胜奖</li>
        <li>2019年护网杯三等奖</li>
        <li>2020年,2018年**公司安全大赛第二名</li>
        <li>2019年**公司内部月、季度赛多次带队参赛获第二名</li>
    </ul>
</div>
<div class="inline-vertical-url" style="width: 42%;">
    <ul>
        <li>中国互联网发展基金会2016年网络安全奖学金</li>
        <li>中山大学校二等奖学金</li>
        <li>第九届全国大学生信息安全大赛技能赛第24名(广东省第一)</li>
        <li>2016“安恒杯”全国高校网络信息安全管理运维挑战赛华南赛区二等奖</li>
        <li>第二届“问鼎杯”全国大学生信息安全与保密技能大赛二等奖</li>
    </ul>
</div>
