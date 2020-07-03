+++
# Accomplishments widget.
widget = "accomplishments"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 50  # Order that this section will appear.

title = "比赛"
subtitle = ""

# Date format
#   Refer to https://sourcethemes.com/academic/docs/customization/#date-format
date_format = "Jan 2006"

# Accomplishments.
#   Add/remove as many `[[item]]` blocks below as you like.
#   `title`, `organization` and `date_start` are the required parameters.
#   Leave other parameters empty if not required.
#   Begin/end multi-line descriptions with 3 quotes `"""`.

[[item]]
  organization = "CCF"
  organization_url = "https://www.datafountain.cn/competitions/354"
  title = "视频版权检测   全国总决赛第五"
  url = "https://www.datafountain.cn/competitions/354"
  date_start = "2019-09-01"
  date_end = ""
  description = """
  * 1 完成了 query 视频和 refer 视频等对应
  * 2 对视频进行关键帧提取并进行正则化
  * 3 对训练集中的样本进行分析，找到部分参数的先验数据
  * 4 找到关键帧对应的原始视频进行相似度匹配和 ORB 匹配二次筛选
  * 5 达到了了 F1-score 86 训练集上对应的准确率到达 90%"""
             


[[item]]
  organization = "kaggle"
  organization_url = "https://www.kaggle.com/c/global-wheat-detection"
  title = "全球小麦检测  TOP2%"
  date_start = "2020-05-01"
  date_end = ""
  url = "https://www.kaggle.com/c/global-wheat-detection"
  description = """
  * 1 引入mixup，cutout，cutmix等数据增强方法增大无偏样本量
  * 2 使用pix2pix的方法，对图像进行二次着色解决因颜色差异无法区分的问题
  * 3 使用伪标签的数据，制作有偏数据并深度调參，控制阈值和插入比例，防止模型过拟合
  * 4 对输出结果在测试时做测试时增强（TTA）在训练的时候使用标签平滑减少过拟合
  * 5 针对错误样本进行分析，制定优化目标和可行方案
  """
  

+++
