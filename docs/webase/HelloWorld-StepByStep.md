## 1 部署WeBASE。

## 2 登录WeBASE管理平台，添加节点信息，私钥信息等。
* 节点信息：
![[节点]](../../images/webase/frontInfo.png)

* 私钥用户：
![[私钥用户]](../../images/webase/keyUser.png)

## 3 开发智能合约，编译、部署、测试合约。
* 部署合约
![[合约]](../../images/webase/contract.png)

##4 根据所写合约和交易api的格式，发送交易。
* 入参：
```
{
    "contractAddress": "0xca597170829f4ad5054b618425a56e0be23cbc55",
    "contractName": "HelloWorld",
    "funcName": "set",
    "funcParam": [ "abc"],
    "groupId": 1,
    "useAes": true,
    "user": "0x4f08eac5af5e77b7006d11bee94adba2f721def8"
}
```

* 交易回执：
```
{
    "transactionHash": "0x295f2d6f520927e270b08d868d45fee34c642711f6076fe63edaab36f543220f",
    "transactionIndex": 0,
    "blockHash": "0x3536d8ac680d38afd6389190f7aba08b73292820cb9977fb006013edb05848ea",
    "blockNumber": 5,
    "cumulativeGasUsed": 0,
    "gasUsed": 32940,
    "contractAddress": "0x0000000000000000000000000000000000000000",
    "status": "0x0",
    "from": "0x4f08eac5af5e77b7006d11bee94adba2f721def8",
    "to": "0xca597170829f4ad5054b618425a56e0be23cbc55",
    "output": "0x",
    "logs": [],
    "logsBloom": "0x00000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000",
    "gasUsedRaw": "0x80ac",
    "statusOK": true,
    "blockNumberRaw": "0x5",
    "transactionIndexRaw": "0x0"
}
```

## 5 登录管理平台查看交易详情，查看交易统计信息，在线运维管理。
* 查看交易解析
![[交易解析]](../../images/webase/transHash.png)

* 交易审计
![[交易审计]](../../images/webase/monitor.png)





