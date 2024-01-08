
## 支付方式
| API名称 | 函数名 | 贡献者名称 | 完成情况 |
|---------|--------|------------|----------|
| [H5支付](https://pay.weixin.qq.com/wiki/doc/apiv3/apis/chapter3_3_1.shtml) | `h5Payment` | 待定 | [ ] |
| [Native支付](https://pay.weixin.qq.com/wiki/doc/apiv3/apis/chapter3_4_1.shtml) | [nativePayment](docs/nativePayment.md) | [zhangrenyang](https://github.com/zhangrenyang) | [√] |
| [App支付](https://pay.weixin.qq.com/wiki/doc/apiv3/apis/chapter3_2_1.shtml) | `appPayment` | 待定 | [ ] |
| [JSAPI支付 或 小程序支付](https://pay.weixin.qq.com/wiki/doc/apiv3/apis/chapter3_1_1.shtml) | `jsapiPayment` | 待定 | [ ] |
| [合单H5支付](https://pay.weixin.qq.com/wiki/doc/apiv3/apis/chapter5_1_2.shtml) | `combineH5Payment` | 待定 | [ ] |
| [合单Native支付](https://pay.weixin.qq.com/wiki/doc/apiv3/apis/chapter5_1_5.shtml) | `combineNativePayment` | 待定 | [ ] |
| [合单App支付](https://pay.weixin.qq.com/wiki/doc/apiv3/apis/chapter5_1_1.shtml) | `combineAppPayment` | 待定 | [ ] |
| [合单JSAPI支付 或 小程序支付](https://pay.weixin.qq.com/wiki/doc/apiv3/apis/chapter5_1_3.shtml) | `combineJsapiPayment` | [yuyansun](https://github.com/Irenia111) | [ ] |

## 订单管理
| API名称 | 函数名 | 贡献者名称 | 完成情况 |
|---------|--------|------------|----------|
| [查询订单](https://pay.weixin.qq.com/wiki/doc/apiv3/apis/chapter3_1_2.shtml) | [queryOrder](docs/queryOrder.md) | [zhangrenyang](https://github.com/zhangrenyang)  | [√] |
| [关闭订单](https://pay.weixin.qq.com/wiki/doc/apiv3/apis/chapter3_1_3.shtml) | [closeOrder](docs/closeOrder.md) | [zhangrenyang](https://github.com/zhangrenyang)  | [√] |
| [查询合单](https://pay.weixin.qq.com/wiki/doc/apiv3/apis/chapter5_1_11.shtml) | `queryCombinedOrder` | 待定 | [ ] |
| [关闭合单](https://pay.weixin.qq.com/wiki/doc/apiv3/apis/chapter5_1_12.shtml) | `closeCombinedOrder` | 待定 | [ ] |

## 账单和资金管理
| API名称 | 函数名 | 贡献者名称 | 完成情况 |
|---------|--------|------------|----------|
| [申请交易账单](https://pay.weixin.qq.com/wiki/doc/apiv3/apis/chapter3_1_6.shtml) | `requestTradeBill` | 待定 | [ ] |
| [申请资金账单](https://pay.weixin.qq.com/wiki/doc/apiv3/apis/chapter3_1_7.shtml) | `requestFundFlowBill` | 待定 | [ ] |
| [下载账单](https://pay.weixin.qq.com/wiki/doc/apiv3/apis/chapter3_1_8.shtml) | `downloadBillingStatement` | 待定 | [ ] |

## 退款和分账 
| API名称 | 函数名 | 贡献者名称 | 完成情况 |
|---------|--------|------------|----------|
| [申请退款](https://pay.weixin.qq.com/wiki/doc/apiv3/apis/chapter3_2_9.shtml) | `requestRefund` | 待定 | [ ] |
| [查询退款](https://pay.weixin.qq.com/wiki/doc/apiv3/apis/chapter3_2_10.shtml) | `queryRefund` | 待定 | [ ] |
| [分账](https://pay.weixin.qq.com/wiki/doc/apiv3/apis/chapter8_1_1.shtml) | `createProfitSharingOrder` | 待定 | [ ] |

## 安全和验证
| API名称 | 函数名 | 贡献者名称 | 完成情况 |
|---------|--------|------------|----------|
| [解密信息](https://pay.weixin.qq.com/docs/merchant/development/interface-rules/sensitive-data-encryption.html) | [decrypt](docs/decrypt.md) | [zhangrenyang](https://github.com/zhangrenyang)  | [√] |
| [签名验证](https://pay.weixin.qq.com/docs/merchant/development/interface-rules/signature-verification.html) | [verifySignature](docs/verifySignature.md) | [zhangrenyang](https://github.com/zhangrenyang)  | [√] |
| [根据序列号获取公钥](https://pay.weixin.qq.com/docs/merchant/apis/platform-certificate/api-v3-get-certificates/get.html) | [fetchWechatPayPublicKey](docs/fetchWechatPayPublicKey.md) | 待定 | [ ] |

## 其他功能
| API名称 | 函数名 | 贡献者名称 | 完成情况 |
|---------|--------|------------|----------|
| [微信提现到零钱](https://pay.weixin.qq.com/docs/merchant/apis/batch-transfer-to-balance/transfer-batch/initiate-batch-transfer.html) | `transferToWallet` | 待定 | [ ] |
