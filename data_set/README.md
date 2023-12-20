## 该文件夹是用来存放训练数据的目录
### 使用步骤如下：
* （1）在data_set文件夹下创建新文件夹"object_data"

* （2）点击链接下载物品分类数据集 

  https://www.kaggle.com/datasets/jessicali9530/caltech256?rvi=1

* （3）解压数据集到object_data文件夹下

* （4）执行"split_data.py"脚本自动将数据集划分成训练集train和验证集val    

```
├── object_data   
       ├── object_photos（解压的数据集文件夹）  
       ├── train（生成的训练集）  
       └── val（生成的验证集） 
```
