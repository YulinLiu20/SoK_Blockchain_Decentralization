
## 2. [Decentralization Index of Top DeFi Tokens](https://github.com/SciEcon/SoK_Blockchain_Decentralization/tree/main/Data_TokenIndex)

### 2.1 Table of Data Files

 |   **Name**   | **Token** | **First Observation Date** |  **File Name** |
 |:------------:|:---------:|:--------------------------:|:--------------:|
 |     Aave     |    AAVE   |         2020-10-02         |  Aave_ent.csv  |
 |   Compound   |    COMP   |         2020-06-14         |  Comp_ent.csv  |
 |     Maker    |    MKR    |         2017-12-15         |  Maker_ent.csv |
 |      Dai     |    DAI    |         2019-11-18         |   Dai_ent.csv  |
 |      Sai     |    SAI    |         2017-12-18         |   Sai_ent.csv  |
 |    Liquity   |    LQTY   |         2021-04-05         |  Lqty_ent.csv  |
 |    Uniswap   |    UNI    |         2020-09-18         |   Uni_ent.csv  |
 |   Sushiswap  |   SUSHI   |         2020-08-26         |  Sushi_ent.csv |
 |   Balancer   |    BAL    |         2020-06-20         |   Bal_ent.csv  |
 |    Bancor    |    BNT    |         2017-06-17         |   Bnt_ent.csv  |
 | Convex Curve |   CVXCRV  |         2021-05-17         | CVXCRV_ent.csv |
 |    Convex    |    CVX    |         2021-05-17         |   CVX_ent.csv  |
 | Fei Protocol |   TRIBE   |          2020-3-28         |  Tribe_ent.csv |
 |     RenVM    |    REN    |         2017-12-31         |   Ren_ent.csv  |
 |     Flexa    |    AMP    |         2019-01-09         |   Fxc_ent.csv  |
 | Tornado Cash |    TORN   |         2020-12-18         |  Torn_ent.csv  |
 |   Synthetix  |    SNX    |         2020-05-11         |   Snx_ent.csv  |
 | Nexus Mutual |    NXM    |         2019-05-23         |   Nxm_ent.csv  |
 
### 2.2 Data Dictionary
 
 | **Variable Name** | **Unit** | **Frequency** | **Description**                                                                                              |
|-------------------|----------|---------------|--------------------------------------------------------------------------------------------------------------|
| val               | N/A      | Daily         | Shannon entropy value of transaction decentralization over the entire day before 00:00 UTC the following day |
| date              | N/A      | Daily         | The corresponding date index was calculated for    
 
### 2.3 More about Data Source
Caculated from Google [BigQuery Ethereum dataset token](https://cloud.google.com/blog/products/data-analytics/ethereum-bigquery-public-dataset-smart-contract-analytics) transfers table. 

