# LSTM-Sat-Telem-Comp

This is the source code of all LSTM based deep learning models (in Matlab) implemented in the next two articles:

1) Different Long Short-Term Memory Approaches to Enhance Prediction-Based Satellite Telemetry Compression
Mahmoud, T.A., Shehab, A.F. and Elshafey, M.A., 2021. Different long short-term memory approaches to enhance prediction-based satellite telemetry compression. Journal of Aerospace Information Systems, 18(2), pp.50-57, doi:10.2514/1.I010906
Abstract:Motivated by the success of deep learning in recent years, prediction-based methods are used to compress satellite telemetry data. In this paper, two-stage lossless compression methods for telemetry data are demonstrated. In the first stage, different approaches of long short-term memory (LSTM) based on one-to-one, many-to-one, and many-to-many network architectures are presented. The framework of implementing each approach, as a predictor, is discussed. In the second stage, a set of competing entropy coding methods are tested and evaluated. The presented approaches are capable of exploring correlation dependencies between consecutive samples in the individual and/or successive telemetry frames. The proposed approaches are introduced in two different versions: stacked- and nonstacked-based LSTM architectures trying to achieve higher prediction efficiency. The proposed approaches are tested on real telemetry data, in frames of different data word widths, in distinct FUNcube satellite sessions. The performance of each presented approach, as a predictor, is evaluated based on prediction gain, and reduction in entropy. However, the performance of the whole two-stage lossless compression method is assessed by compression ratio. Comparative analysis is preformed among the proposed approaches, and the improvements are verified against the state-of-the-art prediction-based approaches.
URL:https://arc.aiaa.org/doi/abs/10.2514/1.I010906

********************************************************************************************************************************************************

and also in the basic idea presented in

2) Recurrent neural network based prediction to enhance satellite telemetry compression
A. F. Shehab, M. A. Elshafey and T. A. Mahmoud, "Recurrent Neural Network Based Prediction to Enhance Satellite Telemetry Compression," 2020 IEEE Aerospace Conference, Big Sky, MT, USA, 2020, pp. 1-11, doi: 10.1109/AERO47225.2020.9172719.
Abstract: Because of the gradually increasing number of remote measured low and/or high frequency sampled parameters in space applications, aerospace mission operators have to make hard choices on which parameters at which sampling rates should be downlinked. On-board aerospace applications are characterized by limited storage and communication budgets, while lossless data compression schemes should be sufficient enough to enhance transmission efficiency and hence the whole aerospace mission. In this paper, a proposed two-stage lossless compression method for telemetry data is presented. The proposed method consists of a decorrelation stage and an entropy coding one. The Long-Short-Term Memory (LSTM) Recurrent Neural Network (RNN) is implemented as a predictor in the decorrelation stage of the proposed method, and an illustrative method of applying LSTM network for telemetry data samples prediction is presented and figured out. In experiments, different entropy coders: Rice codes, arithmetic method and Huffman algorithm are separately implemented at the second stage. The proposed method is tested by different real telemetry data sets of FUNcube satellite in frames of data words of 8-,10-,16-bits widths. Experimental results show that the proposed method improved compression efficiency based on a single stage of entropy coder: Rice codes, arithmetic code, and Huffman algorithm by a ratio up to: 98%, 21%, and 1.6%, respectively.
URL: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9172719&isnumber=9172248

***********************************************************************************************************************************************************
Also the three telemetry datasets from FunCube Satellite, which are test are also included

************************************************************************************************************************************************************


