# 智能毕业纪念册APP
- 发布时间：2019年12月6日
- 项目名称：智能毕业纪念册APP
- 项目设计者：林泽伟
# 价值主张设计
## 加值宣言
百度人脸搜索API，在指定人脸集合中，找到最相似的人脸，查找在他人的回忆照片中，有没有自己的存在；就算是多人的图片，也可以在指定人脸集合中，找到这多个人脸分别最相似的人脸
百度人脸检测API，上传自己的照片和信息，通过照片就能查询用户的属性信息，如年龄、性别等

## 核心价值
能够为用户提供一个能够回忆校园时光的平台，添加自己的同学，可以把自己在校期间拍的图片上传到APP内的朋友圈与朋友分享，让校友通过纪念相片了解自己的信息，让用户能够随时随地查看自己在校园期间与他人有意无意间的合影，上传自己的照片，查找在他人分享的照片中有没有自己，或者与他人的合影，或者是他人拍摄的关于自己的图片。

## 核心价值与用户痛点 
在校期间，会经常参加一些活动，与校友拍合照，但是也是会忘记要照片，但是毕业之后想要看之前的有关自己的照片，却有不知道去哪里找；
在一些活动的大合照中，也有自己的身影，需要查看有没有校友分享这种照片；
需要一个平台专门用于分享自己在校期间的回忆相片；

## 人工智能概率性与用户痛点
- 不同的控制度下所对应的质量控制阈值，如果检测出来的质量信息某一项不符合控制阈值的要求，则会返回错误信息。
- 不同的控制度下所对应的活体控制阈值，如果检测出来的活体分数小于控制阈值，则会返回错误信息。
- 误拒率: 把真人识别为假人的概率. 阈值越高，安全性越高, 要求也就越高, 对应的误识率就越高

## 需求列表与人工智能API加值
- 需求：用户想查找其他用户有无发布有关自己的照片
- API：百度人脸搜索
- 需求：查找其他校友的信息
- API: 百度人脸检测

