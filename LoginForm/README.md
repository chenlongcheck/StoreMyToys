登录注册表单（JavaScript AJAX版）v1.0  
版本说明：  
    1. 注册后录入数据库并存入本地localstorage  
       支持判断用户名长度及非法字符、密码长度强度有效性、手机号以及邮箱有效性  
       支持邮箱提示  
    2. 进入网页优先读取localstorage ， 若存在已登录信息则查找数据库是否有对应信息  
       有 则直接登录  
    3. 登录时读取数据库进行比对，若成功提示登录成功并存入localstorage。  
    4. 若本地存在登录信息后再登录则覆盖保存    
    5. 支持手机号、邮箱、用户名登录，自动匹配  