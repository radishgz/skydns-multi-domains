# skydns-multi-domains
enhance skydns to support multi-domains 
对SKYDNS进行了修改，使一个skydns可以支持多个domain suffix 并修改log 为fleet log，增加如下参数

SKYDNS_DEBUG=false 

默认为打开debug 日志，需要关闭需要设置以上上传

SKYDNS_SECOND_DOMAINS=staging.east.,staging.west.

增加默认domain外的其它domain suffix ，注意最后需要以"."结尾 

其它注意：启动时候需要设置本地地址，否则其它机器访问可能有问题

SKYDNS_ADDR=10.211.55.19:53
