# 📣 技术文档之总结说明
* [代码GitHub的URL](https://github.com/aqiangwansui/python_final_test/tree/master/the_code_of_python_final_test)
* [pythonanywhere URL](http://aqiangwansui.pythonanywhere.com/)

***
### ⛏ 页面的介绍
我们小组网站目前有七个页面，分别是教师工资的页面、北京与新疆教育经费支出对比、城镇平均工资水平、2018年城镇工资各省对比、2017年及2018年教师工资情况变化、2018年教师工资水平各省对比、总结的页面。
1. 教师工资的页面展示了2014年到2018年教师人数的变化，使用了条形图和表格展示。[教师工资的页面](http://aqiangwansui.pythonanywhere.com/)
2. 北京与新疆教育经费支出对比的页面展示了2009-2017年的经费支出对比（缺少了2012及2018的）。[北京与新疆教育经费支出对比](http://aqiangwansui.pythonanywhere.com/animation)
3. 城镇平均工资水平的页面展示了2014年-2018年城镇平均工资水平，使用了地图和表格展示。[城镇平均工资水平](http://mm3337858677.pythonanywhere.com/salary)
4. 2017年及2018年教师工资情况变化的页面展示了2017-2018教师工资情况变化，使用了折线图和表格展示。[2017年及2018年教师工资情况变化](http://aqiangwansui.pythonanywhere.com/scatter)
5. 2018年城镇工资各省对比的页面使用**文字云**展示了2018年城镇工资各省对比。[2018年城镇工资各省对比](http://aqiangwansui.pythonanywhere.com/diamond)
6. 2018年教师工资水平各省对比的页面使用**文字云**展示了2018年教师工资水平各省对比。[2018年教师工资水平各省对比](http://aqiangwansui.pythonanywhere.com/wordcloud)
7. 总结页面主要总结数据可视化的内容，得出最终的结论。[总结](http://aqiangwansui.pythonanywhere.com/user)

***
### 😉 团队的分工
我主要负责HTML文档的书写和数据传递。小伙伴（黄泓元）负责了设计flask的嵌套，实现数据的python——>HTML页面交互。黄泓元是个很很很非常优秀、非常负责、非常热心肠的小伙伴。

*** 

### HTML档描述
1. 我们小组一共有三个HTML文档。
   * base.html主要负责数据可视化界面的美观。
   * index.html主要使用了jinja2的模板。
   * base2.0.html主要负责总结页面的美观。
### PYTHON档描述
2. 我们小组一共有两个py文档。
   * app.py主要负责页面的跳转和交互功能。
   * salary.py主要负责数据的可视化。
### webapp的动作描述
3. 对于webapp的动作描述。
   * 在顶部导航栏设置了超链接，只要点击就可以跳转到想要的界面。
   * 在前六个页面设置了下拉选择框。
### 数据传递描述
* 数据传递的部分是**我负责的**，做出来的不太符合要求。只能说有这个动作。所以我没有把这部分的代码放上来，只是把他部署在pythonanywhere上面了。




