# Adaboost

**任务：**《机器学习实战》书籍第7章
**参考文献：**李航《统计学习方法》第8章 8.1/8.2/8.3节

细节问题：AdaBoost选择分类器是弱分类器还是强分类器？解释原因。
弱分类器。若是强分类器，那么该分类器占的权重alpha会很大，相当于其它分类器不起作用了。所以，多个弱分类器起到“三个臭皮匠，赛过诸葛亮”的效果。