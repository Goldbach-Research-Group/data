data
========
可用于提取特征的原始数据，answer为问题的回答数据，follower为题主的关注数据

## 12.30
* answer: 可以在[此文件](https://github.com/Goldbach-Research-Group/data/blob/master/12.30/answer/306537777.txt)预览
* follower: 可以在[此文件](https://github.com/Goldbach-Research-Group/data/blob/master/12.30/follower/shi-kong-23-21.txt)预览

* getData：包含截至2018 12 30 17 30 的所有回答（共1878个）以及评论、子评论。
回答放在answers文件夹下，一个回答一个Json文件，按默认排序从0开始命名
评论放在comments文件夹下，对应回答命名的文件夹内，包含精选评论（精选评论从0开始，可能与后面的评论重复）
子评论放在child_comments文件夹下，对应命名的文件夹内。
若没有评论或子评论，不会创建对应文件夹。
极少数会出现评论内容乱码和评论抓取不全的情况。
