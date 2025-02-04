# 管理用户的自定义数据

<LastUpdated/>

路径：**设置->字段管理->用户字段管理->用户扩展字段** 

用户自定义字段是除了 [基础用户字段](/guides/user/user-profile.md) 之外，可以给用户对象添加的额外字段。开发者可以通过设置自定义字段，存储**少量**业务相关的数据。

## 配置自定义用户字段

可以定义以下几种类型的自定义字段：

- 字符串；
- 数值；
- 日期；
- 布尔值；
- 枚举值；

1. 你可以在 **添加用户扩展字段** 窗口配置自定义用户字段：

![](../images/extend-column.png)

2. 配置自定义字段之后，你可以开启应用的注册信息补全页面，让用户补全这些自定义字段的信息。

    a. 在 **应用->自建应用->应用详情页->高级配置** 标签页开启 **自定义本应用的登录框** 开关。
    
    ![](../images/extend-column-supplement-1.png)

    b. 然后切换到 **品牌化**，在 **登录注册信息补全** 模块勾选 **注册时信息补全** 开关。
    
    ![](../images/extend-column-supplement-2.png)

    c. 添加自定义字段：
    
    ![](../images/extend-column-supplement-3.png)

    d. 点击 **保存**。

3. 访问应用的登录页面。</br>用户点击注册之后将跳转到下面这个注册信息补全页面：

    <img src="../images/extend-column-supplement-4.png" style="display:block;margin: 0 auto;">

用户成功注册之后，你可以在用户详情页面看到用户刚刚输入的自定义字段值：

<img src="../images/extend-column-supplement-5.png" height=300 style="display:block;margin: 0 auto;">

## 使用 API & SDK 管理用户自定义数据

!!!include(common/sdk-list.md)!!!

<StackSelector snippet="udf" selectLabel="选择语言" :order="['java', 'javascript', 'python', 'csharp', 'swift']"/>
