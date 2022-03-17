# Cloud-Detection-Tool
a simple command tool to mask cloud in image!
- download URL：
- https://pan.baidu.com/s/1i4OU675fM1Sjwn104hl-PQ code: j5yu 

# 输入参数说明

```python
--area_remove：面积过滤参数，当检测出的云像素个数少于该值时，将自动删除，默认为10000，即100*100像素大小的物体
--blocksize：分块大小，根据显存大小来定，RTX3090，默认为4096
--ImgFilePath：输入的栅格路径
--saveRasterpath：输出的云检测路径
--GPUid：指定那个GPU来运算
```

#　引用说明

