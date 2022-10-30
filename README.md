# Board

# The rules of the Opathon

## CP1: 
According to the rules of the algorithm announced at the scene, the contestants find their team (numbered 1-5) and register to join in the background(this system).
The first person to join the team is the ""captain"", and the ""captain"" can be changed once during the competition.

选手根据现场公布的算法规则，找到自己在哪一队（编号1-5），并在后台进行登记加入。
第一位加入队伍的人为“队长”，比赛期间允许更换“队长”1次。

Grouping algorithm rules:
The new string S1 is formed with the name letter signed up in all uppercase (Chinese is converted to the corresponding pinyin, without any space) + the string ""2425"". The MD5 string S1 is used to obtain S2. The last character of S2 is converted to the decimal system to obtain the number I1. Add I1 by 5 to get the number I2, divide I2 by 5 to get the remainder I3. Add I3 by 1 to get the number I4, which is your group number (1-5).

分组算法规则：以自己报名的名字字母全部大写（中文则转成对应拼音，不加空格）+字符串“2425”，形成新字符串S1，将S1取MD5字符串，获取S2，将S2最后一位字母转成10进制，获取数字I1,将I1加5，获取数字I2，将I2除以5获取余数I3，将I3加1获取数字I4，I4即你的分组序号（1-5）

### - Grading rule:
Out of 10 points, when each teammate makes the wrong team for the first time, the team loses 2 points.

###  - 评分规则：
满分10分，每一位队友第一次选错队伍时，该队伍扣2分。

## CP2:
The team captain have to complete the team information setting, including: group name, team color, Logo(URL).

由队长完成队伍信息设置，包括：组名、队伍颜色、Logo。

### - Grading rule:
In chronological order, 10 points will be awarded to the first place, and 2 points will be deducted for each subsequent place.

###  - 评分规则：
按时间排序，第一名得10分，往后每一名递减2分，最多扣10分。

## CP3:
1. Set up a repository under the designated organization of GitHub
2. Invite all judges to join your repository.
3. Determine the open source protocol (written in the root directory of the open source project)
4. Explain why you chose this open source protocol in readme.md

1、在 GitHub 指定组织下建立仓库
2、邀请所有评委加入。
3、确定开源协议（在开源项目的根目录中规范编写）
4、在 readme.md 中说明为何选择这个开源协议

###  - Grading rule:
1. In chronological order, 10 points will be awarded to the first place, and 2 points will be deducted for each subsequent place.
2. If the open source protocol selection is unreasonable, 3 points will be deducted.

 - 评分规则：
1、按时间排序，第一名得10分，往后每一名递减2分，最多扣10分。
2、如开源协议选择不合理，扣3分。


## CP4:
Upload the first version of the NeuCharFramework(NCF)-based project.

上传以 NCF 为基础项目的第一个版本。

### - Grading rule:
In chronological order, 10 points are awarded to the first place, with a maximum of 10 points deducted for each subsequent place by decreasing 2 points.

###  - 评分规则：
按时间排序，第一名得10分，往后每一名递减2分，最多扣10分。

## CP5:
After 24 hours, a server will be provided with a decryption rule. The team needs to add a WebAPI to the project, enter the ciphertext, and return the decryption information. This version needs to be uploaded to the GitHub repository and published on the server, which is accessible.

24小时后，官方会提供一台服务器，服务器内会有一条解密规则，团队需要在项目中添加1个WebAPI，输入密文后，返回解密信息。此版本需要上传至GitHub仓库，并在服务器上发布，可访问。

### - Grading rule:
In chronological order, 10 points are awarded to the first place, with a maximum of 10 points deducted for each subsequent place by decreasing 2 points.

###  - 评分规则：
按时间排序，第一名得10分，往后每一名递减2分，最多扣10分。

## CP6:
1. Upload the complete work to GitHub.
2. Complete the release on the server.
3. Record (or shoot) a project introduction video within 10 minutes, which should demonstrate the complete project content and introduce the idea and characteristics of the project. A supporting PPT is required.

1、GitHub上传完整作品。
2、服务器上完成完整发布。
3、录制（或拍摄）一段10分钟以内项目介绍视频，需要演示完整的项目内容并介绍项目的思路和特点。需要有配套的PPT。

### - Grading rule:
1. In order of time, 20 points will be awarded to the first place, and a maximum of 20 points will be deducted by decreasing 4 points for each subsequent place.
2, the latest submission is 48 hours after the start of the competition, after which the channel is closed, no points will be scored.
3. After the background confirms the completion of CP 6, it is not allowed to submit or modify any more codes, otherwise the score of this round will be 0.


### - 评分规则：
1、按时间排序，第一名得20分，往后每一名递减4分，最多扣20分。
2、最迟提交为比赛开始后48小时，超过时间通道关闭，不得分。
3、后台确认CP 6完成后，不允许再进行任何代码提交或修改，否则本轮得分为0。


==========================================

Project topic selection and open source project citation requirements:

Creation content requirements:

1. Make a WeChat Mini-Program (personal test account can be used and authorized to teammates and judges)

2. The Mini-Program needs to complete the following tasks:

  A. Provide the login page and button. All the following functions can be used only after login;

  B. User information (OpenId and other data as much as possible) needs to be saved in the database and displayed in the administrator background;

  C. Provide a message board page, and the message content must be stored in the database using reversible encryption technology. The administrator can obtain in plain text, after the administrator approved, displayed in the front desk;

  D. Provide a decryption page to interconnect with CP5 so that users can decrypt on the page.

  E. Develop a crawler/spider (the target address will be given in the course of the competition, 36 hours later), which will crawl the real-time competition results and display the real-time competition results in the page of the small program (it needs to be beautified again);

3. Open source projects that must be selected and used in the project. Key algorithms and interfaces are supported by:

  A.	Senparc.Weixin SDK

  B.	NeuCharFramework

  C.	CO2NET

  D. Other friendly types of open source protocol projects

4. readme.md must contain a description of the third-party open source framework that is not provided by Microsoft /.NET, including the name, open source address, open source protocol, and used functions.


* CP: Check Point
* The organizer reserves the right of final interpretation of the results produced in the activity.
