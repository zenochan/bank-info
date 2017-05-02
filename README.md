# bank-info

通过银行卡号前六位获取银行名称


## Install

```groovy
repositeries{
  maven { url "http://maven.mjtown.cn/"}
}
dependencies{
  compile "name.zeno:bank-info:0.0.1"
}
```

## Usage

```
String bankInfo = BankInfo.getNameOfBank("356827");
// bankInfo: 上海银行·申卡贷记卡
```