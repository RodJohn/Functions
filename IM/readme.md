

# 1 第三方服务  VS  自建服务 


## 功能对比

    名称         定位           技术实现                 优点              缺点      
    
    WebSocket   协议           自己维护tcp长连接                          全球部署    维护长连接
    
    firebase    后端平台        saap                                     国内节点不行
    
    野狗         后端平台        saap                                     国外节点
    
    layim       综合方案         websocket



## 对比结果

    第三方服务
        优点
            成熟,稳定,并发高,开发速度快
        缺点
            服务不能在国内外均高可用
            数据不安全,在外部服务器
    自建服务
        优点
            数据安全,节点分布灵活
        缺点
            支撑高连接数,高并发,海量数据
            


# 2   

spring boot + websocket + STOM 服务器

t-io

api-gateway + IM的服务                      