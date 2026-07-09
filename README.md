# Artificial-Experiment

## 📖 仓库简介
本仓库存放机器学习课程所有课堂实验与期末独立大作业，完整覆盖**线性分类、降维聚类、真实场景分类建模**三大模块，所有代码基于 `scikit-learn` 实现，配套官方课件、实验报告文档、数据集与可视化绘图代码，可直接复现全部实验结果。

## 📂 仓库目录结构

### 可视化层级框图
```mermaid
graph TD
    root["Artificial-Experiment/仓库根目录"]
    readme["README.md 说明文档"]
    
    exp1["机器学习实验1<br/>线性分类实验"]
    exp1_code["实验代码.ipynb"]
    exp1_report["实验报告.docx"]
    exp1_pdf["配套课件PDF"]

    exp2["机器学习实验2<br/>降维聚类实验"]
    exp2_code["实验代码.ipynb"]
    exp2_report["实验报告.docx"]
    exp2_pdf["配套课件PDF"]

    final["期末大作业<br/>食堂选择预测建模"]
    final_task["大作业任务书"]
    final_code["完整建模代码"]
    final_data["模拟数据集.csv"]
    final_img["输出图表文件夹"]
    final_report["期末完整报告"]

    root --> readme
    root --> exp1
    root --> exp2
    root --> final

    exp1 --> exp1_code
    exp1 --> exp1_report
    exp1 --> exp1_pdf

    exp2 --> exp2_code
    exp2 --> exp2_report
    exp2 --> exp2_pdf

    final --> final_task
    final --> final_code
    final --> final_data
    final --> final_img
    final --> final_report
