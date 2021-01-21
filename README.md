# RedRockiOSWinnterWork
网校2021年iOS寒假考核

#  2021年红岩网校iOS寒假考核

##  关于寒假考核的一些建议

**写在最前面，希望你们能重视**

- 这学期进度拉得很快，你们的基础都比较薄，很多东西似懂非懂，在开始写寒假考核之前你们最应该做的事是去巩固之前学的知识。寒假考核的本质上也是让你们熟悉并运用之前所学的知识
  - b站小码哥视频https://www.bilibili.com/video/BV1eW411K72i?from=search&seid=8225910973721979473，评论区有全套的网址，看全套太费时间，根据每个part的目录挑自己不熟悉的地方学
  - 结合群里学长们发的课程资料学习，他们做的很用心干货满满。
- 在你复习完之后，应该信心满满的开始写考核，但是请注意不要一上来就直接画UI，请先想一下这个app你该怎么做,思考范围包括但不限于：
  - 观察这个app有几个界面，思考这些界面是通过怎样的逻辑联系的，要对整个app大体上有个概念
  - 观察单个界面，思考：
    - 此界面是由哪些UI控件组合，我要怎么去实现这样的UI效果
    - 此界面涉及哪些逻辑操作，我该怎么去实现
  - 思考不同界面是否有相同的地方，我是否可以把相同的地方的代码抽离封装并复用
- 写考核的时候你肯定会有一句句“卧槽”，踩坑很正常，一个bug找数个小时很正常，放平心态，并且把踩的坑和解决方案用文档记录下来，这些文档将是你们最宝贵的财富
- 假期时间自由度很高，这给了你们宝贵的机会学习知识，但也会让你们懈怠，以致容易沉迷玩乐无法自拔。少年，相信我，你一定会在以后想几个大耳巴子抽死假期疯狂玩乐的自己。所以，好好利用假期多学点知识，过了假期就再没有一整天痛痛快快学习或者写代码的机会了。

##  考核目的

- 掌握这一学期学习的知识：通过考核作业让大家熟悉之间学习的知识，并将其结合应用
- 筛选：本次考核不通过的的同学无法参与移动部门下学期的培训，请务必认真对待
- 选择：下学期取消课堂形式讲课，采取双向选择的导师制度培训，本次考核将成为你能力的主要体现，请用心对待。

##  考核内容

- **题目1:**自由发挥，做一款自己心仪的app，视觉图以及api接口需自行寻找
- **题目2:**仿写知乎日报app，视觉图参照app，接口文档见下方

## 考核要求

### 健康要求

- **严禁熬夜写代码！！！**
- **严禁熬夜写代码！！！**
- **严禁熬夜写代码！！！**

- 代码诚可贵，健康价更高。不要牺牲健康作业。此次寒假作业布置的内容和难度都有一些，你们也需要时间去学习巩固这学期学的知识，最后成绩是根据作业质量和完成度评分，所以请根据自身身体情况工作

###  App要求

####  基本内容

- 对于题目2，UI请严格参照知乎日报app制作，app上的功能不要求全部实现，但是出现的界面要全部制作出来。不要自由发挥。

- 屏幕适配

- 代码规范，命名，注释。不要写些全篇命名、格式、注释奇奇怪怪让人看不懂的阴间代码。项目里代码规范要求包括但不限于：

  - 命名要求

    - 命名采用英文意思命名，不要用拼音命名，比如猫类命名 正确 Cat,错误 mao

    - 类名采用大驼峰命名法
    - 方法、属性、变量采用小驼峰命名法

  - 注释要求：

    - 每个类的.h文件需在第一个 `#import<....>的上面写明这个类是用来做什么

    - 不易看懂的属性需注释属性说明该属性代表含义和用途
    - 方法的实现代码前需注释说明这个方法是做什么的，例如用来网络请求什么数据等

- 完整性，根据提供的api文档，实现绝大部分功能

#### 加分内容

- 了解并使用MVC、MVP、MVVM等架构模式
- 趋近原版的UI
- 简洁、优雅、可读性高的高质量代码
- 封装常用类，包括但不限于多次使用的view、网络请求工具类、公共宏定义类prefix等

#### 减分内容

- UI制作难看
- 功能简陋，未达基本要求
- 代码冗余，可读性差

###  功能要求

1.以下功能原则上必须实现：

- 首页：
  - banner
  - 新闻列表
- 新闻详情页：
  - 新闻内容文本展示
  - 点赞按钮点击后图片颜色变化，点赞数目变化，出现提示“点赞成功”或“取消点赞”
  - 收藏按钮点击后图标变化，出现提示
- 个人界面
  - 实现伪登录、退出登录功能

2.特殊功能：

以下内容为加分项：

- 适配黑暗模式
- 动画
- 其他app展示但是要求实现之外的功能

###  时间要求

- 截止时间2021年2月27日23:59
- 请预留出两个小时用于准备README

### 提交要求

- 需要将项目推送到GitHub上，并附上README,需包含：
  - APP简要介绍（背景、功能、使用步骤等）附Gif图片
  - app构成板块，开发思路
  - 使用的比较重要的技术以及知识点
  - 心得体会
- 发送GitHub仓库地址至mredrockios@163.com
- 邮件标题：2021寒假考核-学号-姓名。如: 2021寒假考核-2019x x x x x x-毛国栋

 ##  接口文档

- BaseURL:https://news-at.zhihu.com/api/3
- 所有请求方式均为GET

### 首页

####  最新新闻（当日新闻）

- 请求url：/news/latest

- 请求参数：无

- 返回实例

  - JSON:

    ```json
    {
        date: "20140523",
        stories: [
            {
                title: "中国古代家具发展到今天有两个高峰，一个两宋一个明末（多图）",
                ga_prefix: "052321",
                images: [
                    "http://p1.zhimg.com/45/b9/45b9f057fc1957ed2c946814342c0f02.jpg"
                ],
                type: 0,
                id: 3930445
            },
        ...
        ],
        top_stories: [
            {
                title: "商场和很多人家里，竹制家具越来越多（多图）",
                image: "http://p2.zhimg.com/9a/15/9a1570bb9e5fa53ae9fb9269a56ee019.jpg",
                ga_prefix: "052315",
                type: 0,
                id: 3930883
            },
        ...
        ]
    }
    ```

  - 分析：

    - `date` : 日期
    - `stories` : 当日新闻 
      - `title` : 新闻标题
      - `images` : 图像地址（官方 API 使用数组形式。目前暂未有使用多张图片的情形出现，**曾见无** `images` **属性的情况**，请在使用中注意 ）
      - `ga_prefix` : 供 Google Analytics 使用
      - `type` : 作用未知
      - `id` : `url` 与 `share_url` 中最后的数字（应为内容的 id）
      - `multipic` : 消息是否包含多张图片（仅出现在包含多图的新闻中）
    - `top_stories` : banner滚动显示的内容

####  过往新闻

- 请求url：/stories/before/日期

- 请求参数：日期 格式：2021年1月20日表示为：20200120。如果需要查询 1 月 18 日的消息，before后的数字应为20210119

- 返回实例：

  - JSON：

    ```json
    {
        "date": "20210119",
        "stories": [
            {
                "image_hue": "0x273438",
                "title": "从《大秦赋》看中国历史剧的兴衰",
                "url": "https://daily.zhihu.com/story/9732166",
                "hint": "宗城 · 10 分钟阅读",
                "ga_prefix": "011907",
                "images": [
                    "https://pic1.zhimg.com/v2-46bd1f81ab5f7e3e86724dae58168ac9.jpg?source=8673f162"
                ],
                "type": 0,
                "id": 9732166
            },
            {
                "image_hue": "0xb3987d",
                "title": "篮球发展历史上有哪些奇葩的战术？",
                "url": "https://daily.zhihu.com/story/9732162",
                "hint": "healer · 3 分钟阅读",
                "ga_prefix": "011907",
                "images": [
                    "https://pic4.zhimg.com/v2-5bb60172a0c142d8682af3b346e0c443.jpg?source=8673f162"
                ],
                "type": 0,
                "id": 9732162
            },
           ....
        ]
    }
    ```

  - 分析：跟最新信息差不多，不再赘述。需要注意的是过往新闻返回的实例无top_stories即banner内容

###  新闻详情页

####  新闻内容（banner内容和新闻列表的新闻内容均是此内容）

- 请求url：/news/文章id

- 请求参数:该文章的id

- 返回实例：

  - JSON:

    ```json
    {
        "body": "<div class=\"main-wrap content-wrap\">\n<div class=\"headline\">\n\n<div class=\"img-place-holder\"></div>\n\n\n\n</div>\n\n<div class=\"content-inner\">\n\n\n\n\n<div class=\"question\">\n<h2 class=\"question-title\"></h2>\n\n<div class=\"answer\">\n\n<div class=\"meta\">\n<img class=\"avatar\" src=\"https://pic1.zhimg.com/v2-1200f5d58bfe9dbba37aa9e08329b914_l.jpg?source=8673f162\">\n<span class=\"author\">BioArt生物艺术，</span><span class=\"bio\">一心关注生命科学，只为分享更多有种、有趣、有料的信息。</span>\n<a href=\"https://www.zhihu.com/question/391735112/answer/1681549660\" class=\"originUrl\" h
      ......
      ,
        "image_hue": "0x3d6476",
        "image_source": "geralt / CC0",
        "section_thumbnail": "https://pic1.zhimg.com/v2-1698e35b2fd050308b5629133c16b9b6.jpg?source=8673f162",
        "title": "为何感染新冠病毒会失去嗅觉或味觉？",
        "url": "https://daily.zhihu.com/story/9732181",
        "image": "https://pic4.zhimg.com/v2-8c5b29894e274931716593775e375b69.jpg?source=8673f162",
        "section_id": 116,
        "share_url": "http://daily.zhihu.com/story/9732181",
        "js": [
            "http://news-at.zhihu.com/js/story.js?v=97942"
        ],
        "section_name": "奇怪的知识",
        "ga_prefix": "012007",
        "images": [
            "https://pic1.zhimg.com/v2-1698e35b2fd050308b5629133c16b9b6.jpg?source=8673f162"
        ],
        "type": 0,
        "id": 9732181,
        "css": [
            "http://news-at.zhihu.com/css/news_qa.auto.css?v=4b3e3"
        ]
    }
    ```

  - 分析：

    - body: HTML 格式的新闻

    - image-source: 图片的内容提供方。为了避免被起诉非法使用图片，在显示图片时最好附上其版权信息。

    - title: 新闻标题

    - image: 获得的图片同最新消息获得的图片分辨率不同。这里获得的是在文章浏览界面中使用的大图。

    - share_url: 供在线查看内容与分享至 SNS 用的 URL

    - js: 供手机端的 WebView(UIWebView) 使用

    - ga_prefix: 供 Google Analytics 使用

    - section: 栏目的信息

    - section_id: 该栏目的id

    - name: 该栏目的名称

    - type: 新闻的类型

    - id: 新闻的 id

    - css: 供手机端的 WebView(UIWebView) 使用

####  新闻额外信息

- 请求url:/story-extra/该新闻id

- 请求参数：该新闻id

- 返回实例：

  ```json
  {
      "long_comments": 0,		//长评论
      "popularity": 46,			//点赞数
      "short_comments": 13,	//短评数
      "comments": 13				//评论总数
  }
  ```

##  其他

- 最后所有作品是会拿出来展示答辩。

- 诸位，新年快乐，新一年少叹气，多开心。
