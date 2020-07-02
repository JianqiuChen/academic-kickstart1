---
# Display name
title: 陈建秋

# Username (this should match the folder name)
authors:
- admin

# Is this the primary user of the site?
superuser: true

# Role/position
role: 计算机视觉方向研究生

# Organizations/Affiliations
organizations:
- name: Uiversity of New South of Wales
  url: ""

# Short bio (displayed in user profile at end of posts)


# Social/Academic Networking
# For available icons, see: https://sourcethemes.com/academic/docs/page-builder/#icons
#   For an email link, use "fas" icon pack, "envelope" icon, and a link in the
#   form "mailto:your-email@example.com" or "#contact" for contact widget.
social:
- icon: envelope
  icon_pack: fas
  link: '#contact'  # For a direct email link, use "mailto:test@example.org".
- icon: comments
  icon_pack: fas
  link: https://blog.csdn.net/JianqiuChen
- icon: github
  icon_pack: fab
  link: https://github.com/JianqiuChen
# Link to a PDF of your resume/CV from the About widget.
# To enable, copy your resume/CV to `static/files/cv.pdf` and uncomment the lines below.
- icon: cv
  icon_pack: ai
  link: files/陈建秋-新南威尔士大学-2021提前批.pdf

bio: My research interests include distributed robotics, mobile computing and programmable matter.

interests:
- Computer Vision
- Feature representation and fusion
- fine-Grained Visual Categorization

education:
  courses:
  - course: 硕士-人工智能 
    institution: Uiversity of New South of Wales
    year: 2021
  - course: 本科-软件工程
    institution: 新疆大学
    year: 2014
# Enter email to display Gravatar (if Gravatar enabled in Config)
email: "ericchenjianqiu@gmail.com"

# Organizational groups that you belong to (for People widget)
#   Set this to `[]` or comment out if you are not using People widget.
user_groups:
- Researchers
- Visitors
---

你好哇:)我是陈建秋，目前就读于澳洲的新南威尔士大学人工智能专业。主要兴趣方向是计算机视觉并做好以此方向长期奋斗的准备

我做过什么：
  1. 细粒度下的可区分特征研究：
     主要工作是对特征表达方式做了进一步的优化，采取了不共享的网络结构提取互补特征
     实验对比了多种定位方法，根据不同定位方法的“性格”用于各个特征提取的阶段
     采取了类激活图指导定位兴趣区域，完成了弱监督下的细粒度分类任务
     对融合方法进行改进并引入ranking loss指导模型的收敛
     在多个数据集上（stanford car，FGVC-aircraft）精度超过了同类模型
  2. 目标检测：
     在目标检测方向主要的成果主要集中于小麦检测的比赛
     针对比赛的训练样本不足，我做了以下工作
     1. 引入mixup，cutout等数据增强方法增大无偏样本量
     2. 使用伪标签的数据，制作有偏数据并深度调參，控制阈值和插入比例，防止模型过拟合
     3. 对输出结果在测试时做测试时增强（TTA）在训练的时候使用标签平滑减少过拟合
  3. 语义分割及3D建图：
     在货仓场景下基于小车摄像头做2D语义分割，并配合组内同事完成3D建图的映射工作
     主要成果：
     在很少量标注数据的情况下完成了语义分割模型的建立并达到MIOU 0.82的效果
     1. 基于场景特性做迁移学习，对数据进行扩充和增强并解决样本不平衡问题
     2. 基于ROS小车二次开发部分功能，并实现视频流和里程计对应
     3. 对已经完成的语义分割模型进行API化，并将预处理工作成功封装在FLASK服务中
     4. 配合组内同事完成3D语义分割建图的工作
  4. 传统视觉方法下的兴趣区域定位研究：
     主要针对车辆正面角度的图片中的兴趣区域进行定位和识别
     1. 对图片进行边缘检测
     2. 对车牌可能所在区域进行对称区域查找
     3. 根据先验分析得到不同类型车牌和车的大致比例进行映射
     4. 使用PCA-Net和SVM进行预测
  
     
     
