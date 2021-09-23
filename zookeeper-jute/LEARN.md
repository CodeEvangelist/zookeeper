###问题一：源码编译异常-提示缺少org.apache.zookeeper.data.*下的包
####答案:运行zookeeper-jute下的maven的compile插件，发现问题解决，但暂不清楚，目前只知道zookeeper-jute的resource目录下有对应的模块文件，但是并不是.java结尾，还需要后续仔细确认清楚，当前为了先弄清楚整体功能，暂不深究