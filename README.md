# Master-Thesis

The purpose of this thesis was to investigate the predictability of Web performance by applying data mining techniques. For research purposes, a station was constructed using the MWING measuring system to record TCP connection parameters. This system was previously used in similar studies done at the Wrocław University of Technology campus (WUT), which allowed comparison of changes in local network performance compared to previous years. The MWING tool was installed on three machines. The first one is in the Laboratory of Internet and Mobile Systems in the WUT Faculty of Computer Science and Management. The other two were registered as part of the Campus Services, which are based on the PIONIER national wideband optical network.

Measurements were made for 87 servers that provided Debian operating system files. For each of the endpoints, an analysis was carried out to extract the maximum amount of information that could be useful from the Web performance perspective. A detailed analysis of autonomous systems (AS) was also carried out.

On the basis of the collected measurements, a series of computational tests were conducted in the Matlab environment, aimed at analyzing the observed performance parameters of the network. A strong dependency between TCP bandwidth and server response (RTT) has been observed. Power law is right for the medians of these two values. An approximation was made, the value of the coefficient of determination R2 = 0.95 suggests that the RTT value can be used to forecast server throughput. The strong dependence was also confirmed by subsequent studies using data mining techniques.

SPSS Modeler 18 (free license) and SPSS Statistics 24 (license of Wroclaw University of Technology) were used for data mining.

Since the research space has proved to be very broad, the data mining methodology was used for two specific business problems. The first one was the case of the prediction of the operation of many servers from which the user is interested in choosing the one that works best. The predictive quality obtained for this case was as high as 83% and was achieved for decision tree algorithms, neural networks, and K-nearest neighbors (depending on the case).

The second research problem was the performance prediction within a single server. Based on the statistical analysis two hosts were chosen, whose performance should have the worst and best predictions. In the worst case, the value of the prediction was equivalent to a random choice. For the best case, the value of 50% prediction was not exceeded, which was slightly improved compared to the random selection (33% for selected assumptions).

As a result of the research, the measurement infrastructure was left behind. It may be used in the future for performance prediction for other research assumptions or for repetition of those presented in this thesis.
