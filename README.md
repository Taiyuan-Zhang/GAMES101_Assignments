# GAMES101_Assignments
repo for the assignments of GAMES101: 现代计算机图形学入门 by 闫令琪

# Assignment1: Roatation and Projection
**全部实现**
- 正确构建模型矩阵。
- 正确构建透视投影矩阵。
- 代码可以在现有框架下正确运行，并能看到变换后的三角形。
- 当按 A 键与 D 键时，三角形能正确旋转。或者正确使用命令行得
到旋转结果图像。
- [提高项]在 main.cpp 中构造一个函数，该函数的作用是得到绕任意
过原点的轴的旋转变换矩阵。
Eigen::Matrix4f get_rotation(Vector3f axis, float angle)

**注：**
提高项的axis在main.cpp中直接进行了定义，初始化为 {0,0,1}，注释头为Bonus by Taiyuan-Zhang