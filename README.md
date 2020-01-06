# -
帮老板报奖，发现很多扫描件要转成电子版需要手动打字，这样操作费时且容易出错，因此该项目旨在批量提取Word中的文字，存入文件夹后使用Baidu API 讲所有文字读取到一个.txt文档中。

首先，假设您扫描的所有图片都保存在一个文件中，并且您想要捕获图片中的文字信息，那么首先需要做的是，您需要调用百度【文字识别】API（以下过程可能不超过5分钟），你需要在https://ai.baidu.com/?track=cp:aipinzhuan|pf:pc|pp:AIpingtai|pu:title|ci:|kw:10005792 官方网页上申请免费账号，然后进入页面中的【控制台】-【文字识别】，得到APP_ID = '********'， API_KEY = ''和SECRECT_KEY=’’。
将这三个信息填写到代码相应位置，运行即可。
！！注意：请提前备份好自己的扫描件文件，因为在识别代码后，程序会删除相应的图片！！
    

Recently, I found that many scanned documents need to be typed manually to be converted into an electronic version. This operation is time-consuming and error-prone. Therefore, the project aims to extract the text in Word in batches and use Baidu API to read all the text after saving them Into a .txt file.

!! !! Note: Please back up your scanned files in advance, because after the identification procedure, the program will delete the corresponding pictures! !!

First, assuming that all the pictures you scanned are saved in a file, and you want to capture the text information in the picture, then the first thing you need to do is to call the Baidu [Text Recognition] API (the following process may not exceed more than 5 minutes ), You need to apply for a free account on the official website at https://ai.baidu.com/?track=cp:aipinzhuan|pf:pc|pp:AIpingtai|pu:title|ci:|kw:10005792, and then enter the page [Console]-[Text Recognition], get APP_ID = '********', API_KEY = ‘’ and SECRECT_KEY = ''.
Fill these three pieces of information to the corresponding locations in the code and run.
!! !! Note: Please back up your scanned files in advance, because after the identification procedure, the program will delete the corresponding pictures! !!

