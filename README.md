📖 Introduction

Regional Case Writer is a specialized AI skill designed for educational informationization enterprises and regional teaching research teams. It transforms fragmented frontline materials into professional, standardized case studies that meet academic and publication standards.
Core Problem

Regional teaching research teams often face challenges:

❌ Fragmented, disorganized materials from schools
❌ Difficulty identifying application highlights
❌ Time-consuming case writing process
❌ Inconsistent quality and format
❌ Need for both detailed and presentation-ready versions
Our Solution

A comprehensive four-step workflow that automates:

Highlight Discovery - Systematically extract value points from raw materials
Pattern Extraction - Build application frameworks with visual diagrams
Case Writing - Generate professional academic content with polish
Dual-Version Output - Standard case (4000 words) + Presentation-ready version (1500-2000 words)

✨ Features
🎯 Intelligent Highlight Extraction

Three-step standardized workflow
Cross-reference with 8 core product modules
Map to theoretical frameworks (7 case types)
Ensure evidence-based claims
📊 Visual Pattern Extraction

Auto-generate application framework diagrams
Support multiple diagram types (flowcharts, architecture diagrams, etc.)
Professional visual representation of implementation models
Export-ready high-quality images
✍️ Professional Case Writing

Academic-standard writing style
Integrated with advanced writing tools (claude-scientific-writer-main)
GB/T 7714-2015 reference formatting
Structured, logical flow
📄 Dual-Version Output

Standard Version (4000 words)

Complete, detailed case study
Suitable for publication and documentation
Comprehensive problem analysis and solution details

Compressed Version (1500-2000 words)

Presentation-ready format
Core content: Problem → Actions → Results → Value
Easy to adapt for PPT materials
📚 Rich Reference Library

7 WeChat article case studies analyzed
9 PDF reference cases (various types)
Writing templates for different scenarios
Prohibited and recommended writing practices
Product feature mapping table (8 products)

🚀 Installation
Prerequisites

Coze platform account
Required skills:
draw-v1.1.0 (for diagram generation)
claude-scientific-writer-main (for academic polishing)
docx (for Word document output)
Install Skill

# Download skill package
wget https:https://github.com/yannkun/educase-writer

# Install in Coze platform
# 1. Navigate to Skills → Create Skill
# 2. Upload the .tar.gz file
# 3. Configure skill parameters
Quick Start

Upload Materials: Provide fragmented teaching materials, product usage data, or initial notes
Define Case Type: Select from 7 predefined case types (teaching model, technology application, etc.)
Specify Output Format: Choose standard/compressed or both versions
Generate: Let the skill handle the complete workflow automatically

📝 Usage
Input Requirements

Supported Input Formats:

Text documents (.txt, .md)
Word documents (.docx)
Excel files (.xlsx, .xls)
PDF files (.pdf)
WeChat article links

Minimum Information Needed:

School/region basic information
Implementation context
Product usage scenarios
Available data or results
Output Format

File Structure:

output/
├── [Case Name]_Standard_Version.docx    # 4000 words detailed case
└── [Case Name]_Compressed_Version.docx   # 1500-2000 words for PPT

Standard Version Sections:

Title (Main + Subtitle)
Abstract
Background & Problem Analysis
Theoretical Framework
Implementation Actions
Results & Impact
Innovation Highlights
References

Compressed Version Sections:

Title
Core Problem
Key Actions
Main Results
Replicable Value
Example Prompt

Please write an educational informationization case based on these materials:

Context: Smart classroom implementation in X School, focusing on AI-assisted teaching
Products: AI teaching assistant, smart homework system
Goal: Demonstrate how AI technology improves teaching efficiency

Requirements:
- Case type: Technology Application
- Output both standard and compressed versions
- Use theoretical framework: TPCK

🏗️ Architecture

┌─────────────────────────────────────────────────────────┐
│                    Regional Case Writer                 │
│                       v1.2.0                            │
└─────────────────────┬───────────────────────────────────┘
                      │
        ┌─────────────┴─────────────┐
        │                           │
   Input Processing          Reference Library
        │                           │
        ├─ Material Analysis      ├─ 7 Case Types Mapping
        ├─ Highlight Discovery    ├─ 8 Products Features
        └─ Context Extraction     ├─ Writing Templates
                                    └─ Prohibited Practices
        │
        ↓
┌─────────────────────────────────────────┐
│      Four-Step Workflow Engine         │
├─────────────────────────────────────────┤
│  Step 1: Highlight Discovery            │
│  ├─ Standardized extraction workflow   │
│  └─ Value point identification          │
│                                         │
│  Step 2: Pattern Extraction              │
│  ├─ Call draw-v1.1.0 skill             │
│  ├─ Generate framework diagrams         │
│  └─ Visual representation               │
│                                         │
│  Step 3: Case Writing                    │
│  ├─ Structure generation                │
│  ├─ Content expansion                  │
│  └─ Call claude-scientific-writer-main │
│     for academic polishing              │
│                                         │
│  Step 4: Dual-Version Output             │
│  ├─ Standard version (4000 words)      │
│  ├─ Compressed version (1500-2000 words)│
│  └─ Call docx skill for formatting     │
└─────────────────────────────────────────┘
                      │
                      ↓
              ┌──────────────┐
              │   Output     │
              │   Files      │
              └──────────────┘

📊 Supported Case Types

Type	Description	Theoretical Framework
Teaching Model	Instructional methodology innovation	TPACK, Constructivism
Technology Application	Digital tools integration	TAM, SAMR
Performance Improvement	Academic outcomes enhancement	Data-driven Decision Making
Case Analysis	Lesson study and optimization	Classroom Observation Protocol
Teaching Mode	Pedagogical pattern exploration	Bloom's Taxonomy
Workload Reduction	Efficiency improvement strategies	Time Management Theory
Regional Governance	School/district transformation	Systems Theory

🎓 Writing Standards
Academic Integrity

✅ Data source tracing
✅ Evidence-based claims
✅ No fabricated information
✅ GB/T 7714-2015 reference format
Writing Style

✅ Natural language, avoid AI-generated patterns
✅ Clear, concise expression
✅ Logical structure
✅ Professional terminology
Format Requirements

✅ Main title + Subtitle (complete sentences)
✅ Architecture diagram first, then text
✅ Sharp problem description
✅ Actionable, specific solutions
✅ Quantifiable results

📚 Reference Resources
Included References

WeChat Articles (7 cases):

Digital technology empowerment for teaching quality improvement
S2C digital education transformation for regional development
AI autonomous learning under "Double Reduction" policy
Smart classroom construction guided by literacy development
AI-integrated interdisciplinary practical activities
COP big data analysis for classroom question design
Evidence-based classroom teaching behavior evaluation

PDF Cases (9 cases):

STEAM+ ecological engineering interdisciplinary practice
Primary school digital transformation "Four-in-One" pathway
AI-integrated curriculum implementation
Labor education construction under five domains integration
Integrated implementation of ideological and political education
"Efficiency Classroom" practice driving teaching ecosystem change
Grid-based mental health protection system
Science and technology education practice for universal innovation
Templates and Guidelines

Case writing templates (teaching model & technology application)
Writing norms (language, argumentation, structure)
Format templates for standard cases
Case index and categorization

🔄 Version History
v1.2.0 (Current Release)

✨ Added 7 WeChat article case studies
✨ Added 9 PDF reference cases
✨ Created优秀案例分析.md (Excellent Case Analysis)
✨ Integrated writing templates and prohibited practices
📦 Package size: 28KB
v1.1.0

✨ Added highlight discovery methodology
✨ Added product feature information (8 core products)
✨ Enhanced theoretical framework mapping
📦 Package size: 23KB
v1.0.0 (Initial Release)

🎉 Basic four-step workflow
📦 Standard case writing capability
📦 Package size: 14KB

🤝 Contributing

Contributions are welcome! Please follow these guidelines:

Fork the repository
Create a feature branch
Make your changes
Submit a pull request
Suggested Contributions

Add more reference case studies
Improve theoretical framework mappings
Enhance writing templates
Add support for additional output formats

📄 License

MIT License - see LICENSE for details

👥 Team

Developed by: Educational Informationization Research Team


🌟 Star History

<img alt="Star History Chart" src="https://api.star-history.com/svg?repos=yourusername/regional-case-writer&type=Date">

<div align="center">

If you find this skill helpful, please consider giving it a ⭐️ star!



</div>

中文文档
项目简介

Regional Case Writer 是一个专门为教育信息化企业和区域教研团队设计的AI技能。它能将一线教研提供的零散材料，转化为高质量、标准化的教育信息化案例。
核心功能

智能亮点挖掘 - 三步标准化流程，从零散材料中提炼应用亮点
模式提炼 - 自动生成应用框架图，直观展示实施模式
专业撰写 - 符合学术标准的案例写作，自动润色
双版本输出 - 标准版（4000字）+ 压缩版（1500-2000字，PPT专用）
适用场景

区域教研团队撰写成功案例
教育信息化企业展示应用效果
学校数字化转型的经验总结
教育主管部门的经验推广
快速开始

上传一线材料（文本、Word、Excel、PDF或微信文章链接）
选择案例类型（7种预设类型）
指定输出格式（标准版/压缩版/双版本）
等待生成
更新日志

v1.2.0（当前版本）

新增7篇微信文章案例分析
新增9篇PDF参考案例
优化写作模板和规范
技能包大小：28KB

<div align="center">

Made for educational innovation · 专为教育创新而设计

</div>
