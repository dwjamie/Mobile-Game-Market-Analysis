# MobileGameMarketAnalysis

#### 1、研究简介：

基于自己爬取的TapTap平台手游数据，分析了手游受众和评价的影响因素，从中发现有价值的用户关注点，以期为手游市场的发展提供一些建议。

#### 2、数据介绍

##### a. 数据简介：

主要包括11列直接爬取获得的属性：游戏名称、总评分、总评论数、厂商、类别、标签、简介、评论id、评论用户、评论内容、评论星级；

以及2列数据预处理后得到的compre（评论预处理结果）和intropre（简介预处理结果）。

##### b. 数据获取：

###### 环境依赖：

python 3，jupyter notebook

###### 运行方式：

在jupyter notebook中打开‘TapTap爬虫.ipynb’文件，直接运行。（如遇到包的缺失，请在anaconda prompt中使用pip install ’package_name‘安装）

运行后将爬取相关数据，并进行预处理。文件将保存在当前目录的'taptap'文件夹下。

#### 3、数据展示与分析：

所有研究中使用的相关R语言代码已经整合为了一个rmd文件，并knit为一个html。

##### Rmd运行：

###### 环境依赖：

R 3.6.3，Rstudio

###### 运行方式：

确保相关文件（停用词表、数据集等）放置到默认目录下，数据集需要移出'taptap'文件夹。

在Rstudio中打开 '数据分析报告.Rmd'，即可根据需要按照顺序运行。如有包缺失，请使用install.packages('package_name')安装。

#### 4、目录结构描述：

|—README.md

|—stopwords.dat

|—stopwordslist.csv
|—tags.csv

|—taptap_data.xls

|—TapTap爬虫.ipynb

|—展示PPT.pptx

|—数据分析报告.html

|—数据分析报告.Rmd 
