# Abstract

This is my 2015 undergraduate graduation design based on GraphX().

Common Interfaces implementedd in this system for upper users:


效率比较高的算法有标签传播(LPA)，lovain method, infomap等，其中以infomap综合优势最好，因为infomap通吃所有类型的网络(有向无向有权无权)，且是线性时间，发现的社区质量也比较。


社区发现发展到现在，领域的拼图基本完善了，可是实际应用一直是困扰这个领域的痛点。所以我觉得在现有评价体系下，再求准没意义了接下来的重点研究方向是scalabl。Louvain则是将Modularity的优化进行了scalable，可以快速的应用在大规模的网络上. This project implements Lonvain on GraphX.




