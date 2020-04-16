-------------------------------04.16更新--------------------------
# ghost-yolo to caffe
添加了darknet2caffe.py

caffe版本再04.16弄通了。是基于前辈们的工作做的粗糙的改动，因为没时间继续钻研，做系统性的封装，所以目前还需要手动修改cfg才可以转成功weights。（我是菜鸟）

1.需要用到的文件添加了两个
darknet to caffe:https://github.com/marvis/pytorch-caffe-darknet-convert 
caffe-yolo：https://github.com/ChenYingpeng/caffe-yolov3

2.具体操作在这里：https://blog.csdn.net/weixin_38715903/article/details/105550619

3.我这边就是提供一下我修改过的文件，我自己是能跑通的。

4.大概就是这样，如果有机会再尝试封装吧



-------------------------------04.02初次------------------------
# ghost-yolo-v1
这里是ghost-yolo.cfg文件,默认大家用过darknet做过yolo训练，所以训练步骤不详述


参考 https://github.com/AlexeyAB/darknet/files/3997987/ghostnet.cfg.txt

设定了2layers ,也可以自行设计3layers

1.darknet的版本：AlexeyAB大神的
git clone https://github.com/AlexeyAB/darknet



2.然后按部就班编译，以及训练就可以了
如果不会编译可以参考博客：https://blog.csdn.net/weixin_38715903/article/details/103695844



3.【划掉】caffe版本的还没弄通，只完成了darknet的基本训练和测试之类的（我是菜鸟）



