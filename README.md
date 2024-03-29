# ark

## 概念

配置+代码=agent instance

增加新的agent类型需要按照ark系统的要求实现一组功能

## agent

- agent_type: agent的类型
- agent_name: agent的instance



## agent type



## ark config

```
ARK_HOME=~/.ark

$ tree .ark

```





## ark agent

bitrue

```
${ID}
BITRUE_API_SPOT_AK
BITRUE_API_SPOT_SK
```



# AGENT INTERFACE

```sh
# 列出所有订单
${agent_type}.order.list
id symbol side status price ov ev utime ctime age
```


## REF
 - https://github.com/tehmoon/cryptocli?tab=readme-ov-file
 - https://github.com/robertkrimen/otto
