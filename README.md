# LabProject
# 实验室项目，判断粪便的颜色和固液体。
# 使用RGB空间转HSV空间，得到H\S\V三个分量之后判断颜色（注：cvtcolor之后通道0\1\2分别是H\S\V通道）。
# 固体液体的判断使用SVM+HOG训练之后测试实现（使用Matlab验证之后转openCV + C++）。
