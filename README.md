# DAMA-DMBOK2-Data-Quality-Dimesion
DAMA-DMBOK2-Data-Quality-Dimesion is a quick reference and implementation of the DAMA Guide to the Data Management Body of Knowledge, focued on the dimension of data quality.


# DQD - Data Quality Dimesions

## A. [DMBoK2] Table 29, page 462 ~ 464.

1. Accuracy 準確性
2. Completeness 完備性
3. Consistency 一致性
4. Integrity 完整性
5. Reasonability 合理性
6. Timeliness 時效性
7. Uniqueness 獨特性
8. Validity 有效性


## B. [CloverDX] 6 Data Quality Metrics

1. Completeness 完備性
    * 必要的資料是否全部都有正確地出現於 dataset 中?
    * This measures whether all the necessary data is present in a specific dataset. You can think about completeness in one of two ways: at the record level or at the attribute level. Measuring completeness at the attribute level is a little more complex however, as not all fields will be mandatory.
    * An example metric for completeness is the percent of data fields that have values entered into them.

2. Accuracy 準確性
    * 與現實相比, 資料與模型是否準確表達/反映真實狀況?
    * How accurately does your data reflect the real-world object? 
    * An example metric for accuracy is finding the percentage of values that are correct compared to the actual value.

3. Consistency 一致性
    * 所有系統的 data 所表達的意義是否一致?
    * Maintaining synchronicity between different databases is essential. To ensure data remains consistent on a daily basis, software systems are often the answer.
    * For example, transaction consistency helps you detect incomplete financial transactions. Once found, you can roll back those errors meaning both balances remain in check.

4. Validity 有效性
    * 衡量 data 必須具備之屬性的程度 如: 是否符合相同的格式?
    * Validity is a measure of how well data conforms to required value attributes
    * For example, ensuring dates conform to the same format, i.e., date/month/year or month/date/year.

5. Timeliness 時效性
    * data 是否即時?
    * Timeliness reflects the accuracy of data at a specific point in time. 
    * An example of this is when a customer moves to a new house, how timely are they in informing their bank of their new address?

6. Integrity 完整性
    * data 在不同系統之間是否保持相同且完整? 如: 跨多個系統的相同數據的百分比
    * To ensure data integrity, it’s important to maintain all the data quality metrics we’ve mentioned above as your data moves between different systems. Typically, data stored in multiple systems breaks data integrity.
    * An example metric for integrity is the percent of data that is the same across multiple systems.


# Ref
* [DAMA DMBoK2 - Body of Knowledge (edition 2)](https://www.dama.org/cpages/body-of-knowledge)
* [6 Data Quality Metrics You Can't Afford To Ignore](https://www.cloverdx.com/blog/6-data-quality-metrics-you-cant-ignore)
* [深度解读数据管理葵花宝典-《DAMA-DMBOK2数据管理知识体系指南（第2版）》](https://blog.csdn.net/fuyipingwml1976124/article/details/106233428)


<!-- Links -->
[DMBoK2]: https://www.dama.org/cpages/body-of-knowledge
[CloverDX]: https://www.cloverdx.com/blog/6-data-quality-metrics-you-cant-ignore
