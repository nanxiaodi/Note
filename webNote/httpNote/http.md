# http笔记(一)
## http消息头
1. 一般头: 同时适用请求和相应消息

2. 请求头: 包含客户端要获取的资源以及客户端的一些消息
3. 响应头: 包含有关服务器响应的补充信息,如其位置或服务器(名称和版本)等的消息头 
4. 实际头: 包含有关实体主体的信息,比如主体长度或者MIME类型
    - MIME类型就是content-type,由类型和子类型组成,用  / 进行分割
        1.  [text/plain[文本/无意义]
            text/html[文本/html]
            image/jpeg[图片/jpeg图片]
            video/mp4[视频/MP4]
            application/octet-stream[二进制数据/无特定]....](https://developer.mozilla.org/zh-CN/docs/Web/HTTP/Basics_of_HTTP/MIME_types)


