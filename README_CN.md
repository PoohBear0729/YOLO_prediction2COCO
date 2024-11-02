# YOLO prediction.json 文件格式转换为COCO 格式.

## 这是一个将YOLO验证的prediction.json文件转换为COCO格式，方便将YOLO的指标转换为COCO指标，因为原本的prediction文件里面的id和COCO的对应不上会有错误，也就是你的图片文件名不是数字，是字符串的时候会报错。

# 使用

## 将pred_json_path更改为你的YOLO验证得到的prediction. json文件的路径

## 将annotation_json_path更改为coco的标签json文件的路径。

## Output_file是修改的json文件要保存的路径
