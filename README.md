# forex bot
1. catboost 是一个很容易上手的开源gradient boost on decision trees工具。可以通过历史数据和一些辅助的数据维度来发现pattern的可能性（possibilities）
2. Icarus是一个很稳定的metatrader 4的EA，现有的Icarus是martingale交易，是双向anti-trend交易。在sideway trend可以盈利。但在超出range的（up、down) trend就会爆仓。
Icarus提供了多仓位交易 和 很多有用的交易信息。
## 设想
1. 利用catboost 训练一个pattern的 decision tree。在possibilities有利的情况下开仓，如果在下一个pattern形成时候，如果判定trend继续可以加仓，如果判定counter trend获利平仓。
2. stop limit也是又pattern的反向possibilities来设定
3. pattern应该是time frame independent。
4. 可以在多个time frame上做一致性判定
5. 
new line
