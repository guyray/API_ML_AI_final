发布名称|发布时间|发布人
---|:--:|---:
Mood Hunter（心轨）|2019.12.25|曾拱韬
项目状态|已完成|曾拱韬

# 情绪追踪APP
- 智能产品名称：Mood Hunter（心轨）
## [20x20PPT展示](https://github.com/guyray/API_ML_AI_final/blob/master/20x20.pptx)

# 价值主张写作
- 一句话版本：记录日常生活的情绪和感情生活，记录生活留念美好瞬间，情绪复盘加深自我认识来控制情绪

- 一分钟版本:心轨专注于引导使用者随时记录情绪，以及想法、感知、造成情绪的原因等，帮助改善使用者的情绪状态；还能追踪情绪变化，并从心理学角度给予分析和建议。在积累一定的记录数据后，心轨就会提供直观的情绪统计功能。它能够展示特定时长内的情绪变化趋势图，情绪波动和心理状况一目了然。

# 一. 价值主张设计
## 1.1 加值宣言
#### 加值宣言
**便捷性与认知智能**
- 使用百度**情感倾向分析**API，识别日常记录的文字中的情感倾向，自动判断该文本的情感极性类别并给出相应的置信度，输出三种情感极性标签：积极、消极、中性，快速高效地记录情绪变化
- 使用Face++**人脸识别**API，对上传的自拍进行表情分析，自动判断该图片中表情的情感倾向与置信度，输出九种表情标签，提升情绪记录效率
- 使用科大讯飞**实时语音转写**API，把录入的语音实时转写为文字，再利用百度**情感倾向分析**API进行情感情绪判断，简化情绪记录方式

## 1.2 核心价值
#### 核心价值宣言

记录日常生活的情绪和感情生活，记录生活留念美好瞬间，情绪复盘加深自我认识来控制情绪

#### 目标用户
有意识通过调节情绪改善自己生活的人，如：在校大学生，职场人士、精神疾病患者、恋爱中的情侣、日记控

用户分类 | 用户范围
-|-
种子用户 | 在校大学生，职场人士 |
核心用户 | 职场人士、精神疾病患者 |
目标用户 | 有意识通过调节情绪改善自己生活的人 | 
潜在用户 | 在校学生 |

## 1.3 核心价值与用户痛点

#### 用户痛点宣言：
- 1）经常有各种小情绪，无法很好地控制自己的情绪？通过本APP完成情绪记录后，可以查询到自己的情绪记录，以及关于自己情绪的各项数据分析。
- 2）精神疾病患者可以轻松记录自己的情绪变化，形成月度情绪曲线，协助监测病情发展
## 1.4 人工智能概率性与用户痛点 

- 用户记录的文本和图像生成的情感标签上置信区间供用户参考，若标签不准确用户可随时手动进行更改
- 对于情感倾向的识别出错时，对于普通用户来说并没有太大的影响，但对于要以此作为参考的精神疾病患者来说，不能直接以此作为就诊的参考数据，但对于患者进行自我情绪监控来说，识别上的错误并不会对治疗方案与用药造成影响，仅作为参考使用


## 1.5 需求列表与人工智能API加值 

#### 需求列表
用户案例 | 对应API |  重要程度
-|-|-
一天结束想整理一下今天的照片，记录一下今天的感受，但很累了又不想操作太麻烦 | 情感倾向分析、人脸表情识别 | 重要 |
记录一段时间之后想回顾前段时间的情绪变化，看到对自己情绪的分析 | 情感倾向分析、人脸表情识别 | 次重要|
躁郁症患者想知道自己是处于相对躁期还是抑郁期，希望可以通过数据看到 | 情感倾向分析、人脸表情识别 | 次重要|
-----------
# 二. 原型.[原型文档下载](https://guyray.github.io/API_final_prototype/)

## 2.1 交互及界面设计 （部分功能展示）
 #### 1) 新建日记
![首页](https://upload-images.jianshu.io/upload_images/9893857-d3688c66cd07210d.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

#### 2) 查看统计数据
![统计数据](https://upload-images.jianshu.io/upload_images/9893857-957edde3744dabf6.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
#### 3) 新增活动或提醒
![日历](https://upload-images.jianshu.io/upload_images/9893857-79cffad54772a5a4.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
#### 4) 编辑表情
![设置](https://upload-images.jianshu.io/upload_images/9893857-82e27bf3c256f8db.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

## 2.2 信息设计 
#### 1) 产品信息架构图
![产品信息架构图](https://upload-images.jianshu.io/upload_images/9893857-dfaea2f28f58abf3.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
#### 2) 产品功能结构图
![产品功能结构图](https://upload-images.jianshu.io/upload_images/9893857-fa1e6297f1d66b35.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
#### 3) 产品使用流程图
![产品使用流程图](https://upload-images.jianshu.io/upload_images/9893857-a4ca077cba0792bf.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)


## 三. API的使用与输出入展示
## 3.1 API调用测试
#### 1. FACE++人脸识别远程图片
##### - [完整代码示例](https://github.com/guyray/API_ML_AI_final/blob/master/API%E6%B5%8B%E8%AF%95%E4%BB%A3%E7%A0%81/%E4%BA%BA%E8%84%B8%E8%AF%86%E5%88%AB%E9%9B%86%E5%90%88%E6%B5%8B%E8%AF%95.png)
##### - 返回数据
![人脸识别返回数据](https://upload-images.jianshu.io/upload_images/9893857-300df3fb970dbfe5.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

字段 | 类型|  说明
-|-|-
emotion	 | Object | 情绪识别结果。返回值包含以下字段。anger：愤怒, disgust：厌恶, fear：恐惧, happiness：高兴,neutral：平静, sadness：伤心, surprise：惊讶 |

#### 2. 百度情感倾向分析API 
##### - [完整代码示例](https://github.com/guyray/API_ML_AI_final/blob/master/API%E6%B5%8B%E8%AF%95%E4%BB%A3%E7%A0%81/%E7%99%BE%E5%BA%A6%E6%83%85%E6%84%9F%E5%80%BE%E5%90%91%E5%88%86%E6%9E%90API%E6%B5%8B%E8%AF%95.html)



![百度情感倾向分析API](https://upload-images.jianshu.io/upload_images/9893857-4368c1bce40d059a.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

```
# 参数    说明    描述
# log_id    uint64    请求唯一标识码
# sentiment    int    表示情感极性分类结果，0:负向，1:中性，2:正向
# confidence    float    表示分类的置信度，取值范围[0,1]
# positive_prob    float    表示属于积极类别的概率 ，取值范围[0,1]
# negative_prob    float    表示属于消极类别的概率，取值范围[0,1]
```

#### 3. 科大讯飞实时语音转写API
##### - [完整代码示例](https://github.com/guyray/API_ML_AI_final/blob/master/API%E6%B5%8B%E8%AF%95%E4%BB%A3%E7%A0%81/%E8%AF%AD%E9%9F%B3%E8%BD%AC%E5%86%99API%E6%B5%8B%E8%AF%95.png)


##### - 返回数据
![科大讯飞语音转写返回数据 ](https://upload-images.jianshu.io/upload_images/9893857-301b0f24e2d4c8ea.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

##### - 对比：百度语音识别返回的结果
![百度返回结果](https://upload-images.jianshu.io/upload_images/9893857-1a6ff916e13d6072.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

## 3.2 API使用比较分析 

#### 人脸识别API对比
量规 | API排序 |  文字记录
-|-|-
兼容性 |**FACE++**=**Azure**>**百度**| 百度人脸识别测试图片URL许多都不能读取，最后必须把图片上传到百度产品的网站上才能获取图片 |
响应性|**Azure**>**Face++**>**百度**| 除了百度人脸识别外都可连续响应API的请求，百度人脸识别会出现无法获得返回数据或者是返回相同的数据,Azure的响应时间最短，百度人脸识别的响应时间最长|
识别准确性 |**FACE++**>**Azure**>**百度** | FACE++对于情绪的识别比AZURE更加敏感，会识别出更高的情绪反应。百度人脸识别在进行多人识别时只能识别一个人的面孔 |

#### 语音转写API对比
量规 | API排序 |  文字记录
-|-|-
兼容性 |**科大讯飞**=**腾讯**>**百度** | 许多音频百度的返回结果是为无法识别，而科大讯飞可以识别。|
响应性| **腾讯**=**百度**>**科大讯飞** | 科大讯飞识别时需要分片上传后再合并音频，之后再上传转写结果，识别时间比起百度稍长|
识别准确性 |**科大讯飞**>**腾讯**>**百度** | 科大讯飞对于中文的识别结果几乎没有错误，而百度的识别结果错误很多而且无法组成有意义的句子 |
## 3.3 API使用后风险报告
#### 一. API类别的现在及未来发展性
##### 1)  企业发展性
- 当前使用的API基于旷视的**Face++人脸识别**、百度自然语言处理的**情感倾向识别**、科大讯飞的**实时语音转写**。
- 旷视和百度都是中国人工智能领域的开拓者。其中旷视是基于深度学习算法的计算机视觉算法的引领者，百度AI专利申请量5712位列中国第一，在深度学习领域专利申请量位居全球第二。
- 科大讯飞是国内最大的语音技术提供商，其联手中科院推出了轰动世界的“讯飞输入法”，能直接将用户语音转化为文字，并且识别率高达97%以上。目前，微信与各语音记录APP的实时语音转写都由科大讯飞提供技术支持
##### 2) API前景：
- 目前，人工智能技术在图像处理领域发展得最好，其中人脸识别是最最成熟、应用最广的一项技术。旷视为美图旗下的美图秀秀App、美颜相机、美颜手机等一系列软硬件产品提供了人脸识别技术支持
- 百度自然语言处理部是百度最早成立的部门之一。其中，百度自然语言处理在深度问答方向经过多年打磨，积累了问句理解、答案抽取、观点分析与聚合等方面的一整套技术方案。篇章理解通过篇章结构分析、主体分析、内容标签、情感分析等关键技术实现对文本内容的理解，目前，篇章理解的关键技术已经在搜索、资讯流、糯米等产品中实现应用。在如此多的应用与数据支撑下，情感倾向分析API的识别与分析能力在未来将会不断提升

#### 二. 输入输出限制
**QPS并发限制**： 
- **百度情感倾向API**：以上两种计费方式在开通付费后，均可保证您 20 QPS 的并发需求，如果并发量无法满足业务需求，可通过工单形式进行商务咨询进行定制提升
- **Face++人脸识别API**：按量计费时，人脸识别API组（除人脸稠密关键点API）整组保障10QPS，开通[企业认证]后可翻倍至20QPS；在包时计费模式下，您可以按月或按天购买指定API组的QPS配额，最高QPS为30.
- **科大讯飞实时语音转写API**：并发数10路
#### 三. 定价
##### 1. 百度情感倾向分析API
**百度NLP下API免费额度**：每个接口累计50万次。通过企业认证后，每个接口每天50万次免费调用量，并发限制也将由2QPS提升至5QPS。

![免费额度](https://upload-images.jianshu.io/upload_images/9893857-0846e9beed5f78d2.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

各API在每日免费额度用完后，超出部分需要按次数进行额外购买。 自然处理技术产品，采用后付费与预付费两种方式：

1. 按量后付费 对您实际产生的计费调用量按固定单价进行计费结算，系统每小时从您的百度云账户中扣除对应的消费额。

产品服务 | 按量结算付费 |  QPS限制
-|-|-
情感倾向分析	 | 0.0025元/次 | 20 |

2. 预付费次数包 您可根据业务量评估，提前一次性付费购买对应规格的次数包，在有效期内产生计费的调用量优先使用次数包抵扣，所有有效次数包抵扣完毕后再自动转为按量后付费方式。（次数包规格越大，单价越低）

产品服务 | QPS限制 | 有效期|价格|享有对应次数包规格的产品列表
-|-|-|-|-
10万次|	20|	一年|	230元|	文本纠错、情感倾向分析、评论观点抽取、对话情绪识别|
30万次|	20|	一年|	630元|	文本纠错、情感倾向分析、评论观点抽取、对话情绪识别|
50万次|	20|	一年|	950元|	文本纠错、情感倾向分析、评论观点抽取、对话情绪识别|
100万次|	20|	一年|	1700元|	文本纠错、情感倾向分析、评论观点抽取、对话情绪识别|
300万次|	20|	一年|	4500元|	文本纠错、情感倾向分析、评论观点抽取、对话情绪识别|
10万次|	20|	一年|	280元|	词法分析定制、评论观点抽取定制、情感倾向分析定制|
30万次|	20|	一年|	780元|	词法分析定制、评论观点抽取定制、情感倾向分析定制|
50万次|	20|	一年|	1200元|	词法分析定制、评论观点抽取定制、情感倾向分析定制|
100万次|	20|	一年|	2200元|	词法分析定制、评论观点抽取定制、情感倾向分析定制|
300万次|	20|	一年|	6000元|	词法分析定制、评论观点抽取定制、情感倾向分析定制|

##### 2. Face++人脸识别API
1. 按量计费
提前充值账户，按实际调用量即时扣费。使用多少，支付多少。收费项包括API调用和API调用失败。

API | 调用费用（元／次）|  QPS限制
-|-|-
人脸检测	 | 0.001元/次 | 20 |
人脸分析   | 0.001元/次 | 20 |

2. 包时计费
在包时计费模式下，您可以按月或按天购买指定API组的QPS配额。在付费时段内无限量调用，可灵活指定服务起始时间。

API | 单位|  定价（元／单位）| QPS限制
-|-|-|-
人脸识别	 | 1QPS * 1天 | 100 | 30
人脸识别   | 1QPS * 1月（30天） |1000|30

##### 3. 科大讯飞实时语音转写API
套餐|体验包|	时长套餐|	并发套餐|	
-|-|-|-
价格|	免费|	￥198.00|	￥1180.00|	
时长量|	24小时|	500小时以上|	不限时长|	
支持并发| 1路 |     1路~10路|    1路~10路|
有效期|	30天|	一年|	一年|	
单价|	免费|	6元/小时起|	2万元/路/年|	

## 清单
[API测试代码](https://github.com/guyray/API_ML_AI_final/tree/master/API%E6%B5%8B%E8%AF%95%E4%BB%A3%E7%A0%81)

[测试音频](https://github.com/guyray/API_ML_AI_final/blob/master/API%E6%B5%8B%E8%AF%95%E4%BB%A3%E7%A0%81/demo1.wav)

[原型文档](https://guyray.github.io/API_final_prototype/)
