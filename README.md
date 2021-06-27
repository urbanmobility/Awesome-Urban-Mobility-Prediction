This is a list of useful information about urban mobility prediction. Related papers, datasets and codes are included.

### POI Recommendations
Papers | Paper | Code | Time | Accepted | Accuracy |
-------|-------|------|------|----------|----------|
A recurrent model with spatial and temporal contexts.(ST-RNN) | [Paper](https://ojs.aaai.org/index.php/AAAI/article/view/9971)| [Code](https://github.com/yongqyu/STRNN) | 2016 | AAAI | Gowalla: Rec@5 =0.1524, Rec@10=0.2714.<br>GTD: Rec@5=0.4986, Rec@10=0.6812. |
Geo-teaser: Geo-temporal sequential embedding rank for point-of-interest recommendation.(Geo-teaser) | [Paper](https://dl.acm.org/doi/abs/10.1145/3041021.3054138)| [Code](https://github.com/JasonLiu-THU/geo_teaser) | 2017 | WWW | Foursquare: Prec@5=0.13, Prec@10=0.1, Rec@5=0.15, Rec@10=0.2<br>Gowalla: Prec@5=0.16, Prec@10=0.13, Rec@5=0.07, Rec@10=0.1 |
Next point-of-interest recommendation with temporal and multi-level context attention.(TMCA) | [Paper](https://ieeexplore.ieee.org/abstract/document/8594953)| [Code](https://github.com/zhenql/TMCA) | 2018 | ICDM | Gowalla: Rec@5=0.21926, Rec@10=0.27725.<br>Foursquare: Rec@5=0.02870, Rec@10=0.04809. |
HST-LSTM: A Hierarchical Spatial-Temporal Long-Short Term Memory Network for Location Prediction.(HST-LSTM) | [Paper](https://www.ijcai.org/Proceedings/2018/0324.pdf)| None | 2018 | IJCAI | Baidu Map: Acc@10=0.4847, Acc@20=0.5657. |
Content-aware hierarchical point-of-interest embedding model for successive poi recommendation.(CAPE) | [Paper](https://www.ijcai.org/Proceedings/2018/0458.pdf)| [Code](https://github.com/qnfnwkd/CAPE) | 2018 | IJCAI |With STELLAR: Rec@5=0.2384, Rec@10=0.2989.<br>With LSTM: Rec@5=0.2412, Rec@10=0.3054.<br>With GRU: Rec@5=0.2433, Rec@10=0.3079.<br>With ST-RNN: Rec@5=0.2239, Rec@10=0.2601. |
DeepMove: Predicting Human Mobility with Attentional Recurrent Networks.(DeepMove) | [Paper](https://dl.acm.org/doi/abs/10.1145/3178876.3186058)| [Code](https://github.com/vonfeng/DeepMove) | 2018 | WWW | Foursquare (NY): Rec@5=0.3372, Rec@10=0.4091.<br>Gowalla: Rec@5=0.2021, Rec@10=0.2510. |
Long-and short-term preference learning for next poi recommendation(LSPL). | [Paper](https://dl.acm.org/doi/abs/10.1145/3357384.3358171)| None | 2019 | CIKM | Foursquare (NYC): Prec3@10=0.3901, Prec@20=0.4461.<br>Foursquare (TKY): Prec@10=0.3986, Prec@20=0.4596. |
Where to go next: A spatio-temporal gated network for next poi recommendation.(STGCN) | [Paper](https://ieeexplore.ieee.org/abstract/document/9133505)| [Code](https://github.com/VeritasYin/STGCN_IJCAI-18) | 2019 | AAAI | Foursquare (CA): Acc@5=0.1308, Acc@10=0.1612.<br>Foursquare (SIN): Acc@5=0.2737, Acc@10=0.3017.<br>Gowalla: Acc@5=0.1644, Acc@10=0.2020.<br>Brightkite: Acc@5=0.4953, Acc@10=0.5231. |
Topic-Enhanced Memory Networks for Personalised Point-of-Interest Recommendation.(TEMN) | [Paper](https://dl.acm.org/doi/abs/10.1145/3292500.3330781)| [Code](https://github.com/XiaoZHOUCAM/Topic-Enhanced-Memory-Networks-for-Personalised-Point-of-Interest-Recommendation) | 2019 | KDD | WeChat (GPR):<br>TEMN (GPR): Acc@5=0.70389, Acc@10=0.81752.<br>TEMN (CPR): Acc@5=0.72876, Acc@10=0.83398. |
Location prediction over sparse user mobility traces using rnns: Flashback in hidden states!(Flashback) | [Paper](https://www.ijcai.org/Proceedings/2020/0302.pdf)| [Code](https://github.com/eXascaleInfolab/Flashback_code) | 2020 | IJCAI | Foursquare: Acc2@5=0.5399, Acc@10=0.6236.<br>Gowalla: Acc@5=0.2754, Acc@10=0.3479. |
Discovering subsequence patterns for next poi recommendation!(ASPPA)  | [Paper](https://www.ijcai.org/Proceedings/2020/0445.pdf)| None | 2020 | IJCAI | Foursquare (US): Acc@10=0.3371, Acc@20=0.3950.<br>Gowalla: Acc@10=0.2947, Acc@20=0.3573. |
Next Point-of-Interest Recommendation on Resource-Constrained Mobile Devices.(LLRec) | [Paper](https://dl.acm.org/doi/abs/10.1145/3366423.3380170)| None | 2020 | WWW | Foursquare: Acc@10=0.3542, Acc@20=0.4594.<br>Gowalla: Acc@10=0.3874, Acc@20=0.4781. |
Personalized Long- and Short-term Preference Learning for Next POI Recommendation.(PLSPL) | [Paper](https://ieeexplore.ieee.org/abstract/document/9117156)| None | 2020 | TKDE | Foursquare (NYC): Prec@10=0.3953, Prec@20=0.4475<br>Foursquare (TKY): Prec@10=0.4020, Prec@20=0.4664. |
Where to go next: Modeling long-and short-term user preferences for point-ofinterest recommendation.(LSTPM) | [Paper](https://ojs.aaai.org/index.php/AAAI/article/view/5353)| [Code](https://github.com/NLPWM-WHU/LSTPM) | 2020 | AAAI | Foursquare (NY): Rec@5=0.3372, Rec@10=0.4091.<br>Gowalla: Rec@5=0.2021, Rec@10=0.2510. |
An Interactive Multi-Task Learning Framework for Next POI Recommendation with Uncertain Check-ins.(iMTL) | [Paper](https://www.ijcai.org/Proceedings/2020/0491.pdf)| None | 2020 | IJCAI | Foursquare (CLT): Rec@10=0.0534, Map4@10=0.0238.<br>Foursquare (CAL): Rec@10=0.0691, Map@10=0.0443.<br>Foursquare (PHO): Rec@10=0.0769, Map@10=0.0352. |
A Category-Aware Deep Model for Successive POI Recommendation on Sparse Check-in Data.(CatDM) | [Paper](https://dl.acm.org/doi/abs/10.1145/3366423.3380202)| [Code](https://github.com/fqyuu/CatDM) | 2020 | WWW | Foursquare (NYC): Rec@5=0.2407, Rec@10=0.3113.<br>Foursquare (TKY): Rec@5=0.2148, Rec@10=0.2739. |
An attentional recurrent neural network for personalized next location recommendation.(ARNN) | [Paper](https://ojs.aaai.org/index.php/AAAI/article/view/5337)| None | 2020 | WWW | Foursquare (NY): Acc@10=0.4162, Acc@20=0.4393<br>Foursquare (TK): Acc@10=0.4285, Acc@20=0.4864<br>Gowalla (SF): Acc@10=0.2336, Acc@20=0.2530. |
Exploiting geographical-temporal awareness attention for next point-of-interest recommendation.(GT-HAN) | [Paper](https://www.sciencedirect.com/science/article/abs/pii/S0925231220300680)| None | 2020 | Neurocomputing | Foursquare: AUC8=0.9661, acc@5: 0.13-0.15, acc@10: 0.17-0.19, acc@20: 0.23-0.25 (depending on latent dimensionality). |
Time-Aware Location Prediction by Convolutional Area-of-Interest Modeling and Memory-Augmented Attentive LSTM.(t-LocPred) | [Paper](https://ieeexplore.ieee.org/abstract/document/9128016)| None | 2020 | TKDE | Gowalla: MRR5=0.247 (C=6, all),<br>Weeplaces: MRR=0.277 (C=6, all),<br>Brightkite: MRR=0.388 (C=4, all). |
Content-Aware Successive Point-of-Interest Recommendation.(CAPRE) | [Paper](https://epubs.siam.org/doi/abs/10.1137/1.9781611976236.12)| None | 2020 | SDM | Foursquare: Rec@5=0.1724, Rec@10=0.2084<br>Instagram: Rec@5=0.2934, Rec@10=0.3588. |
Geography-Aware Sequential Location Recommendation.(GeoSAN) | [Paper](https://dl.acm.org/doi/abs/10.1145/3394486.3403252)| [Code](https://github.com/libertyeagle/GeoSAN) | 2020 | KDD | Foursquare: Acc@5=0.3735, Acc@10=0.4867.<br>Gowalla: Acc@5=0.4951, Acc@10=0.6028.<br>Brightkite: Acc@5=0.5258, Acc@10=0.6425.|




