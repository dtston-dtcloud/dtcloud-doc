# Amazon Echo音箱接入流程
## 1. Alexa Skill配置
### 1.1 创建亚马逊开发者账号
1）打开[亚马逊开发者中心](https://developer.amazon.com/)，点击Sign In，进入登录界面。
![Alt text](/assets/zh-cn/guidelines/echo/20171101105314.png)
2）点击Create your Amazon account，进入注册界面。
![Alt text](/assets/zh-cn/guidelines/echo/20171101105728.png)
3）填写注册信息，点击Create your Amazon account，完成注册。
![Alt text](/assets/zh-cn/guidelines/echo/20171101105845.png)
### 1.2 创建Skill
1）亚马逊账号注册成功，打开[亚马逊开发者控制台](https://developer.amazon.com/home.html/)，登录账号。
![Alt text](/assets/zh-cn/guidelines/echo/20171101110937.png)
2）登录成功后进入控制台，点击ALEXA进入管理界面，点击下面的Alexa Skills Kit的Get Started，开始配置Alexa。
![Alt text](/assets/zh-cn/guidelines/echo/alexa_manager.png)
3）点击Add a New Skill，添加新的Skill
![Alt text](/assets/zh-cn/guidelines/echo/add_new_skill.png)
4）配置Skill Information
![Alt text](/assets/zh-cn/guidelines/echo/config_skill_information.png)
a. Skill type:  Skill的类型，选择 “Custom Interaction Model”
<br/>b. Language: Skill的语言，默认选择English(U.S.)
<br/>c. Name:  Skill的名称, 定为 “Smart Light”
<br/>d. Invocation Name: Alexa的唤醒词，唤醒词有一定的限制规则，建议由容易发音识别的单词组成，提高唤醒准确度，详细说明可以参考[唤醒词命名规则](https://developer.amazon.com/docs/custom-skills/choose-the-invocation-name-for-a-custom-skill.html#invocation-name-requirements)。这里定为 “smart light”
<br/><br/>**点击保存**，保存后点击Nexe，进入Interaction Model
![Alt text](/assets/zh-cn/guidelines/echo/save_skill_information.png)
5）配置Interaction Model