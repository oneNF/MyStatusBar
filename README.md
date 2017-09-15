# MyStatusBar
my first project
状态栏设置 简单粗暴 ：
1.引用库：compile 'com.jaeger.statusbaruitl:library:1.3.6'
2.在acitivity 加入两句代码：        
                    StatusBarUtil.setTransparent(this);
                    StatusBarUtil.setColorNoTranslucent(this, ContextCompat.getColor(this,R.color.color_74b5fe));//设置你要的颜色值
