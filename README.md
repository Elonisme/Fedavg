# README
## 步骤
1. 加载数据
2. 采样
3. 构建全局模型
4. 初始化全局模型参数
5. 选择参与的客户端
6. 分发全局模型
7. 串行训练客户模型
8. 综合客户模型的参数得到全局模型
9. 跳至第6步，直至epoch结束
10. 得到最后的全局模型