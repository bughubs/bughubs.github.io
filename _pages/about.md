---
permalink: /
title: "个人简历"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

# **A.** **教育背景**

<table style="border-collapse: collapse;" border="0" cellspacing="0" cellpadding="0">
    <tr>
        <td>2018/09-2022/06</td>
        <td>中南大学(985)</td>
        <td>地球科学与信息物理学院</td>
        <td>理学学士</td>
        <td>地理信息科学</td>
    </tr>
    <tr>
        <td colspan="5">综合排名:4/59</td>
    </tr>
    <tr>
        <td>2022/09-2025/06</td>
        <td>武汉大学(985)</td>
        <td>遥感信息工程学院</td>
        <td>工学硕士(在读)</td>
        <td>摄影测量与遥感</td>
    </tr>
    <tr>
        <td colspan="5">导师：袁强强，苏鑫，张良培大组</td>
    </tr>
</table>


# **B.** **科研成果**

**Ruiyang Sun,** Xin Su*, Qiangqiang Yuan, Hongzan Jiao, Jiang He, Li Zheng. Urban region function classification via fusing optical imagery and social media data: A spatio-temporal Transformer interaction approach. ***Information Fusion.\*** (SCI 一区, IF = 18.6) (在投，二审小修已经提交)

# **C.** **会议经历及获奖荣誉**

| 序号 |                             经历                             |   年度    |
| :--: | :----------------------------------------------------------: | :-------: |
|  1.  | GSCS&ICUI2023全球智慧城市峰会暨第三届国际城市信息国际会议 英文口头汇报 |   2023    |
|  2.  |     “南方测绘杯”第十二届全国大学生测绘科技论文竞赛特等奖     |   2021    |
|  3.  |              全国第六届大学生艺术展演一等奖2021              |   2021    |
|  4.  |                  优秀学生、学业奖学金多次。                  | 2018-2022 |

# **D.** **研究经历**

|                           研究课题                           |                          阶段性成果                          |    时间     |
| :----------------------------------------------------------: | :----------------------------------------------------------: | :---------: |
| 基于光学图像和社交媒体数据融合面向城市功能区分类的时空Transformer交互方法 | Information Fusion二审小修 <br> GSCS&ICUI2023国际会议英文口头汇报 | 2022/06至今 |
|              空间演化社团探测的进化蚁群优化方法              |               全国大学生测绘科技论文竞赛特等奖               |    2021     |
|              新冠肺炎疫情流行特征及时空演变分析              |                    省级大学生创新训练项目                    |    2020     |


<!-- 
<table>
    <tr>
        <td>基于光学图像和社交媒体数据融合面向城市功能区分类的时空Transformer交互方法</td>
        <td>Information Fusion二审小修，在GSCS&ICUI2023国际会议做英文口头汇报</td>
        <td>2022/06至今</td>
    </tr>
    <tr>
        <td>空间演化社团探测的进化蚁群优化方法</td>
        <td>全国大学生测绘科技论文竞赛特等奖</td>
        <td>2021</td>
    </tr>
    <tr>
        <td>新冠肺炎疫情流行特征及时空演变分析</td>
        <td>省级大学生创新训练项目</td>
        <td>2020</td>
    </tr>
</table> -->

# **E.** **研究兴趣**

◆ 异构多模态数据融合（图像与时序数据、图像与文本数据）

◆ 时序社交数据  

◆ 遥感、街景图像

◆ 深度学习算法  

◆ 多模态大模型

# **F.** **个人兴趣特长**

曾有7年的学校交响乐团小提琴及中提琴演奏经历。高中时以小提琴手身份随兰州一中高中交响乐团访问德国演出，获得中德文化艺术交流年金奖，大学时曾先后在中南大学梅溪湖新春音乐会等重大演出中担任中提琴手，获湖南省第六届大学生艺术展演一等奖、全国第六届大学生艺术展演一等奖。

# **G.** **文献笔记**

{% include base_path %}
{% for post in site.posts %}
  {% capture year %}{{ post.date | date: '%Y' }}{% endcapture %}
  {% if year != written_year %}
    {% capture written_year %}{{ year }}{% endcapture %}
  {% endif %}
  {% include archive-single.html %}
{% endfor %}
