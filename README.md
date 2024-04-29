# 专业：计算机科学与技术

## 姓名：贺磊

## 学号：82342204

## 创建github账户

进入github的官网：https://github.com/，点击右上角的“Sign up”，然后输入自己的邮箱地址，新建一个密码，以及用户名称，我的用户名称是hl7321，其中7321是我的手机尾号。

之后会进入一个验证环节，主要作用是判定我是不是真实用户。

判断完之后github会发送一个验证码到我的邮箱中，我这里使用的是我的qq邮箱，因此打开邮箱查看验证码，输入完成之后会自动创建账户。

选择登入，输入账号密码之后就完成了账号的创建。

## 建立一个xxDataMining

## 上传自己的ppt到hlDataMining中

点击我的库，然后选择add file ，随后将自己的ppt文件拖拽至上传界面，点击commit change，即添加完成。

## 想学习或获得的计算机技能：使用深度学习框架进行视频异常检测任务

## 视频异常检测方向简介

视频异常检测是计算机视觉领域的一个研究方向，它主要关注于识别视频中的异常行为或事件。这些异常可能包括但不限于犯罪行为、交通事故、设备故障、人群异常聚集等。视频异常检测在安全监控、交通管理、工业自动化和医疗健康等领域有着广泛的应用。

## 视频异常检测方向的基本流程

### 该方向的基础研究方法

#### 基于重构
基于重构的视频异常检测方法的核心思想是通过训练正常视频数据来获得正常数据的分布表示。在测试过程中，正常测试样本会具有较小的重构误差，而异常样本的重构误差则较大，从而实现视频的异常检测。

#### 基于预测
基于预测的视频异常检测方法通常假定一段连续的正常视频存在某种有规律的上下文联系，可以学习这种依赖关系并较好地预测未来帧，而异常视频往往违背这些依赖关系，导致未来帧不可预测。

#### 基于分类
基于分类的视频异常检测方法主要分为单分类和多分类两种。基于单分类方法的视频异常检测的主要思想是通过正常视频数据训练一个单类分类器，在测试过程中分类器只需要判别给定数据是否属于该类即可。

#### 基于回归
其主要思想是将异常得分作为评估指标，设置适当的阈值，若异常得分高于阈值，则将其视作异常，否则便为正常。

## 视频异常检测与深度学习算法

目前基于深度学习方法的视频异常检测研究主要面临着以下挑战和问题：
1. 正常视频和异常视频之间的数据不平衡性。
2. 缺乏异常视频的注释，对异常定义模糊。

随着现实生活中使用端到端的深度学习方法进行异常检测的部署，一些旧的数据集（如UMN、Subway或UCSD等）已经无法满足深度学习对于训练数据的需求，从而严重阻碍了端到端可训练深度学习模型的发展。

## 解决办法

解决办法有三：

1. **构建更多的数据集**：考虑到视频异常检测在实际生活中的应用，从泛化角度出发，未来应该构建更多大规模的、具有丰富异常数量和异常种类并且带有详细异常标签的数据集。
2. **设计更好的方法**：需要设计新的方法进行高效视频数据预处理和特征提取，进而突破处理速度的限制，使得这些系统能够用于实时的检测场景。
3. **提出更可靠的评估指标**：未来需要提出更可靠的评估指标，以评估精准检测到的局部异常区域。# hlDataMining
