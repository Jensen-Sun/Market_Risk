# Market_Risk
S&amp;P500波动率预测
从yfinance中导入S&P5002010-2024年的数据，分别采用ARCH、GARCH、GIR-GARCH、EGARCH、SVR-GARCH、神经网络模型对2024年的S&P500的波动率进行预测，选用RMSE对模型的预测结果进行评价，实验结果显示，机器学习算法预测误差RMSE在0.0005左右，显著低于传统GARCH系列模型的预测误差（0.077左右），预测精度大幅提升。
