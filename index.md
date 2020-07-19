---
layout: default
---
I am a member of PNNL's [computing research division](http://www.pnnl.gov/computing/). Here are some problems keeping us inspired.

<img src="images/spark.jpeg">

## [](#header-2) Latest News
* "A look inside the black box: Using graph- theoretical descriptors to interpret a Continuous-Filter Convolutional Neural Network (CF-CNN) trained on the global and local minimum energy structures of neutral water clusters". 2020 Journal of Chemical Physics special issue Machine Learning Meets Chemical Physics. [Paper](publications/2020_interpretable_molecular_convnets.pdf) [Code](https://github.com/exalearn/molecular-graph-descriptors)
* [Preprint](publications/2020_arxiv_koopman.pdf) "Model-Agnostic Algorithm for Real-Time Attack Identification in Power Grid using Koopman Modes." 
* New [molecular graph database](https://sites.uw.edu/wdbase) with nearly 5 million structures released.
* [Open-source](https://github.com/pnnl/GridSTAGE) release of GridSTAGE, a multivariate spatio-temporal data generation framework for simulation of adversarial scenarios in cyber-physical systems. [Slides](publications/Powerdrone_eML_2020Apr_v1.pdf)
* [Preprint](publications/2020_gramnet.pdf) "XQA: Relationship Explanation in Knowledge Graphs via Graph-Augmented Neural Networks."
* [Tutorial](publications/ECP2020-ExalearnDesign-Tutorial-v3.pdf) at 2020 Exascale Computing Project's Annual Meeting on Molecule Design via Deep Reinforcement Learning.
* [Snomed2Vec: Random Walk and Poincaré Embeddings of a Clinical Knowledge Base for Healthcare Analytics](https://arxiv.org/abs/1907.08650) 2019 KDD Workshop on Applied Data Science for Healthcare (DSHealth '19)/KDD Health Day.
* [Enterprise Cyber Resiliency Against Lateral Movement: A Graph Theoretic Approach,](https://arxiv.org/pdf/1905.01002.pdf) book chapter in Industrial Control Systems Security and Resiliency, Springer 2019.
* Our paper on [Temporal Subgraph Isomorphism](publications/2018_ieee_bigdata_gta3.pdf) received best paper award at 2nd IEEE BigData Workshop on Graph Techniques for Adversarial Activity Analytics.
* [StreamWorks](publications/2015_streamworks_edbt.pdf) wins a [R&D100 award](https://www.pnnl.gov/news/release.aspx?id=4530).
* Presentation on Streaming Graph Querying for Cyber-security at Microsoft BlueHat conference: [Continuous Pattern Detection on Streaming Data: Present and Future](publications/StreamWorks_BlueHat.pdf).
* [Arun Sathanur](https://www.linkedin.com/in/arunsathanur) and I are super excited to announce the initial release of a [parallel generator for attributed graph databases](https://github.com/propgraph/pgm).  Please check it out - bug reports are highly appreciated!
* Our paper "[Scalable Pattern Discovery from Dynamic Graphs](publications/2018_wsdm_percolator.pdf)" accepted in [2018 ACM Intl. Conf. on Web Search and Data Mining (WSDM)](http://www.wsdm-conference.org/2018/)
* Our paper "[Application Specific Graph Sampling for Frequent Subgraph Mining and Community Detection](publications/2017_GMSampling.pdf)" accepted in [IEEE BigData 2017](http://cci.drexel.edu/bigdata/bigdata2017)
* Upcoming talk on "Networks and Graphs" at [CoDA 2018](http://cnls.lanl.gov/coda2018) at Los Alamost National Laboratory.

## [](#header-2) Knowledge Graphs
The ability to construct domain specific knowledge graphs is critical to drive needs for question-answering or hypothesis generation. Despite their value, automated construction of knowledge graphs remains an expensive technical challenge that is beyond the reach for most enterprises and academic institutions. We propose an end-to-end framework for developing custom knowledge graph driven analytics for arbitrary application domains. 

* Please check out [NOUS](https://github.com/streaming-graphs/NOUS), our open source knowledge graph framework.
* Our [short paper in Data Engineering meets the Semantic Web, at ICDE 2017](https://arxiv.org/pdf/1606.02314.pdf) shows how a generic knowledge graph system can answer complex application queries by reading the web
* Data quality is a major issue for automated knowledge graph construction. See our [paper in 2016 SDM Workshop](https://arxiv.org/pdf/1601.03778) for estimating confidence in triples via Bayesian Personalized Ranking
* Discovering frequent patterns in the data is critical for sensemaking. See our paper in 2014 KDD Workshop for [Learning frequent patterns from graph streams](http://proceedings.mlr.press/v36/ray14.pdf).

## [](#header-1) Streaming Algorithms
StreamWorks is a graph analytics system designed to detect patterns from massive data streams. This video shows a demonstration of StreamWorks's capability to detect exfiltration events from a network traffic flow data stream. StreamWorks was selected by US Department of Homeland Security as the 2017 graduate of its [Transition-To-Practice program](https://www.dhs.gov/science-and-technology/csd-ttp).

* Our paper on [Temporal Subgraph Isomorphism](publications/2018_ieee_bigdata_gta3.pdf) at 2nd IEEE BigData Workshop on Graph Techniques for Adversarial Activity Analytics.
* Check out our [EDBT paper](publications/2015_streamworks_edbt.pdf) on detecting patterns from dynamic graph datastreams via subgraph isomorphism.
* If you are interested in exploring graph querying for cyber-security applications, see our [SIGMOD workshop paper](publications/2013_grades.pdf).
* The entire pipeline is described in our [SIGMOD demonstrations paper](publications/2013_sigmod_demo.pdf).
* Not streaming, but this [SIGMOD workshop paper](publications/2014_parasol.pdf) explores the issues around querying cross-cloud databases.

## [](#header-1) Autonomous Systems Design
Resilience is the ability of a system to continue to function, even in a degraded manner, in the face of impediments that affect the proper operation of some of its components. For a cyber-network impediments can be randomly occurring failures of software services or hardware systems in an enterprise, or it may be unavailability of services or systems as the consequence of a cyber attack. 
* [Enterprise Cyber Resiliency Against Lateral Movement: A Graph Theoretic Approach,](https://arxiv.org/pdf/1905.01002.pdf) book chapter in Industrial Control Systems Security and Resiliency, Springer 2019.
* We published this [really cool paper in ICASSP 2016](publications/2016_icassp.pdf) showing how graph models and their metrics provide a simple, yet powerful tool to discover diverse types of network intrusions.
* Our paper at [2015 Automated Decision Making for Active Cyber Defense](publications/2015_safeconfig.pdf) presenting algorithms to alter a network itself to adapt to an attack
* Our [paper](publications/2015_acm_ccs_demo.pdf) at 2015 ACM Conference on Computer and Communications Security showing a live demonstration of cyber resilience in Amazon Cloud

## [](#header-1) Sensor Networks
In my prior life I had implemented a sensor network protocol named [PakBus](https://s.campbellsci.com/documents/cn/manuals/pakbusnetguide.pdf). Developed by Campbell Scientific, PakBus is universally used by data collection devices. Our open-source version of a C++/Linux version of PakBus is available [here](https://github.com/sutanay/PbCdlComm).

## [](#header-4) Recent Publications
* Jenna A. Bilbrey, Joseph P. Heindel, Malachi Schram, Pradipta Bandyopadhyay, Sotiris S. Xantheas, and Sutanay Choudhury. [A look inside the black box: Using graph-theoretical descriptors to interpret a Continuous-Filter Convolutional Neural Network (CF-CNN) trained on the global and local minimum energy structures of neutral water clusters](publications/2020_interpretable_molecular_convnets.pdf) J. Chem. Phys. 153, 024302 (2020).
* K. Agarwal, T. Eftimov, R. Addanki, S. Choudhury, S. Tamang and R. Rallo. [Snomed2Vec: Random Walk and Poincaré Embeddings of a Clinical Knowledge Base for Healthcare Analytics](https://arxiv.org/abs/1907.08650) 2019 KDD Workshop on Applied Data Science for Healthcare (DSHealth '19)/KDD Health Day.
* Chen P.-Y., S. Choudhury, L. Rodriguez, A.O. Hero and I. Ray, [Enterprise Cyber Resiliency Against Lateral Movement: A Graph Theoretic Approach,](https://arxiv.org/pdf/1905.01002.pdf) Chapter in Industrial Control Systems Security and Resiliency: Practice and Theory, Eds. C. Rieger, I. Ray, Q. Zhu, M. Haney, Springer 2019.
* Joslyn C.A., M. Robinson, J. Smart, K. Agarwal, D. Bridgeland, A.G. Brown, and S. Choudhury, et al. "HyperThesis: Topological Hypothesis Management in a Hypergraph Knowledgebase." NIST Text Analysis Conference (TAC) 2018, Gaithersburg, Maryland. 
* Mackey P.S., K. Porterfield, E.B. Fitzhenry, S. Choudhury, and G. Chin. 2018. [A Chronological Edge-Driven Approach to Temporal Subgraph Isomorphism.](publications/2018_ieee_bigdata_gta3.pdf) In The 2nd IEEE BigData Workshop on Graph Techniques for Adversarial Activity Analytics. 
* Deep Learning for Scientific Discovery, C. Corley, N. Hodas, E. Yeung, A. Tartakovsky, T. Hagge, S. Choudhury, K. Agarwal, C. Siegel, J. Daily.  The Next Wave, 2018.
* Choudhury, S., Purohit, S., Lin, P., Wu, Y., Holder, L., & Agarwal, K. 2018. [Percolator: Scalable Pattern Discovery in Dynamic Graphs](publications/2018_wsdm_percolator.pdf).  11th ACM International Conference on Web Search and Data Mining.
*  Sathanur, A. V., Choudhury, S., Joslyn, C., & Purohit, S. (2017). [When Labels Fall Short: Property Graph Simulation via Blending of Network Structure and Vertex Attributes](publications/2017_cikm_graphgen.pdf). 26th ACM International Conference on Information and Knowledge Management (CIKM) 
* Purohit, S., Holder, L., & Choudhury, S. (2017). [Application-Specific Graph Sampling for Frequent Subgraph Mining and Community Detection](publications/2017_ieee_bigdata.pdf). In IEEE International Conference on Big Data.

* Choudhury, S., Agarwal, K., Purohit, S., Zhang, B., Pirrung, M., Smith, W. and Thomas, M., 2017, April. [Nous: Construction and querying of dynamic knowledge graphs](https://arxiv.org/pdf/1606.02314.pdf). In Data Engineering (ICDE), 2017 IEEE 33rd International Conference on (pp. 1563-1565). IEEE.
* Zhang, B., Choudhury, S., Hasan, M.A., Ning, X., Agarwal, K., Purohit, S. and Cabrera, P.P., 2016. [Trust from the past: Bayesian personalized ranking based link prediction in knowledge graphs.](https://arxiv.org/pdf/1601.03778). In 2016 SIAM Data Mining Workshop on Mining Networks and Graphs
* Chen, P.Y., Choudhury, S. and Hero, A.O., 2016, March. [Multi-centrality graph spectral decompositions and their application to cyber intrusion detection](publications/2016_icassp.pdf). In Acoustics, Speech and Signal Processing (ICASSP), 2016 IEEE International Conference on (pp. 4553-4557). IEEE.
* Choudhury, S., Rodriguez, L., Curtis, D., Oler, K., Nordquist, P., Chen, P.Y. and Ray, I., 2015, October. [Action recommendation for cyber resilience.](publications/2015_safeconfig.pdf) In Proceedings of the 2015 Workshop on Automated Decision Making for Active Cyber Defense (pp. 3-8). ACM.
* Choudhury S, L Holder, G Chin, K Agarwal, JT Feo. 2015. [A Selectivity based approach to Continuous Pattern Detection in Streaming Graphs](publications/2015_streamworks_edbt.pdf), In Proceedings of the 18th International Conference on Extending Database Technology.  [CODE](https://github.com/streaming-graphs/StreamWorks)
* Ray, A., Holder, L. and Choudhury, S., 2014, August. [Frequent Subgraph Discovery in Large Attributed Streaming Graphs](http://www.jmlr.org/proceedings/papers/v36/ray14.pdf). In BigMine/Special Issue of Journal of Machine Learning Research (pp. 166-181).
* Lieberman, M.D., Choudhury, S., Hughes, M., Patrone, D., Hider Jr, R.T., Piatko, C.D., Chapman, M., Marple, J.P. and Silberberg, D., 2014, June. [Parasol: An Architecture for Cross-Cloud Federated Graph Querying](publications/2014_parasol.pdf). In Proceedings of Workshop on Data analytics in the Cloud (pp. 1-4). ACM.
* Morari, A., Castellana, V.G., Villa, O., Tumeo, A., Weaver, J., Haglin, D., Choudhury, S. and Feo, J., 2014. [Scaling semantic graph databases in size and performance](publications/2014_ieee_micro.pdf). IEEE Micro, 34(4), pp.16-26.
* Joslyn, C., Choudhury, S., Haglin, D., Howe, B., Nickless, B. and Olsen, B., 2013, June. [Massive scale cyber traffic analysis: a driver for graph database research](publications/2013_grades.pdf). In First International Workshop on Graph Data Management Experiences and Systems (p. 3). ACM.

