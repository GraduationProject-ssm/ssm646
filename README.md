# [首页查询更多项目](https://github.com/GraduationProject-ssm) 包安装运行


# ssm646基于web的物流配送管理系统的设计与实现+vue

![picture](https://raw.githubusercontent.com/GraduationProject-springboot/.github/main/img/wx.png)

### 点击播放视频 ▼
[![Watch the video](https://i.sstatic.net/Vp2cE.png)](https://www.bilibili.com/video/BV1Tm8QeZE4a?p=45)


# 第一章 绪论
## 1.1研究背景与意义
在科学技术水平还比较低下的时期，企业通常采用人工登记的方式对相关的物流配送信息进行记录，而后对这些信息记录进行管理和控制。这种采用纸质存储信息的管理模式，对于企业管理人员来说，即不方便后期的数据记录查找，以及进行必要的个人信息资料更新与管理操作，也容易在登记过程中出现失误，严重的影响了信息的真实性和可靠性[1]。所以，传统的使用纸质的方式对相关数据信息进行管理，已经满足不了人们的现实使用需求了，也顺应不了时代的进步和发展。

现今，科学技术正在飞速的发展，其所迸发的力量是无穷的，并且发挥出了巨大的作用，由此促进了信息化的时代诞生[2]。信息化的管理模式正是信息化时代的产物，通过使用信息化的管理模式，可以解除时空的限制，在任何时间和任何地点，均可对数据资源进行管理，由此可见，信息化的管理模式具有极大的现实意义和使用价值。为了提高企业管理人员的管理质量和水平，避免错误的记录物流配送信息，确保数据的真实性和可维护性，本人设计了一款基于web的物流配送管理系统。
## 1.2国内外研究现状
在国外，尤其是美国为首的发达国家，对信息化管理模式的研究比较早，这些国家对学校、企业、医院、军事等领域的信息化管理建设非常重视。随后许多国家紧随其后，不断地发展和完善信息化管理模式。上个世纪末，德国等国家，重点研究了将信息化建设应用到企业的日常办公工作，英国等国家也加强了对信息化的基础设施的投资[3]。近几十年，随着互联网的发展与普及，使得信息化的管理模式将取代纸质化的管理模式成为了必然趋势。当下，信息化管理模式的相关技术已经非常成熟了[4]。

与国外相比，我国虽然对信息化管理模式的起步比较晚，但是在极短时间内，信息化管理模式发展迅猛，与之相关的技术和工具也由展露头角，到稳步发展，再到趋于成熟，目前也正在逐渐与发达国家缩小差距[5]。近些年，我国的相关技术人员也研究和设计出了支付宝、微信等应用软件，随后，在较短的时间内，被人们所接受和认可，再到当下，人们的日常生活也离不了这些应用软件的使用，并且正在被不断地推广到全球各地，也逐渐被各个地方各个国家的人们所支持和认可，从这一方面可以看出来，我国的信息化技术的发展，以及专业能力和水平的提高是值得被世界所肯定的[6]。
## 1.3论文组织结构
本文介绍了设计和实现基于web的物流配送管理系统的全过程，从研究系统的背景、意义、现状，到通过系统分析过程，确定系统的主要功能需求，再通过系统设计过程，设计相关的功能模块和数据表，最后通过功能测试，发现系统设计的问题，并完善系统的设计。本文具体的组织结构安排如下：

第一章绪论，本章主要介绍了研究系统的相关背景、意义、现状等内容。通过本章所介绍的相关内容，可以对系统的发展有一定的了解和认识，并且也说明了系统开发是具有一定的现实依据和使用价值。再根据研究内容的介绍，可以了解本文对系统的哪些内容进行了具体的研究。

第二章相关技术介绍，本章主要介绍了开发系统所用到的关键性技术工具，比如Java语言、JSP技术、MySQL数据库等。通过使用Java语言对系统功能进行编码实现，使用JSP技术创建系统主要使用界面，使用MySQL数据库管控系统后台数据信息。本章通过介绍的相关开发技术工具，为系统的设计和实现提供技术支持。

第三章系统分析，本章主要介绍了系统相关的分析内容。通过需求分析过程，分析系统实际需要的使用功能需求，规划系统即将设计的整体功能设计。再通过可行性分析过程，具体分析设计的系统在经济、技术等方面，是否具备实现的可行性，分析系统能够被成功设计和实现的可能性。

第四章系统设计，本章主要介绍了系统相关的设计内容。通过总体功能设计阶段，结合需求分析，对系统进行整体的功能设计规划，基本确定系统的功能模块设计，增加系统实现的可能性。通过数据库设计阶段，使用MySQL数据库管理相关的系统数据，再通过对系统进行实体-联系图设计以及相关数据表格设计，存放与系统相关的数据信息，便于后期数据库相关人员对系统进行管控。

第五章系统实现，本章主要介绍了系统功能实现的相关内容。通过对系统主要的功能模块用户界面，及其相关的具体操作和处理步骤进行展示和说明，用户了解和认识系统主要的功能设计，便于用户访问和使用本系统，以满足自己一定的使用需求的目的。

第六章系统测试，本章主要介绍了系统测试的相关内容。通过对系统测试进行简单的概括说明，了解系统测试的基本内容和常用方法。通过对系统进行功能测试，检测系统功能设计是否有漏洞，测试系统的功能模块能否正常运行，以及在运行过程中是否发现错误，而后不断地完善系统设计。

第七章总结与展望，本章主要是对系统实现的整个过程进行总结，以及展望系统发展的未来状况。总结系统整个的开发设计过程，对系统实现所具有的优势进行说明，并且分析系统可能存在的不足，针对于这些不足，对系统进行改进和完善。展望未来学习和掌握更加先进的技术，将其运用到本系统的设计中，开发出一款功能更强大、应用范围更广的系统。














# 第二章 相关技术介绍
## 2.1 B/S架构
浏览器/服务器结构，可以被简写为B/S结构（Browser/Server结构），是目前最受欢迎的软件开发结构之一[7]。B/S结构主要通过将系统网址发布到浏览器的方式，由用户在浏览器上进行网站访问，即可实现对系统的相关操作，进而满足实际的功能需求。服务器/客户机结构，可以被简写为C/S结构（Client/Server结构），其主要通过运行客户端程序面向系统的使用对象，进而实现系统的功能操作[8]。通过C/S结构开发的客户端应用程序具有较快的处理速度和响应时间，其在运行安全方面和性能稳定方面具有较大的优势。但是，由于用户需要下载客户端程序，并且通过进行正确的安装步骤，才可运行和使用系统，安装步骤繁琐，工作量大，灵活性不好，并且与系统相关的软、硬件均需要定期的升级和维护，所需的成本极高。相比之下，开发人员一般首先考虑使用C/S结构实现系统。
## 2.2 Java语言
Java语言是面向对象的编程语言，而比较常用的C语言，则是面向过程的编程语言。那么，面向对象与面向过程这两种开发方式具体哪些什么区别[9]。面向过程是将一个问题整体，分解成一个个具体的步骤，通过分阶段的使用函数对这些具体步骤的处理，最终实现对问题的解决。面向对象最主要的目的不是分阶段地实现每个步骤，而是以对象的方式对需要解决的问题进行分解，再通过描述对象的行为，实现问题的解决。面向对象的编程语言是科技进步的产物，它的出现顺应了社会的发展。面向对象的系统设计，可以继承和封装相关对象及其属性，提高功能代码的使用率，由此减少开发人员的设计压力。因此，研发人员大多使用面向对象的编程语言来解决实际的问题。

Java语言具有跨平台性、可移植性等特点，如此说明使用Java语言编程设计的系统，可以支持在不同的浏览器平台上运行，并且代码也可以被转移到其他开发环境中执行，便于在更多的其他任务中使用系统，以此可以延长软件的使用周期。Java语言具有较强的健壮性和稳定性，当系统因为输入错误或外界操作不正常而发生故障时，不会导致死机、崩溃现象的出现，而会给用户一定的错误提示信息，帮助用户找到出错的原因，然后在较短的时间内解决问题。语法简单，容易被理解和掌握[10]。除了上述特点外，Java语言还具有使用简单、容易学习、操作便捷等优点，因此许多开发人员会优先考虑使用Java语言对系统进行功能设计。
## 2.3 MySQL数据库
MySQL数据库是一种轻量级的关系型数据库，因为它占用的内存资源非常少，而且能够在较短的时间内，快速地响应用户需求，所以非常适应于中小型的系统的开发[11]。MySQL数据库代码具有开源性，设计人员可以在经过源代码设计人员的同意下，个性化地选择使用和修改相关代码，以适应所设计系统的开发和运行。MySQL数据库具有免费性，设计人员不需要额外支付数据库软件使用费用，就可以直接使用MySQL数据库，设计系统相关的数据表格，存储和管理一定的数据记录，由此极大地节约了系统的开发成本[12]。除此之外，MySQL数据库还具有定时刷新功能以及较强的灵活性，在一定的时间范围内，对数据进行刷新操作，便于及时更新和存储数据，并且可以将不同的信息记录存放在不同的数据表格中，较为灵活支持关联不同的数据表格。
## 2.4 JSP技术
Java服务器页面，简写为JSP技术（Java Server Pages技术），其是一种使用较为频繁的动态页面设计技术[13]。由于JSP技术主要是基于Java进行编写的创建动态页面技术，故而其能够支持在不同的Java应用服务器上运行，并且可以在不同的网页上实现数据传递、信息记录、信息共享等功能。JSP技术继承了Java servlet的所有功能，所生成的web网页内容是与平台和协议无关，可以响应多种类型的请求，也能够交互式地生成数据和浏览页面[14]。除此之外，JSP技术具有预编译的特点，也就是首次运行时需要对JSP代码进行编译处理，而后再运行时，就无需再次进行编译，直接使用之前已经编译好的程序即可。JSP技术以在相关的HTML代码嵌入JSP标签的方式，在相应的用户页面中生成相关的JSP文件，对应用程序的相关显示界面进行创建。







# 第三章 系统分析
## 3.1系统的需求分析
需求分析是以用户的使用需求为基础，将用户的真实期望转化为实际的功能设计过程。本人主要通过问卷调查、现场调研的方式，分析系统主要的功能使用需求。本系统的使用对象主要分为管理员角色和用户角色，管理员主要的角色职能是管理物流配送相关的信息记录，用户主要的角色功能是查看和保存个人信息记录。需求分析主要包括功能需求、业务需求、性能需求、安全需求等内容。

其中，功能需求是指为了能够满足不同使用者的具体使用需求，调研人员据此分析系统实际的功能需求，开发人员再根据分析结果，对系统的实际功能模块进行详细的设计和实现，其中，系统主要的功能需求包括用户管理、车辆信息管理、货物订单管理等模块。

业务需求是指为了更快更好地实现对车辆信息的交互和管理过程，相关人员将整个物流配送管理系统的分解为多个便于实现的子功能模块，每个子功能模块的设计就能够实现相应的系统业务流程，系统主要的业务需求包括用户注册、登录、查询、更新等流程。

性能需求是指为了保证系统的实现能够满足设计期望，以及避免因为不合格的系统性能而造成的软件或网络问题，而对系统进行组件检查、网络服务、信息存储、处理器运作、响应时间等必要的性能需求分析。如果系统在运行过程中，组件检查正常、网络服务正常、信息存储安全、处理器运作正常、响应时间快，那么可以说本次所设计的系统是具备良好的使用性能的。

安全需求是指为了查验所设计的系统是否具有安全性和可靠性，而对系统进行健壮性、可用性、防病毒、数据保密等必要的安全需求分析。由系统授权的合法的用户正常的访问本系统，并且可以选择查看、修改相关信息记录，但是未经授权的非法用户是不能随意修改信息记录。
## 3.2系统的可行性分析
### 3.2.1经济可行性
对于开发者来说，研发一款系统最主要的目的是能够获取一定的利润。对于使用者来说，设计一款系统最关键的作用是能够满足一定的使用需求。本物流配送管理系统通过使用Java语言，对系统功能进行编码实现。根据使用Java语言的相关特点可知，开发出来的系统能够支持运行在各种类型的浏览器中。本系统使用了开源的、免费的MySQL数据库，存储和管理与系统相关的数据记录。MySQL数据库占用内存少，语法简单，操作简便，所以在保证运行速度和响应速率的同时，也大大降低了系统开发的成本。本人尽最大可能地降低开发成本，设计出一款能够满足用户实际使用需求的系统，便于提高相关人员的管理质量和工作效率。根据上述分析可知，基于web的物流配送管理系统的开发是具备经济可行性的。
### 3.2.2技术可行性
本物流配送管理系统通过采用Java语言设计系统功能，SSM框架设计系统基本架构，JSP技术创建用户界面，MySQL数据库管控数据信息。根据Java所具有的特点可知，使用Java语言开发的系统是可以在各种浏览器上被访问和运行，并且代码具有较高的可移植性，便于技术人员将代码运用到更高级别的任务中，增加代码的可重复使用率。JSP技术以Java语言为基础，编写自己的脚本语言，因此其具有可扩充性、跨平台性的特点，可以支持多种网页格式，并且相关代码也有着较强的稳定性和健壮性。MySQL数据库是开源的小型关系型数据库，其具有较快的响应速度，较少的内存占用，较简单的操作流程，所以非常适用于中小型应用系统的开发。根据上述分析可知，开发一款基于Java技术的物流配送管理系统是具备技术可行性的。
### 3.2.3操作可行性
用户在使用本系统时，不需要通过下载、安装客户端程序等复杂的步骤，也不需要掌握一定的计算机专业知识和技能，直接通过在浏览器上访问系统网址，即可根据相关的提示信息，运行和使用本系统，进而满足自己的使用需求。本系统的实现以人性化设计为主要目的，界面设计具有较高的友好性，数据库连接也具有较强的交互性。对于用户来说，只需要懂得Windows应用程序最基本的操作流程步骤，比如当用户双击选择某个功能时，就可以成功地使用该功能模块了，由此实现对本系统所进行地具体功能操作。综合上述分析可知，基于web的物流配送管理系统具备操作可行性的。






# 第四章 系统设计
## 4.1系统的总体设计
本系统是以B/S开发结构为基础进行设计和实现的，并且通过关键的开发技术，比如Java语言、SSM框架、MySQL数据库等技术，对系统的功能模块、后台管理模块等进行实现，系统功能实现后，用户可以通过使用浏览器，运行和使用系统。通过需求分析的相关内容，可以确定用户对于本系统的具体使用需求，进而规划出系统基本需要具备的功能模块。基于web的物流配送管理系统的使用对象主要分为管理员角色和用户角色，主要的功能需求包括用户管理、车辆信息管理、货物订单管理等。系统总体功能设计图如图4-1所示。

基于web的物流配送管理系统

用户信息管理

货物订单管理

车辆信息管理

货物信息管理

基础数据管理

用户信息修改

用户信息新增

基础数据添加 

基础数据删除

基础数据修改

货物信息添加

货物信息修改

货物信息删除

货物订单添加

货物订单删改

货物订单删除

车辆信息添加 

车辆信息修改 

车辆信息删除 

公告信息管理

公告信息修改

公告信息删除

公告信息添加


![](/md/blog.001.png)

图4-1系统总体功能设计图

## 4.2数据库设计
### 4.2.1概念设计
MySQL数据库是免费的面向使用对象，其源代码对外也是公开发布的，也就是说设计人员在经过源代码设计人员的同意之后，就可以根据自身的一定需求，对相关代码进行使用和修改，由此极大的节约了软件开发成本[15]。而且，MySQL数据库占用极少的内存资源，系统与用户之间的交互性强，响应速度和运行速度也比较快，非常适用于中小型系统的开发和设计。从一定意义上说，MySQL数据库的使用价值是非常高的，其相关的语法语义也比较容易理解和掌握，因此本人使用MySQL数据库完成对相关的系统数据的存储和管控。数据库设计过程主要包括概念设计和逻辑设计两个阶段。其中，概念设计是逻辑设计的基础依据，逻辑设计是概念设计的具体实现。

概念设计阶段主要目的是将真实世界的工作任务转化为抽象世界的概念模型，通过设计实体-联系图（E-R图）的方式，来表示实际生活中的工作功能中的实体和属性[16]。这样一来，在物流配送管理系统中，就可以对每一个工作流程进行设计，进而实现对相关的用户信息传递和共享，并由此构建出与系统有关的实体及其属性。本阶段的设计内容是将现实世界中用户对系统的相关功能需求，描述成为便于数据库设计人员理解的概念模型。系统的各实体E-R图设计如图4-2、图4-3、图4-4、图4-5、图4-6、图4-7、图4-8、图4-9、图4-10、图4-11所示，总体E-R图设计如图4-12所示。

![](/md/blog.002.png)

图4-2管理员信息E-R图

![](/md/blog.003.png)

图4-3员工信息E-R图

![](/md/blog.004.png)

图4-4客户信息E-R图

![](/md/blog.005.png)

图4-5字典信息E-R图

![](/md/blog.006.png)

图4-6车辆信息E-R图

![](/md/blog.007.png)

图4-7货物信息E-R图

![](/md/blog.008.png)

图4-8货物订单信息E-R图

![](/md/blog.009.png)

图4-9出入库信息E-R图

![](/md/blog.010.png)

图4-10出入库详情信息E-R图

![](/md/blog.011.png)

图4-11公告信息E-R图

![](/md/blog.012.png)

图4-12系统的总体E-R图
### 4.2.2逻辑设计
逻辑设计阶段主要的目的是将概念设计中已经构建好的概念数据模型，转变成数据库能够识别和存储的二维数据表格的形式[17]。本阶段的设计内容是数据库设计人员将理解好的概念模型，描述成为MySQL数据库能够识别的数据表格。本阶段具体的实现方式是将上一阶段设计的E-R图转变成方便数据库进行存储和管理的数据表格，具体的数据表格设计如表4-1、表4-2、表4-3、表4-4、表4-5、4-6、表4-7、表4-8、表4-9、4-10所示。

表4-1 管理员信息表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|id|Int|编号|否|
|2|username|String|用户名|是|
|3|password|String|密码|是|
|4|role|String|角色|是|
|5|addtime|Date|新增时间|是|

表4-2 员工信息表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|id|Int|编号|否|
|2|<p>yonghu\_uuid\_</p><p>number</p>|String|工作证号|是|
|3|username|String|账户|是|
|4|password|String|密码|是|
|5|yonghu\_name|String|员工姓名|是|
|6|yonghu\_photo|String|头像|是|
|7|sex\_types|Integer|性别|是|
|8|bumen\_types|Integer|部门|是|
|9|yonghu\_phone|String|联系方式|是|
|10|yonghu\_id\_number|String|员工身份证号|是|
|11|yonghu\_email|String|邮箱|是|
|12|yonghu\_address|String|居住地址|是|
|13|yonghu\_time|date|出生年月|是|
|14|yonghu\_delete|Integer|假删|是|
|15|create\_time|Date|创建时间|是|

表4-3 客户信息表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|id|Int|编号|否|
|2|kehu\_uuid\_number|String|客户编号|是|
|3|kehu\_gongshi|String|公司名称|是|
|4|kehu\_address|String|公司地址|是|
|5|sex\_types|Integer|性别|是|
|6|kehu\_name|String|联系人|是|
|7|kehu\_phone|String|联系方式|是|
|8|kehu\_email|String|邮箱|是|
|9|kehu\_delete|Integer|假删|是|
|10|create\_time|Date|创建时间|是|

表4-4 字典信息表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|id|Int|编号|否|
|2|dic\_code|String|字段|是|
|3|dic\_name|String|字段名|是|
|4|code\_index|Integer|编码|是|
|5|index\_name|String|编码名字|是|
|6|super\_id|Integer|父字段编号|是|
|7|beizhu|String|备注|是|
|8|create\_time|Date|创建时间|是|

表4-5 车辆信息表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|id|Int|编号|否|
|2|cheliang\_uuid\_number|String|车辆编号|是|
|3|cheliang\_name|String|车辆名称|是|
|4|cheliang\_types|Integer|车辆类型|是|
|5|cheliang\_number|Integer|车辆数量|是|
|6|cheliang\_content|String|车辆详情|是|
|7|create\_time|Date|创建时间|是|

表4-6 货物信息表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|id|Int|编号|否|
|2|goods\_name|String|货物名称|是|
|3|goods\_types|Integer|货物类型|是|
|4|goods\_photo|String|货物图片|是|
|5|goods\_kucun\_number|Integer|货物数量|是|
|6|goods\_money|BigDecimal|货物价格|是|
|7|goods\_content|String|货物详情|是|
|8|create\_time|Date|创建时间|是|

表4-7货物订单信息表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|id|Int|编号|否|
|2|goods\_name|String|货物订单号|是|
|3|goods\_id|Integer|货物|是|
|4|kehu\_id|Integer|购买客户|是|
|5|cheliang\_id|Integer|车辆|是|
|6|goods\_order\_number|Integer|购买数量|是|
|7|goods\_order\_shouhuoren|String|收货人|是|
|8|goods\_order\_phone|String|联系方式|是|
|9|goods\_order\_address|String|送货地点|是|
|10|goods\_order\_types|Integer|订单状态|是|
|11|create\_time|Date|创建时间|是|

表4-8出入库信息表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|id|Int|编号|否|
|2|goods\_churu\_inout\_uuid\_number|String|出入库流水号|是|
|3|goods\_churu\_inout\_name|String|出入库名称|是|
|4|goods\_churu\_inout\_types|Integer|出入库类型|是|
|5|goods\_churu\_inout\_content|String|备注|是|
|6|insert\_time|Date|添加时间|是|
|7|create\_time|Date|创建时间|是|

表4-9出入库详情信息表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|id|Int|编号|否|
|2|<p>goods\_churu\_inout\_</p><p>id</p>|Integer|出入库|是|
|3|goods\_id|Integer|货物|是|
|4|goods\_churu\_inout\_list\_number|Integer|操作数量|是|
|5|insert\_time|Date|操作时间|是|
|6|create\_time|Date|创建时间|是|

表4-10公告信息表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|id|Int|编号|否|
|2|news\_name|String|公告标题|是|
|3|news\_types|Integer|公告类型|是|
|4|news\_photo|String|公告图片|是|
|5|insert\_time|Date|公告时间|是|
|6|news\_content|String|公告详情|是|
|7|create\_time|Date|创建时间|是|













# 第五章 系统实现
## 5.1个人中心
个人中心模块设计的主要目的是方便用户对个人信息进行管理，用户可以根据自己的实际需求，选择每隔一段时间，对个人账户的密码等相关信息进行更新操作，修改密码界面设计如图5-1所示，个人信息界面如图5-2所示。

![](/md/blog.013.png)

图5-1修改密码界面

![](/md/blog.014.png)

图5-2个人信息界面
## 5.2管理员管理
管理员管理模块设计的主要目的是方便管理用户对相关的管理员信息进行管理，管理用户可以选择查看管理员的用户名，修改管理员的密码，管理员管理界面设计如图5-3所示。

![](/md/blog.015.png)

图5-3管理员管理界面
## 5.3员工管理
员工管理模块设计的主要目的是方便管理用户对相关的员工信息进行管理，管理用户可以选择查看员工的邮箱，修改员工的手机号码，员工管理界面设计如图5-4所示。

![](/md/blog.016.png)

图5-4用户管理界面
## 5.4客户管理
客户管理模块设计的主要目的是方便管理用户对相关的客户信息进行管理，管理用户可以选择查看客户的邮箱，修改客户的手机号码，客户管理界面设计如图5-5所示。

![](/md/blog.017.png)

图5-5客户管理界面
## 5.5车辆信息管理
车辆信息管理模块设计的主要目的是方便用户对相关的车辆信息进行管理，用户可以选择查看车辆的详细信息，修改车辆的名称，车辆信息管理界面设计如图5-6所示。

![](/md/blog.018.png)

图5-6车辆信息管理界面
## 5.6基础数据管理
基础数据管理模块设计的主要目的是方便用户对相关的部门、货物类型、公告类型信息进行管理，用户可以选择查看部门、货物类型、公告类型的详细信息，修改部门、货物类型、公告类型的名称，部门管理界面设计如图5-7所示，货物类型管理界面设计如图5-8所示，公告类型管理界面设计如图5-9所示。

![](/md/blog.019.png)

图5-7部门管理界面

![](/md/blog.020.png)

图5-8货物类型管理界面

![](/md/blog.021.png)

图5-9公告类型管理界面
## 5.7货物信息管理
货物信息管理模块设计的主要目的是方便用户对相关的货物、货物订单信息进行管理，用户可以选择查看货物、货物订单的详细信息，修改货物的名称，修改货物订单的送货地点，货物信息管理界面设计如图5-10所示，货物订单管理界面设计如图5-11所示。

![](/md/blog.022.png)

图5-10货物信息管理界面

![](/md/blog.023.png)

图5-11货物订单管理界面
## 5.8出入库管理
出入库管理模块设计的主要目的是方便用户对相关的出入库信息进行管理，用户可以选择查看出入库的详细信息，修改出入库的名称，出入库管理界面设计如图5-12所示，出入库详情管理界面设计如图5-13所示。

![](/md/blog.024.png)

图5-12出入库管理界面

![](/md/blog.025.png)

图5-13出入库详情管理界面
## 5.9公告信息管理
公告信息模块设计的主要目的是方便用户对相关的公告信息进行管理，用户可以选择查看公告的详细信息，修改公告的名称，公告信息管理界面设计如图5-14所示。

![](/md/blog.026.png)

图5-14公告信息界面

















