# 如何获取Gmail邮箱的授权码？

## 步骤详解

### 1. 打开谷歌邮箱设置

进入谷歌邮箱的设置页面：[Gmail设置](https://mail.google.com/mail/u/0/#settings/fwdandpop)

![image](https://github.com/jaydenzaydenjd/Gmail/assets/169983666/8aa03957-5cc4-4722-988a-d8089f963aa1)


### 2. 启用IMAP

在“转发和 POP/IMAP”选项卡下，启用IMAP。

![image](https://github.com/jaydenzaydenjd/Gmail/assets/169983666/d227ed07-6c1b-4edf-80a1-64eb3d02c58d)


### 3. 管理您的Google账号

点击右上角的Logo，然后选择“管理您的Google账号”。

![image](https://github.com/jaydenzaydenjd/Gmail/assets/169983666/cb8ad813-0fa1-4281-a6ef-55a165ae212e)



### 4. 设置应用专用密码

返回“管理您的Google账号”页面，找到安全性选项，设置应用专用密码。

![image](https://github.com/jaydenzaydenjd/Gmail/assets/169983666/13435c2b-0873-4936-952e-0e3e5d96e6f4)


### 5. 生成并复制专用密码

生成应用专用密码，并将其复制。

![image](https://github.com/jaydenzaydenjd/Gmail/assets/169983666/16a90ce3-9339-4115-9df0-029c8fe6c164)


### 6. 应用到OpenCart中

将生成的授权码应用到OpenCart的邮件设置中。

```bash
#Mail Engine
SMTP

#Mail Parameters
demo@gmail.com

#SMTP Hostname
ssl://smtp.ym.163.com

#SMTP Username
demo@gmail.com

#SMTP Password
生成的授权码

#SMTP Port
465

#SMTP Timeout
5

确保在“store”选项卡内的“E-Mail”同步修改为“demo@gmail.com”。

