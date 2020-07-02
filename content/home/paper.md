+++
# Accomplishments widget.
widget = "accomplishments"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 50  # Order that this section will appear.

title = "科研经历"
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
  organization = "ICBAIE 2020 （IEEE-CS conference）"
  organization_url = ""
  title = "Weakly Supervised Learning of Discriminative Features for Fine-Grained Visual Categorization"
  url = "http://www.icbaie2020.com/"
  date_start = "2020-03-01"
  date_end = ""
  description = """
  * 1 对特征表达方式做了进一步的优化，采取了不共享的网络结构提取互补特征
  * 2 实验对比了多种定位方法，根据不同定位方法的“性格”用于各个特征提取的阶段
  * 3 采取了类激活图指导定位兴趣区域
  * 4 对融合方法进行改进并引入ranking loss指导模型的收敛
  * 5 在多个数据集上（stanford car，FGVC-aircraft）精度超过了同类模型"""
             


[[item]]
  organization = "CISCE2020 （IEEE-CS conference）"
  organization_url = "http://www.iccisce2020.org/"
  title = "Vehicle Brand Classification Method Based on PCA-NET Under Complex Background"
  date_start = "2020-01-01"
  date_end = ""
  url = "http://www.iccisce2020.org/"
  description = """
  * 1. 对图片进行边缘检测
  * 2. 对车牌可能所在区域进行对称区域查找
  * 3. 根据先验分析得到不同类型车牌和车的大致比例进行映射
  * 4. 使用PCA-Net和SVM进行预测
  """
  

+++
