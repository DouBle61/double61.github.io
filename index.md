---
layout: home
title: Home
---

<!-- 语言切换按钮（固定右上角，不挡内容） -->
<div style="position: fixed; top: 20px; right: 20px; z-index: 100; background: rgba(255,255,255,0.9); padding: 10px; border-radius: 8px; box-shadow: 0 2px 10px rgba(0,0,0,0.1);">
  <button onclick="switchLang('zh')" style="font-size: 16px; padding: 8px 16px; margin: 0 5px; cursor: pointer; border: 1px solid #ccc; border-radius: 4px; background: #f0f0f0;">中文</button>
  <button onclick="switchLang('en')" style="font-size: 16px; padding: 8px 16px; margin: 0 5px; cursor: pointer; border: 1px solid #ccc; border-radius: 4px; background: #f0f0f0;">English</button>
</div>

<!-- 中文内容（默认显示，用标准 Markdown 写） -->
<div id="zh-content">

<img style="float:right; padding-left:20px; padding-bottom:20px;" src="https://avatars.githubusercontent.com/u/260212410?v=4" width="220" alt="头像">

# 你的名字（中文）

我是中文内容示例（这里写你的自我介绍）

我持有中国传媒大学文学与艺术双学士学位，专业排名第1，获国家奖学金。

## 代表作品

- **体育：运动与生命的共鸣 | 主创**  
  成都2021世界大学生夏季运动会赛前展映作品（2023）。  
  获2025年北京市广播电视局优秀广播电视公益广告专项资金支持。  
  入选国家广播电视总局优秀公益广告作品库。  
  在“学习强国”平台及北京-内蒙古对口帮扶城市地方电视台播出。

- **湾区全运会，好运全城 | 主创**  
  第十五届全运会（粤港澳，2025）赛前展映作品。  
  广东省广播电视局2025年重大主题公益广告扶持项目。  
  入选国家市场监管总局“十八大以来优秀公益广告展播”。  
  在中央级媒体及“时说新语”平台播出。

- **北京漫步 | 项目负责人**  
  获北京中轴线保护基金会表彰。  
  北京市文化艺术基金2023传播交流项目资助。  
  国家级大学生创新创业训练计划结项“好”。  
  博雅品牌研究院年度学术创新项目“优秀”。  
  中国大学生广告节学院奖入围。  
  为北京西城区、大兴区、天津河西区等提供服务。

- **原创粉的春天 | 主创**  
  2023浙江卫视综艺共创论坛冠军。  
  导师：著名综艺导演岑俊义。  
  第31、32届北京大学生电影节国产原创单元初选评委。

- **实习经历**  
  中国传媒大学70周年视觉识别系统（VIS）设计。  
  第十四届全国冬季运动会（2024）IP及衍生品开发。  
  央视2025春晚视觉设计。  
  北京2022冬奥会赛时志愿服务及赛后遗产转化研究。  
  界面新闻·财新（CBN）：上海联合媒体集团界面新闻及SMG财新科技体育 desk 记者。

- **社会实践**  
  连续四年参与三地暑期支教。  
  获首都大学生社会实践（青春兴国）“优秀团队”。  
  获“全国优秀大学生志愿者”“先进个人”（2022）。  
  事迹被中国青年报报道并被共青团中央转发。  
  受邀作为学生代表赴人民大会堂参加“时代楷模”报告会。

</div>

<!-- 英文内容（默认隐藏，用标准 Markdown 写） -->
<div id="en-content" style="display: none;">

<img style="float:right; padding-left:20px; padding-bottom:20px;" src="https://avatars.githubusercontent.com/u/260212410?v=4" width="220" alt="Avatar">

# Your Name

I am currently an M.S./Ph.D. student in Science Communication at UCAS.  
My research focuses on interstellar sci-fi and Large Language Models.

I hold a double Bachelor's degree in Literature and Arts from Communication University of China (CUC), ranking 1st in major and awarded National Scholarship.

## Selected Work

- **Sports: The Resonance of Movement and Life | Lead Creator**  
  Pre-game screening for Chengdu 2021 FISU Games (2023).  
  Supported by 2025 Beijing Radio & TV Public Service Ad Fund.  
  Selected into NRTA Excellent PSA Library.  
  Broadcast on "Xuexi Qiangguo" and local TV stations.

- **National Games in the Bay Area, Good Luck to the Whole City | Lead Creator**  
  Pre-game screening for 15th National Games (2025).  
  Supported by Guangdong Radio & TV Major Theme PSA Project.  
  Selected for SAMR Excellent PSA Exhibition.  
  Broadcast on central media and "Shi Shuo Xin Yu".

- **Beijing Walk | Project Lead**  
  Commended by Beijing Central Axis Protection Foundation.  
  Funded by Beijing Culture and Arts Fund (2023).  
  National Undergraduate Innovation Program rated "Good".  
  Boya Institute annual project "Excellent".  
  Finalist in Academy Award of Chinese University Students Advertising Festival.  
  Served Xicheng, Daxing (Beijing), Hexi (Tianjin), etc.

- **The Spring of Original Work Fans | Lead Creator**  
  Champion of 2023 Zhejiang TV Variety Co-Creation Forum.  
  Mentored by director Cen Junyi.  
  Judge for 31st/32nd Beijing Student Film Festival Domestic Original Unit.

- **Internship**  
  CUC 70th Anniversary VIS design.  
  14th National Winter Games IP & derivatives.  
  CCTV 2025 Spring Gala visual design.  
  Beijing 2022 Winter Olympics volunteer & legacy research.  
  Jiemian News & Yicai: Tech/Sports journalist.

- **Social Practice**  
  Four years of summer rural teaching in three locations.  
  Awarded "Excellent Team" for Capital Students Social Practice.  
  Named National Excellent Volunteer (2022).  
  Reported by China Youth Daily, reposted by CYL Central.  
  Invited to Great Hall of the People as student representative.

(last updated: Feb 2025)

</div>

<!-- JS 切换脚本 -->
<script>
function switchLang(lang) {
  if (lang === 'zh') {
    document.getElementById('zh-content').style.display = 'block';
    document.getElementById('en-content').style.display = 'none';
  } else {
    document.getElementById('zh-content').style.display = 'none';
    document.getElementById('en-content').style.display = 'block';
  }
}
</script>

<!-- 内容顶部间距（避开固定按钮） -->
<style>
  #zh-content, #en-content {
    margin-top: 80px;
    max-width: 800px;  /* 可选：限制宽度，更整洁 */
    margin-left: auto;
    margin-right: auto;
    padding: 20px;
  }
</style>
