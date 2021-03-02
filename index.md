---
layout: home
permalink: /

title: "NEDO ROBO-MARC"
excerpt: "NEDO ROBO-MARC (Robot Platformization) Project Web page"
#action: true
#action_btn:
#  - label: "Download"
#    fa_icon : "fas fa-download"
#    class: "btn btn-lg btn-success"
#    url: "https://github.com/manid2/lone-wolf-theme/releases/latest"
#  - dropdown: false
#  - dropdown_items:
#    - label: "v1.0.2"
#      url: "https://github.com/manid2/lone-wolf-theme/releases/tag/v1.0.2"
#      fa_icon: "fas fa-arrow-down"

feature_rows:
  - title: "Overview"
    excerpt: "Overview of the Project"
    url: "/project_overview/"
    img_path: "feature_rows/nedo-06.png"
    img_alt: "Overview of the Project"
  - title: "ROS NEWS"
    excerpt: "ROSおよびRTM関係のNEWS"
    url: "/rosnews/"
    img_path: "feature_rows/rosnews.png"
    img_alt: "ROS News"
  - title: "symposium2021"
    excerpt: "Symposium 2021"
    url: "/symposium2021/"
    img_path: "feature_rows/sympo2021.png"
    img_alt: "Symposium 2021"
  - title: "News"
    excerpt: "Nedo Project News"
    url: "/newslist/"
    img_path: "feature_rows/news.png"
    img_alt: "News"


---

## NEDO特別講座

NEDO特別講座 (2020-2022年度) および、そのコアプロジェクト (NEDO ロボット活用型市場化適用技術開発プロジェクト (2017-2019年度) ) のページです。

This is Web page to publish R&D result by “NEDO’s Technology Development Project for Robot Commercialization Applications” (FY2017-2019) and “NEDO Course (NEDO Kouza)”.

### NEDO News

<div align="center"><img src="{{site.baseurl}}/assets/images/nedo-news-s.png" width="80%"></div>


<section>
  <ul>
 {% for post in site.posts %}
    <li><a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
  </ul>
</section>

