### 基于SpringBoot + Vue的家具维修售后系统.

#### 安装环境

JAVA 环境 

Node.js环境 [https://nodejs.org/en/] 选择14.17

Yarn 打开cmd， 输入npm install -g yarn !!!必须安装完毕nodejs

Mysql 数据库 [https://blog.csdn.net/qq_40303031/article/details/88935262] 一定要把账户和密码记住

redis

Idea 编译器 [https://blog.csdn.net/weixin_44505194/article/details/104452880]

WebStorm OR VScode 编译器 [https://www.jianshu.com/p/d63b5bae9dff]

#### 采用技术及功能

后端：SpringBoot、MybatisPlus、MySQL、Redis、
前端：Vue、Apex、Antd、Axios

平台前端：vue(框架) + vuex(全局缓存) + rue-router(路由) + axios(请求插件) + apex(图表)  + antd-ui(ui组件)

平台后台：springboot(框架) + redis(缓存中间件) + shiro(权限中间件) + mybatisplus(orm) + restful风格接口 + mysql(数据库)

开发环境：windows10 or windows7 ， vscode or webstorm ， idea + lambok


#### 前台启动方式
安装所需文件 yarn install 
运行 yarn run dev

#### 默认后台账户密码
[管理员]
admin
1234qwer

###### 管理员：
公告信息 、工单管理 、缴费记录 、家具产品 、维修信息 、预约管理 、服务类型 、评价管理 、员工管理 、客户管理 、数据统计 、工作状态 、评价统计 、家具出厂、数据统计。

###### 客户：
账户注册登录、个人信息修改、维修工单添加、维修费用支付、维修记录、工单评价。

###### 维修工：
注册登录、密码修改、维修任务、工单评价。

###### 客服：
注册登录、密码修改、工单管理 、维修信息 、预约管理 、服务类型 、评价管理 。

#### 项目截图
暂无

|  |  |
|---------------------|---------------------|
| ![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/75786fb6-fe41-40c1-b477-d6b426cc99a4.png) | ![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/02aecf0e-6584-4386-bf08-cc12586b31bd.png) |
| ![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/924132c9-abf2-4f3e-a551-2070161e814d.png) | ![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/3c990501-1604-4a11-b84c-967074155693.png) |
| ![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/67741639-0f37-4fa3-901b-20654f1c5195.png) | ![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/3e80c94c-d916-4926-84fb-cbe42e5c7673.png) |
| ![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/a89fdb17-4413-425a-9295-652de4a85864.png) | ![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/5c0ef5d2-5c06-41e4-8c8d-f78a11b02402.png) |
| ![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/ad4330d5-35a1-40ee-bb72-11a1dc0b15a9.png) | ![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/16c5f98b-e9f0-4499-8538-f6944a762769.png) |
| ![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/b6b8ef42-4a09-421e-84ea-9a890a0d09db.png) | ![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/27eb5235-8d3d-44c4-a4b5-0e3362fdd4aa.png) |
| ![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/b8a25bbe-9691-473e-b0e7-0fd6ce1d5e8e.png) | ![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/28ca5407-014a-41ef-b8ec-8ef67ccf7531.png) |
| ![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/b429d544-683b-4b46-b8c5-8a54df161777.png) | ![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/60a0a927-1ee2-4f36-8e47-2ba8bc44d365.png) |
| ![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/b899768b-603c-4e52-9ed4-61657ae3a59e.png) | ![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/289f6f88-cb11-4bd1-82ec-9658a12a4c30.png) |
| ![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/c4df9b0e-355b-42be-a71f-123962aa9e5c.png) | ![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/680d931f-686e-4ff0-aaf8-daf874d33906.png) |
| ![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/e3fc053e-1ea6-4c86-8f97-3e4a71acb04e.png) | ![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/7824ff09-076c-44cf-a57e-f50c3bd8d9d3.png) |
| ![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/e51f276b-6fcc-465e-95df-fc2f93107d0d.png) | ![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/13761b23-2bc8-4a22-a0d3-6a503e11a76c.png) |
| ![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/f80561bd-c1e4-4c20-9804-b5a089d3744b.png) | ![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/20476df5-bc00-47cd-9ef1-f45429ab8ad6.png) |

![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/work/936e9baf53eb9a217af4f89c616dc19.png)

#### 演示视频

暂无

#### 获取方式

Email: fan1ke2ke@gmail.com

WeChat: `Storm_Berserker`

`附带部署与讲解服务，因为要恰饭资源非免费，伸手党勿扰，谢谢理解😭`

> 1.项目纯原创，不做二手贩子 2.一次购买终身有效 3.项目讲解持续到答辩结束 4.非常负责的答辩指导 5.黑奴价格

> 项目部署调试不好包退！功能逻辑没讲明白包退！

#### 其它资源

[2024年-答辩顺利通过-客户评价👻](https://berserker287.github.io/2024/06/06/2024%E5%B9%B4%E7%AD%94%E8%BE%A9%E9%A1%BA%E5%88%A9%E9%80%9A%E8%BF%87/)

[2023年-答辩顺利通过-客户评价🐢](https://berserker287.github.io/2023/06/14/2023%E5%B9%B4%E7%AD%94%E8%BE%A9%E9%A1%BA%E5%88%A9%E9%80%9A%E8%BF%87/)

[2022年-答辩通过率100%-客户评价🐣](https://berserker287.github.io/2022/05/25/%E9%A1%B9%E7%9B%AE%E4%BA%A4%E6%98%93%E8%AE%B0%E5%BD%95/)

[毕业答辩导师提问的高频问题](https://berserker287.github.io/2023/06/13/%E6%AF%95%E4%B8%9A%E7%AD%94%E8%BE%A9%E5%AF%BC%E5%B8%88%E6%8F%90%E9%97%AE%E7%9A%84%E9%AB%98%E9%A2%91%E9%97%AE%E9%A2%98/)

[50个高频答辩问题-技术篇](https://berserker287.github.io/2023/06/13/50%E4%B8%AA%E9%AB%98%E9%A2%91%E7%AD%94%E8%BE%A9%E9%97%AE%E9%A2%98-%E6%8A%80%E6%9C%AF%E7%AF%87/)

[计算机毕设答辩时都会问到哪些问题？](https://www.zhihu.com/question/31020988)

[计算机专业毕业答辩小tips](https://zhuanlan.zhihu.com/p/145911029)

#### 接JAVAWEB毕设，纯原创，价格公道，诚信第一

`网站建设、小程序、H5、APP、各种系统 选题+开题报告+任务书+程序定制+安装调试+项目讲解+论文+答辩PPT`

More info: [悲伤的橘子树](https://berserker287.github.io/)

