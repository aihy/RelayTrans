# RelayTrans

## TODO

### 1 研究其他项目

- [ ] [Syncthing](https://github.com/syncthing/syncthing)
- [ ] [Transmission](https://github.com/transmission/transmission)
- [ ] [qBittorrent](https://github.com/qbittorrent/qBittorrent)
- [ ] [libtorrent](https://github.com/arvidn/libtorrent)
- [ ] [python-bittorrent](https://github.com/JosephSalisbury/python-bittorrent)
- [ ] [bittorrent-protocol](https://github.com/webtorrent/bittorrent-protocol)
- [ ] [opentracker](http://erdgeist.org/arts/software/opentracker/)
- [ ] [ipfs](https://github.com/ipfs/ipfs)
- [ ] [amule](https://github.com/amule-project/amule)
- [ ] [emule](https://www.emule-project.net/)

### 2 确立需求

1. 文件中继：解决直连速度慢的问题，所有用户帮忙中继
2. 文件下载：根据下载链接、种子、哈希值从全世界用户电脑上下载文件
3. 文件上传：给全世界用户上传文件
4. 安全：加密、匿名、混淆流量
5. 去中心化：防止被封禁
6. 评分、评论与聊天：下载文件前就知道文件评价如何，值不值得下载
7. 净化市场：如何让整体环境不被porn和劣质内容充斥
8. 奖惩制度：奖励上传者，防止迅雷吸血，如何排队，参考emule，bt，pt，bitcoin

### 3 实验探究

1. 模拟节点通信，优化上传下载中继策略
2. 模拟节点收益，优化奖惩制度

### 4 设计原则

1. 保持简单
2. 尽可能占用更少的系统资源
