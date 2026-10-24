# 基于大模型的校园智能问答系统的设计与实现

北京工业大学耿丹学院 2027 届本科毕业设计（论文）LaTeX 源码与 PDF 文稿。

仓库地址：<https://github.com/Mrxy-liu/campus-qa-thesis>

| 项目 | 内容 |
|---|---|
| 学生 | 刘奇 |
| 学号 | 230809215 |
| 班级 | 计科 23-2 班 |
| 专业 | 计算机科学与技术 |
| 二级学院 | 信息工程学院 |
| 指导教师 | 段雪丽 |

## 文档结构

- 封面
- 诚信承诺（含电子签名）
- 中文摘要、关键词
- Abstract、Research Area、Key Words
- 目录
- 第 1 章 绪论
- 第 2 章 相关技术与理论基础
- 第 3 章 系统需求分析
- 第 4 章 系统设计
- 第 5 章 系统实现
- 第 6 章 系统测试与效果评价
- 结论
- 参考文献（26 条，中文 20 条、外文 6 条）
- 致谢

正文含 8 幅 TikZ 图、11 张表、8 个编号公式，图表公式和章节均在正文中有交叉引用。

## 编译

需要安装 XeLaTeX 与 `ctex` 宏包，并具备宋体、黑体、楷体、Times New Roman 字体。在项目根目录执行：

```powershell
xelatex main.tex
xelatex main.tex
```

或者：

```powershell
latexmk -xelatex main.tex
```

生成文件为 `main.pdf`。目录中的 `main.pdf` 是已编译版本，可直接查看。

## 目录说明

```text
main.tex                 LaTeX 主文件（页面、样式、封面、摘要、目录）
chapters/ch1.tex         第 1 章 绪论
chapters/ch2.tex         第 2 章 相关技术与理论基础
chapters/ch3.tex         第 3 章 系统需求分析
chapters/ch4.tex         第 4 章 系统设计
chapters/ch5.tex         第 5 章 系统实现
chapters/ch6.tex         第 6 章 系统测试与效果评价
chapters/conclusion.tex  结论
chapters/references.tex  参考文献
chapters/acknowledgements.tex 致谢
figures/signature.png    诚信承诺电子签名
main.pdf                 编译后的论文 PDF
```

## 说明与边界

- 第 1 至第 5 章依据任务书、开题报告和系统设计撰写；第 5 章代码片段用于说明与设计对应的核心实现结构，不是完整工程代码。
- 第 6 章给出测试环境、测试用例、100 题测试集、评价指标和 A/B1/B2/B3 对照实验方案。由于系统联调与完整实验尚在推进，正文没有填写估计值或虚构的实测指标；系统完成后应按表 6-2、表 6-3、表 6-4 的字段补入真实数据。
- 参考文献取自任务书和开题报告提供的文献清单，并按正文首次引用顺序重新编号；正式提交前建议再核对一遍卷期、页码和 DOI。
- 本仓库用于课程作业与论文排版，不代表已经完成系统联调和最终答辩版本。
