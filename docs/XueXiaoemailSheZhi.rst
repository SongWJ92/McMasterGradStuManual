﻿学校email激活与收发
===========================
.. attention::
   **学校email只有等注册后才能激活**

激活方法
---------------------------------------
1. 方法一：在手机上登录mosaic

| 第一步：登陆mosica之后，在右上角点击三个横线的图标

.. image:: /resource/activate_email_on_phone_1.png
   :align: center

| 第二步：选择Navigator

.. image:: /resource/activate_email_on_phone_2.png
   :align: center

| 第三步：选择Email Management

.. image:: /resource/activate_email_on_phone_3.png
   :align: center

| 第四步：点击“Manage you Email Service”，找到学校的邮箱，选择Activate。同时也设置一下Primary Email Account，就是默认接受学校发的Email的邮箱。

.. image:: /resource/activate_email_on_phone_4.png
   :align: center

以上截图感谢17-PH-朱莹提供

收发方法
-------------------------------------------------
McMaster的email激活后，有两种方法可以收发 ：

1. 通过网页： https://studentmail.mcmaster.ca

2. 通过客户端email软件：在手机或电脑上，设置如下：

| Account type: IMAP 
| Incoming server: mcmasterimap.mcmaster.ca 
| Outgoing server: mcmastersmtp.mcmaster.ca 
| SSL encryption for both incoming and outgoing servers turned on. 
| Incoming port 993 
| Outgoing port 465 
| Outgoing server to require authentication using the same credentials as the incoming server. 

具体看这里： http://mcmaster.ca/uts/gmailforstudents/imapsetup.html 

如果Email收发不成功，请联系学校UTS，http://www.mcmaster.ca/uts/

注意事项： 
--------------------------------------
1. Iphone：Do not select Gmail as the mail provider, select Other。Set port to 465，not 587
2. Android phones：May require that the encryption method be set SSL-accept all certificates instead of just SSL. 
3. 用户名是你的MACID，不要加@mcmaster.ca， MACID区分大小写的 
4. After disabling multiple account log in on Google, it may be necessary to log into the McMaster account on the web in order to be able to set up IMAP. (Please go to https://studentmail.mcmaster.ca and log in, then log out and try the IMAP setup again.) 
5. 学校的邮件系统分为2部分：（1）full-time学生使用的是Google的企业邮箱服务，就是gmail的企业版，在国内无法登陆，甚至激活都不可以，大家来Canada之后再激活登陆。如果想在国内激活并访问，请自行搜索翻墙方法。（2）访问学者使用的是Microsoft Exchange企业邮箱，就是outlook的企业版，这个在国内可以登陆，现在已经可以激活并且使用了。
6. 学校的邮箱在没激活之前，都会先转发到你的申请邮箱里。学校Email激活后可以设置默认转发到McMaster的邮箱里，方法是mosaic->Student Center->Personal Information->email addresses，把你希望设置为默认接受学校邮件的Email勾上Preferred。
