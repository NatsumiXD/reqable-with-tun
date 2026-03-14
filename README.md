# reqable-with-tun
在reqable中利用clash(mihomo)的tun实现全数据包拦截（支持系统代理拦截）

## 经过测试可用：
FLClash

## 使用方法：
1. 确保reqable的代理打开在9000端口上，并启动调试（使系统代理未设置）
2. 导入仓库中的yaml到clash里面，打开虚拟网卡(or tun)+关闭代理启动
3. 此时即可在reqable中收到系统内所有数据包

## 注意事项：
为了避免reqable处理海量数据包然后爆掉，尽量少开联网软件。
