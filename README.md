# TreeGame
# 1 代码中实现了搜索二叉树，包括给二叉树增加元素，删除元素，查找元素；

# 2 游戏主要用炮弹击中外星人（飞机）;外星人的坐标是随机生成的一组数，有10个元素，就是用二叉树来构建的。

    输入x 和 y坐标，来和此时外星人的坐标进行比较，此时运用二叉树的查找元素search这一方法，
	
	如果x坐标不一致，则y坐标在上一次的基础上加30,随机生成外星人的新的坐标。
	
	如果找到了，与X坐标一致，则重新render 渲染页面，提示文字显示，已拯救地球
	