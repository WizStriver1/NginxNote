# Nginx 出现413 Request Entity Too Large的解决方法

client_max_body_size设置为限定值，比如下面设置为10m。
```
http {
    client_max_body_size 10m;
}
```