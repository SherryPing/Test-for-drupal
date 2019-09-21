**《DRUPAL 8 EXPLAINED》——读书笔记**

注：这是根据本书做出的例子，包括下载的模块等，有部分模块出现不兼容情况，在笔记中标出，在site中不影响显示，以下是对每一章的大纲概括：



**

**CONTENTS** 

About Drupal 8 Explained 

About OSTraining 

About Pantheon 

About the Authors 

About the Legal Details 

\1. Drupal Explained 

\2. Drupal Planning Explained 

\3. Drupal Installations Explained 

\4. Drupal Administration Explained 

\5. Drupal Content Explained 

\6. Drupal Fields Explained 

\7. Drupal Modules Explained 

\8. Drupal Menus Explained 

\9. Drupal Blocks Explained 

\10. Drupal Themes Explained 

\11. Drupal Views Explained 

\12. Drupal Layout Modules Explained 

\13. Finishing the Design Explained 

\14. Drupal Users Explained 

\15. Drupal Site Management Explained

 

**前言-****ABOUT DRUPAL 8 EXPLAINED** 

1. **THIS BOOK IS ACTIVE** **（这本书很灵活）——所以，在这本书的每一章中，你都会被要求与Drupal合作。**


2. **这本书列举了一些具体的例子。——这本书使用了一个特定的示例站点。让这本书的所有读者建立一个相同的网站，使我们很容易给你具体的指示，解释，和截图。**

![img](file:///C:\Users\ASUS\AppData\Local\Temp\ksohtml4344\wps1.jpg) 

3. **这本书将删选掉一些东西。——这本书不全面。它并不包含你能知道的关于Drupal的所有信息。它只包含了Drupal初学者需要知道的内容。**

4. **这本书几乎没有使用任何代码。****——这本书没有讨论设计主题或构建模块。您不必是一个开发人员才能使用Drupal。**

5. **这本书里的东西会改变的****——Drupal经常发生变化，添加到它上的额外特性和设计也是如此。**


6. **你需要****为这本书提前准备****什么？****——一个可以联网的可安装drupla的电脑**

 

**Chapter1—****DRUPAL EXPLAINED****(关于drupal)** 

1. **drupal它是为人们在网上发布内容而设计的：新闻，博客，照片，产品，文档，事件，或者其他的东西。因为它使您能够管理您的内容，所以您经常会听到它被称为“内容管理系统”(ContentManagementSystem)或简称CMS。**

2. **版本：Drupal 8于2015年发布，大大改进了Drupal数据和代码的管理方式。**

3. **drupal优点：更容易，更快开发，更便宜，有更多选择（更丰富的模块选择）**

 

**Chapter2—****DRUPAL PLANNING EXPLAINED****(drupal网站规划)** 

1. **目的：了解网站计划中涉及的内容。了解项目管理计划涉及的内容。认识到发展计划所涉及的内容。了解维护计划中涉及的内容。 开始为我们将在这本书中建立的网站思考网站，项目管理，开发和维护计划。**

2. **要规划Drupal站点，您需要四种类型的计划：**

1）**Drupal网站计划：该计划的重点是定义网站的内容和功能需求，以及设计(可视化、**	**结构化、布局和交互)方面。网站计划通常包括需求文档和设计。根据您选择的项目管**	**理方法，与网站计划相关的详细程度可能有所不同。你是从一个大图片草图开始，稍**	**后，当你构建你的网站的每一个部分时，你会添加更精细的细节，使你的网站完全符**	**合你的需要。包括内容，交流区，导航，功能，角色和权限，执行情况（预期），安**	**全性，设计（Drupal有主题以适应移动设备，交互计划，描述线框样式指南中的对象**	**的行为。 确保颜色、字体、布局、图像、品牌等方面的一致性。）**

2）**Drupal项目管理计划****：你需要什么技能？网站规划和开发任务将如何完成？现场**	**何时启动？要花多少钱？您将如何监视进度？该如何将如果需求或设计功能无法满**	**足最初的要求，您可以管理期望吗？**

3）**Drupal发展计划：发展计划是建立网站的人之间讨论的一个来源。重要的是要记**	**住的是发展这个词。接下来要记住的是，开发不应没有网站计划，它传达给开发者你**	**想要或需要什么，它是什么样子，它需要支持什么过程，等等。1.内容：例如，开发**	**计划可以记录您的内容策略。2.实施：发展计划的另一个方面是每项战略何时实施。**

4）**Drupal维护计划**：日常监测维修，计划更新维修，现场管理

 

**经过上面4个计划，最终完成的网站如下：**

![img](file:///C:\Users\ASUS\AppData\Local\Temp\ksohtml4344\wps2.jpg) 

 

 

 

 

 

 

 

 

 

 

 

 

 

**网站内容类型准备：新闻文章，在线图书、音频和视频、静态内容、文档、Drupal公司事件信息、地图讨论论坛、有用的Drupal网站信息、有用的Drupal用户组信息**

 

**网站也将有以下几种类型的交流：屏幕上的内容传递消息。Drupal的默认电子邮件传递帐户设置操作。允许用户对内容进行评论。提供社交媒体链接可以帮助访问者与其他人共享站点的页面。联系表单，以便用户可以访问站点上的管理员。**

 

**站点可包括的内容：共享能力，论坛管理，投票，交流区，搜索，网站地图，自动的自定义的url,谷歌分析，搜索引擎优化特性**

 

**用户角色：只能看网站的匿名访客，可以登录、发布评论和加入讨论论坛的经过身份验证的用户。能写博客文章的博主，可以管理Drupal公司列表的公司编辑，能够管理论坛主题的主持人，有权在网站上做任何事情的管理员**

 

**为了帮助您可视化我们的Drupalville网站在这本书的结尾，下面是一些关键的登陆页面，您将构建。**

**资源：用户可以在此站点上使用的Drupal信息概述**



![img](file:///C:\Users\ASUS\AppData\Local\Temp\ksohtml4344\wps3.jpg) 

**公司：显示具有徽标的Drupal公司的网格**

**事件:显示在日历布局中**

 

**Chapter3—drupal安装**

1. **安装环境需要：本地服务器或者一个通用的 PHPWeb 服务器（Apache）或者由 Drupal 专家托管的 Web 服务器。**

**法1：通过PANTHEON安装**

**法2：自动安装（一键安装）**

**法3：手动安装（composer安装完drupal8-手动修改xmapp里htdocs项目的文件名为d8(举例)-**<http://127.0.0.1/phpmyadmin>**新建数据库-**<http://127.0.0.1/d8>新建用户访问（第一次需要按步骤安装一下）**）**

**安装步骤：详见文档。。。（--90页）**

 

**Chapter4—drupal管理**

1. **导航栏：了解菜单栏，快捷方式（添加和删除），用户信息，导航栏横竖显示**

2. **内容（content）：过滤筛选，添加内容（文章，基本页面），评论，文件**

3. **结构（structure）:一共八种。。。**

4. **外观（appearance）:主题**

5. **扩展（extend）:模块**

6. **配置（configuration）:添加模块就会变多**

7. **人员（people）:添加人员，设置权限，添加角色**

8. **报告（report）: 此区域包含有关网站健康状况的报告。**

9. **帮助（help）:您将看到有关站点所有不同区域的文档链接。**

10. **管理者和访客切换**

 

**Chapter5—drupal内容**

1. **目的：添加内容。找到内容。创建一篇文章。创建一个基本页面。启用更多内容类型。创建新的内容类型。编辑内容类型。描述内容类型的用途。**

2. **基本内容类型：文章，基本页面，论坛主题（创建，加链接），book类型（创建用户手册）**

3. **自定义内容类型（字段）：**

1）**事件（时间，地点）（此内容类型将用于发布Drupal相关事件，例如年度DrupAlcons等）**

2）**网站（网站截图和网站信息）（此内容类型将用于发布为Drupal提供信息、教程、模块或主题的站点）**

3）**用户组（会议地点和组织者详细信息）（此内容类型可用于发布本地组的站点，用于讨论和学习Drupal）**

4）**公司（公司logo和地址）（此内容类型可用于发布提供Drupal相关服务的业务）。**

**Chapter6—drupal字段**

1. **目的：我们开始了解如何使您的内容类型具有独特性、趣味性和实用性。（将不同类型的字段添加到内容类型）**

2. **字段类型：标题，主体，图片，分类（Taxonomy）**

**文本(5种不同类型)、布尔、注释、日期、电子邮件、链接、****数字****(3种不同类型)、列表(用于数字和文本)、内容引用、用户参考、其他参考(太多而不能在此列出)****，电话**

3. **内容类型添加字段：**

1）**网站类型：添加屏幕截图，评论，是一个官方的Drupal站点？网站链接等字段**

2）**公司类型：重用在其他内容类型上创建的几个字段，并添加另一种类型的字段。正文，图片，术语参考：标签，列表(文本)：服务，链接:公司网站,评论**

3）**事件类型：正文，图片，链接，评论，十进制：事件价格，日期，实体引用：事件发起人**

4. **管理显示：表单管理显示，管理显示（默认，摘要显示）**

5. **用户组字段：正文：用户组描述，链接：用户组网站，文本：会议地点，内容参考：组织者**

6. **分类（taxonomy）:vocabulary(词汇：这是一组术语的名称), terms(术语：这些关键词和短语实际上是对你的内容进行分类的)，Term reference field（术语参考字段：这是您的术语如何连接到您的内容），创建组织术语有层次**

 

**Chapter7—drupal模块**

1. **通用模块：**

1) **Address（地址）:将地址字段添加到内容类型的模块。这将有助于我们的事件内容类型。**

2) **Simple GMap（简单的GMap）:另一个事件字段。这个在你的内容页面上放了一张地图。**

3) **Video Embed field(视频嵌入字段)：为你的文章内容增加深度的另一种方法是包括一个视频，增强你的文本。**

4) **poll(投票)：一种内容类型，使您能够向网站访问者提出一个简单的问题并收集他们的答案。**

5) **Add To Any(任意添加)：一个模块，它添加了与内容相关的功能，即站点访问者共享内容页面的能力。**

6) **Sitemap(网站地图)：一种快速简便的方式，为访问者提供一个页面，显示您的网站结构一目了然。**

7) **Pathauto(自动路径)：添加到新站点的第一个模块之一。它使您可以为URL创建模板，而不必使用默认值或手动创建别名。**

8) **Meta Tag(元标签)：不要与术语标记混淆，这是在网页标题中创建<meta>标记的模块。**

9) **Google Analytics(谷歌分析)：谁不想知道他们的网站访问者呢？你将需要一个谷歌分析帐户。**

7. **改进内容类型：添加Telephone字段（在内容类型-event里选择），map字段；**

8. **改进文章类型：添加video字段**

9. **允许访客提供反馈：添加telephone字段到联系表单类型，poll（内容增加poll选项卡），添加社交共享链接**

10. **将SEO**支持添加到DRUPAL：metatag

**11.如何查找模块: 从Drupal.org下载,https://drupal.org/project/project_module****.**

|      |                                                              |
| ---- | ------------------------------------------------------------ |
|      | ![img](file:///C:\Users\ASUS\AppData\Local\Temp\ksohtml4344\wps4.jpg) |

\12. 评估模块

 

**Chapter8—drupal菜单**

1. 菜单只是在您的Drupal站点上创建导航的一种主要的方式。

2. **创建菜单链接方式：法一：在创建或编辑内容时，选中“提供菜单链接”框。法二：转到结构，菜单，或者添加一个新的链接或移动一个现有的链接。**

3. **菜单权重：数值越大，菜单越靠后（从-50—50）**

4. **父子菜单：添加Admin Toolbar模块插件**

 

**Chapter9—drupal区块（drupal blocks）**

1. **菜单块，品牌块，内容块，模块块，自定义块（主页面的侧边栏块）**

2. **区分不同类型的块。创建自定义块。创建自定义块类型。在你的网站上放置一个街区。将块放置在特定的你网站上的网页。**

3. **在一定条件下显示块：ContentType：只有在某些内容类型上才会出现块的选项。Pages：根据URL显示内容的选项。Roles：限制哪个角色可以看到哪个块的选项。**

 

**Chapter10—drupal主题**

1. **Bartik,Seven,Stark**

2. **Bartik换颜色，换logo**

3. **安装主题：Danland Theme, Drupal8 Zymphonies Theme, Breeze Theme（subtheme）并调整块布局到合适的位置**

4. **修改主题原则：1）除非您正在应用主题或模块的开发人员提供的代码修补程序，否则第一条规则是不修改主题或模块的代码。2）如果您想要更改主题，如更改颜色或字体，甚至更改主题使用的图像，我们建议创建一个子主题。**

5. **寻找合适的主题：https://drupal.org/project/project_theme，从核心兼容性过滤器中选择8.x并单击“Search”。如何判断一个主题是否是一个基本主题base theme？描述应该说明它是，或者说它是一个“starter theme”。**

6. 

|      |                                                              |
| ---- | ------------------------------------------------------------ |
|      | ![img](file:///C:\Users\ASUS\AppData\Local\Temp\ksohtml4344\wps5.jpg) |

评估主题：

1）**Description：这个主题做什么，它的特点，要求，和一些有关安装的方向。**

2）**Project Information** **：该页面的此区域包含一些有用的信息。首先，它告诉您**	**是否正在积极维护和更新主题。其次，它将告诉您主题是否经常被下载或安装。ledger** 	**分类账，分户账，总账**

3）**Downloads: 与模块一样，建议在现场使用绿色区域中的主题。**

4）**Sidebar: 维护人员,问题，资源（文档），开发**

 

**Chapter11—drupal视图（DRUPAL VIEWS）**

1. **视图主要功能：显示：视图使您能够创建自己的页面、块、RSS提要等；格式：视图使您能够在表、网格、列表、幻灯片显示、日历等中格式化信息；字段：使用视图，您只能显示所需的字段。您可以根据您的选择显示、隐藏、重新排序和更改字段的显示。Filter：视图使您能够根据内容类型、分类法术语、发布日期或许多其他条件进行筛选。排序：视图使您能够按字母顺序、受欢迎程度、作者名称或您选择的任何标准进行排序。**

2. **用视图创建块****：事件块，公司块，用户组，网站组等（放在secondary区域）**

3. **用视图创建页面：为以上块创建对应的登录页面，生成页面链接，对应不容视图功能包括通过设置视图中的显示、格式、字段、筛选器、排序和其他功能，您可以从头开始创建视图页。您还看到了多种格式，包括HTML列表，未格式化的列表、表和网格，幻灯片。**

4. **日历：导入日历模块和视图模板模块；幻灯片：导入Views Slideshow，Libraries，使用外部库来支持幻灯片的显示**

5. **视图总结：专注于这五个决策，您就可以创建您想要的许多视图。**

**1）显示：您想要页面、块还是rss ？**

**2) 格式：您想要列表、网格、表格、幻灯片或其他内容吗？**

**3）字段：要显示哪些字段？**

**4) 筛选器: 是否要向下搜索并只选择某些内容?**

**5)排序：您想如何组织所有显示的内容？**

 

**Chapter12—Drupal布局模块**

1. **你需要专注于三个模块：**

1）**Display Suite：使您能够准确地控制各个内容项的布局。**

2）**FieldGroup: 提供在折叠菜单或选项卡中分组字段的能力。**

3）**Panel: 面板使您可以组合来自整个站点的不同元素。**

**2.Display Suite：install the Layout plugin** **Module** **and Display Suite.**

2. **设置内容类型的布局显示：设置event,再显示管理display manage里面两行，三行。。。**

3. **FieldGroup模块：安装field_group模块,设置websties**

4. **Panel: 安装tool suite, panels, page Manager,---page451**

 

5. **为了使这些页面能够像现在一样出现，您做了什么？**

1）**.创建一个内容类型：Eventor Company。**

2）**.添加字段：事件标识、事件价格、赞助商等等。**

3）**.增加一个主题：微风。**

4）**.创建并放置块：新事件或公司。**

5）**.使用布局模块：字段组或显示套件**

 

**在创建内容类型之前，不能添加字段。只有拥有正确的内容类型和字段，才能添加内容。如果没有添加任何内容，则无法创建视图块。如果您没有任何字段、内容，有时也没有可用的视图，就不能使用布局模块。**

 

**举另一个例子：你做了什么来创建你的主页？**

1）**设置内容类型。**

2）**添加字段：文章、用户组和站点所有需要的字段。**

3）**添加一个主题：微风。**

4）**创建块：幻灯片现在，再加上新的网站，公司等等。**

5）**使用布局模块：面板。**

 

**Chapter13—完成网站设计**

1. **自上而下修改：完成metadata, slideshow， sidebar， frontpage**

2. **结构-视图-frontpage**

 

**Chapter14—drupal用户**

1. **解释Drupal角色和权限：匿名用户，验证用户，管理员，写者，主持人（论坛+评论）**

2. **确保正确设置用户帐户有四个步骤：**

1）**.添加一个角色。**

2）**.设置角色权限。**

3）**.创建用户。**

4）**.测试用户，以确保它具有正确的权限。**

**3.添加用户信息**

 

**Chapter15—drupal网站管理**

1. **目的：更新模块和主题；禁用或卸载模块和主题；使用其他措施保护您的网站；备份你的网站。**

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

**附录1：常用模块安装**

**1.地图：**http://drupal.org/project/simple_gmap

**2.video field(媒体字段)：**https://www.drupal.org/project/video_embed_field

**3.poll field:** http://drupal.org/project/poll

**4.addtoany:** http://drupal.org/project/addtoany

**5.metatag(元标签)：**<http://drupal.org/project/metatag>

**依赖token：**http://drupal.org/project/token

**6.Admin Toolbar（管理工具栏，显示下拉菜单）：**https://drupal.org/project/admin_toolbar

**7.Danland Theme**: <https://www.drupal.org/project/danland>

**8.Drupal8 Zymphonies Theme：**https://drupal.org/project/drupal8_zymphonies_theme

**9.Breeze Theme:**https://drupal.org/project/breeze  https://drupal.org/project/bootstrap

**10.有关创建子主题的信息：**https://drupal.org/docs/8/theming-drupal-8/creating-a-drupal-8-sub-theme-or-sub-theme-of-sub-theme.

**11. drupal付费主题网站：**http://themeforest.net/category/cms- themes/drupal

<http://templatemonster.com/drupal-themes.php>

<http://morethanthemes.com>

**12.Devel模块：**<https://drupal.org/project/devel>

**13.日历：**http://drupal.org/project/calendar.

**14.视图模板：**https://drupal.org/project/Views_templates

**15.幻灯片：**http://drupal.org/project/views_slideshow. Install Views Slideshow and Views Slideshow Cycle module. 

http://drupal.org/project/libraries

https://github.com/malsup/cycle

**16.Display Suite:** <https://drupal.org/project/layout_plugin>（可能不需要这个，看ds的依赖）

http://drupal.org/project/ds 

**17.用户组模块：**<https://drupal.org/project/field_group>

**18.panel:** https://drupal.org/project/ctools

https://drupal.org/project/panels

https://drupal.org/project/page_manager（可能不需要这个，看ctools里面有）

**19.切换用户Masquerade：**http://drupal.org/project/masquerade. 

**20.备份：Install Backup and Migrate** http://drupal.org/project/backup_migrate. 

 

**问题：**

1. **Q:模块兼容问题，导致网站出现“网站**遇到了不可预知的错误。请稍后再试。”的提示。

  **A:目前解决办法：去看apache的error log 定位错误模块，去web根目录的module中删除出问题的模块。**

2. **有些模块下载之后，尤其是版本是beta和alpha的居多，安装时会跳出问题1的错误提示，然后即便安装好也不会在网站中配置完，需要过一段时间（半天？）会在菜单栏中自动配置。**

3. **网站首页打开速度不稳定，有时候巨慢，不知道是不是网速原因，其他页面速度正常。**

 

 

 

 