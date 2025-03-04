# <p align=center>Awesome Transformer in Transportation 🚦 🚗 🚕 🛣️ 🚆 🛩️ ⛵️</p>


<div align=center>

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) 
<!-- ![GitHub stars](https://img.shields.io/github/stars/cocacola-lab/Awesome-Transformer-for-Transportation.svg?color=red&style=for-the-badge) 
![GitHub forks](https://img.shields.io/github/forks/cocacola-lab/Awesome-Transformer-for-Transportation.svg?color=yellow&style=for-the-badge) 
![GitHub activity](https://img.shields.io/github/last-commit/cocacola-lab/Awesome-Transformer-for-Transportation?style=for-the-badge) 
![visitors](https://visitor-badge.glitch.me/badge?page_id=cocacola-lab/Awesome-Transformer-for-Transportation)  -->


A collection of resources on Transformer in Transportation.

</div>

<h4 align="left">
    <p>
        <b>English</b> |
        <a href="https://github.com/cocacola-lab/Awesome-Transformer-in-Transportation/blob/main/README_zh.md">中文</a>
    <p>
</h4>

## <span id="head-content"> *Content* </span>
* - [ ] [1. Description](#head1)
* - [ ] [2. Paper With Code](#head2)
  * - [ ] [Traffic Forecasting](#head-Traffic-Forecasting)
  * - [ ] [Traffic Control](#head-Traffic-Control)
  * - [ ] [Public Transit Management](#head-Public-Transit-Management)
  * - [ ] [Analysis of Public Feedback](#head-Analysis-of-Public-Feedback)
  * - [ ] [Dissemination of Real-Time Information](#head-Dissemination-of-Real-Time-Information)
  * - [ ] [Co-pilot for Drivers](#head-Co-pilot-for-Drivers)
  * - [ ] [Autonomous Vehicle Control](#head-Autonomous-Vehicle-Control)
  * - [ ] [Motion Planning and Execution](#head-Motion-Planning-and-Execution)
  * - [ ] [Bird's Eye View (BEV) Perception](#head-Bird's-Eye-View-(BEV)-Perception)
  * - [ ] [Route Optimization](#head-Route-Optimization)
  * - [ ] [Accident Prediction](#head-Accident-Prediction)
  * - [ ] [Safety-Critical Event Detection](#head-Safety-Critical-Event-Detection)
  * - [ ] [Traffic Scenario Identificationg](#head-Traffic-Scenario-Identification)
  * - [ ] [Other Applications](#head-Other-Applications)
* - [ ] [3. Survey Paper](#head3)
* [*Contact Me*](#head4)

## <span id="head1"> *1. Description* </span>
>🐌 Markdown Format:
>
> * (Conference/Journal Year) **Title**, First Author et al. [[Paper](URL)] [[Code](URL)] [[Project](URL)] <br/>
> * (Conference/Journal Year) [💬Topic] **Title**, First Author et al. [[Paper](URL)] [[Code](URL)] [[Project](URL)]
>     * (Optional) ```🌱``` or ```📌 ```
>     * (Optional) 🚀 or 👑 or 📚

* 🌱: Novel idea
* 📌: The first...
* 🚀: State-of-the-Art approach
* 👑: Widely-used model
* 📚：New Tasks/Dataset/Benchmark



## <span id="head2"> *2. Paper With Code* </span>

   * <span id="head-Traffic-Forecasting"> **Traffic Forecasting** </span> **[       «🎯Back To Top»       ](#)**
       ```Accurate traffic forecasting is the cornerstone of intelligent transportation systems (ITS). By predicting traffic conditions, transportation authorities can optimize traffic flow, reduce congestion, and improve overall efficiency. Transformers are proving to be highly effective in analyzing historical traffic data and predicting future traffic patterns. This Traffic Forecasting task, in turn, enables proactive measures like dynamic traffic management, route optimization, and real-time traveler information dissemination.```
      * (2025 SENSORS) **Spatial–Temporal Transformer Networks for Traffic Flow Forecasting Using a Pre-Trained Language Model**, J Ma et al. [[Paper](https://www.mdpi.com/1424-8220/24/17/5502)]
        * ```This work can capture complex spatial-temporal dependencies in traffic data, considering factors such as road networks, weather conditions, and historical trends, leads to more accurate and reliable predictions. ```
      * (2024 Communications in Transportation Research) **Explainable Traffic Flow Prediction with Large Language Models**, Xusen Guo et al. [[Paper](https://www.sciencedirect.com/science/article/pii/S2772424724000337)] [[Code](https://github.com/Guoxs/xTP-LLM)] 
        * ```MLLMs can analyze multimodal traffic data, including time series, images, and videos, to generate interpretable traffic flow predictions. ```      
       * (2024) **TransGPT: Multi-modal Generative Pre-trained Transformer for Transportation**, Not specified. [[Paper](https://arxiv.org/pdf/2402.07233)] [[Code](Not found)]  
         * ```Proposes a multimodal transformer framework for transportation data analysis, integrating text, image, and sensor data streams.```
      * (2023) **Deep Learning Transformer Models for Building a Comprehensive and Real-time Trauma Observatory: Development and Validation Study**, Not specified. [[Paper](https://pmc.ncbi.nlm.nih.gov/articles/PMC11041521/)] [[Code](Not found)]  
        * ```Develops transformer-based models for real-time trauma monitoring systems with clinical validation.```
          
        * (AAAI 2023) BigST: Linear Complexity Spatio-Temporal Graph Neural Network for Traffic Forecasting on Large-Scale Road Networks, Zhaoyang Meng et al. [[Paper](https://dl.acm.org/doi/pdf/10.14778/3641204.3641217)] [[Code](https://github.com/usail-hkust/BigST)]  
          * ```The block-based spatiotemporal graph partitioning algorithm reduces the modeling complexity from O(N²) to linear. It achieves parallel computation on millions of nodes through dynamic graph partitioning. This work also introduces the first theoretical framework proving that spatiotemporal models can operate at linear complexity, and releases the open-source synthetic dataset GlobalRoad-1M, which includes complex road topologies and simulated traffic accident labels.```

       * (AAAI 2023) [💬Unified Model] Trafformer: Unify Time and Space in Traffic Prediction, Yuqi Li et al. [[Paper](https://ojs.aaai.org/index.php/AAAI/article/view/25980)] [[code](Not Found)]
          * ```The spatiotemporal joint attention matrix fuses the spatial adjacency matrix and the temporal similarity matrix into a single attention weight.```

       * (KDD 2024) STGformer: Efficient Spatiotemporal Graph Transformer for Traffic Forecasting, Weiqi Chen et al. [[Paper](https://arxiv.org/abs/2410.00385)] [[Code](https://github.com/Dreamzz5/STGformer)]  
          * ```Kernel-approximated linear attention leverages random feature mapping to reduce the Softmax computation complexity from O(N²) to O(N).```
       * (NeurIPS 2023) STAEformer: Spatio-Temporal Adaptive Embedding Makes Vanilla Transformer SOTA for Traffic Forecasting, Shen Fang et al. [[Paper](https://arxiv.org/abs/2308.10425)] [[Code](https://github.com/XDZhelheim/STAEformer)]  

       * (AAAI 2023) PDFormer: Propagation Delay-Aware Dynamic Long-Range Transformer for Traffic Flow Prediction, Jingyuan Wang et al. [[Paper](https://arxiv.org/abs/2301.07945)] [[Code](https://github.com/BUAABIGSCity/PDFormer)]
         * ```The semantic propagation mask generates a dynamic delay graph via k-Shape clustering to quantify traffic wave propagation time; it is the first deep learning model to incorporate the physical propagation delay of traffic flow.```

       * (NeurIPS 2024) Spatial-Temporal-Decoupled Masked Pre-training for Spatiotemporal Forecasting, Yushun Jiang et al. [[Paper](https://arxiv.org/abs/2312.00516)] [[code](https://github.com/Jimmy-7664/STD-MAE)]  
         * ``` Applies masking separately along the spatial and temporal dimensions. This allows the model to independently capture long-range spatial dependencies and temporal heterogeneity, effectively mitigating the 'spatiotemporal illusion' caused by short input windows in traditional models, and thereby generally enhancing the performance of downstream spatiotemporal predictors.```

       * (Neuromputing 2022) Meta Graph Transformer: A Novel Framework for Spatial–Temporal Traffic Prediction, Jingyuan Wang et al. [[Paper](https://www.sciencedirect.com/science/article/pii/S0925231221018725?via%3Dihub)] [[Code](https://github.com/lonicera-yx/MGT)] 
         * ```The meta-graph generator dynamically constructs spatiotemporal dependencies based on node meta-features (such as POI density and road hierarchy).```

       * (ICDE 2023) Self-Supervised Spatial-Temporal Bottleneck Attentive Network for Efficient Long-term Traffic Forecasting, 贡乐天 et al.[[paper](https://ieeexplore.ieee.org/document/10184658)][[code](https://github.com/guoshnBJTU/SSTBAN)] 
         * ```A self-supervised spatiotemporal bottleneck attention network is proposed that integrates self-supervised learning with a lightweight attention mechanism, significantly enhancing both the accuracy and efficiency of long-term traffic forecasting.```

       * (2020 《Transactions in GIS》) Traffic Transformer: Capturing the Continuity and Periodicity of Time Series for Traffic Forecasting, Yuxuan Liang et al. [[Paper](https://onlinelibrary.wiley.com/doi/full/10.1111/tgis.12644)]  [[code](Not Found)]
        * ```The Lipschitz constraint module forces the change rate between predictions of adjacent time steps to be no greater than the maximum fluctuation in historical data; this work is the first to introduce differential equation stability theory into spatiotemporal modeling.```

       * (SIGSPATIAL 2021) DetectorNet: Transformer-enhanced Spatial Temporal Graph Neural Network for Traffic Prediction, Zhang et al. [[Paper](https://arxiv.org/abs/2111.00869)] [[Code](Not Found)] 
         * ```The multi-view spatiotemporal modeling approach combines transformer-based multi-perspective temporal attention (covering short, medium, and long cycles) with dynamic graph convolution.```
        
       * (KDD 2024) [💬LLM] UrbanGPT: Spatio-Temporal Large Language Models, Cheng Long et al. [[Paper](https://arxiv.org/abs/2403.00813)] [[code](https://github.com/HKUDS/UrbanGPT)]  
        * ```The spatiotemporal vocabulary encodes road network topology into a token sequence to support bidirectional conversion between GPS coordinates and semantic locations; it is the first multimodal large model in the traffic domain that supports prediction tasks controlled via text instructions.```

       * (2023 《Expert Systems with Applications》) Spatio-temporal Graph Mixformer for Traffic Forecasting, Lablack 和 Shen. [[paper](https://www.sciencedirect.com/science/article/pii/S0957417423007832?via%3Dihub)][[code](https://github.com/Mouradost/STGM)]
         * ```Building on the Transformer, the model introduces temporal dilated convolution, multi-head attention, and an estimator module to effectively capture dynamic spatiotemporal dependencies in traffic data. It fuses multi-perspective information through a hybrid module, achieving both efficient and accurate traffic flow forecasting.```

       * (2025) T-Graphormer: Using Transformers for Spatiotemporal Forecasting, Bai and Liu. [[Paper](https://www.arxiv.org/abs/2501.13274)] [[代码](https://github.com/rdh1115/T-Graphormer)]
         * ```Extends Graphormer into the temporal dimension. Through a global self-attention mechanism, every node in the graph simultaneously captures dependencies in both space and time, reducing reliance on predefined spatiotemporal inductive biases. ```


   * <span id="head-Traffic-Control"> **Traffic Control** </span> **[       «🎯Back To Top»       ](#)**
       ```LLMs can act as intelligent traffic controllers, optimizing traffic flow at intersections by analyzing real-time data and providing context-aware decisions to drivers, infrastructure, and autonomous vehicles.```
      * (2025) **Large Language Models (LLMs) as Traffic Control Systems at Urban Intersections: A New Paradigm**, Not specified. [[Paper](https://www.mdpi.com/2624-8921/7/1/11)] [[Code](Not found)]  
        * ```Pioneering study implementing LLMs for real-time urban intersection management through multimodal data processing.```
     
     * (IJCAI 2024)  X-Light: Cross-City Traffic Signal Control Using Transformer on Transformer as Meta Multi-Agent Reinforcement Learner, Jiang et al. [[Paper](https://arxiv.org/abs/2404.12090)] [[code](https://github.com/jianghaoyuan1994/X-Light)]
          * ``Propose a Transformer-on-Transformer architecture: the lower-level Transformer aggregates multi-dimensional MDP information (state/action/reward) from intersections, while the upper-level Transformer learns cross-city meta-decision patterns.```

   * (KDD 2023) TransformerLight: A Novel Sequence Modeling Based Traffic Signaling Mechanism via Gated Transformer, Wu et al. [[Paper](https://dl.acm.org/doi/10.1145/3580305.3599530)] [[code](https://github.com/Smart-Trafficlab/TransformerLight)]
          * ```Directly generate optimal signal phases through gated Transformer blocks, thereby bypassing the dynamic programming and value function estimation of traditional reinforcement learning, and achieving state-of-the-art performance on real road networks.```

   * <span id="head-Public-Transit-Management"> **Public Transit Management** </span> **[       «🎯Back To Top»       ](#)**
       ```LLMs can enhance public transit systems by optimizing route planning, reducing wait times, and providing personalized travel assistance to passengers.```
      * (2025) **Exploring the Potential of Large Language Models in Public Transportation: San Antonio Case Study**, Not specified. [[Paper](https://arxiv.org/abs/2501.03904)] [[Code](Not found)]  
        * ```Case study demonstrating LLM applications in public transit scheduling and demand forecasting.```


   * <span id="head-Analysis-of-Public-Feedback"> **Analysis of Public Feedback** </span> **[       «🎯Back To Top»       ](#)**
       ```LLMs can analyze public complaints and suggestions related to transportation systems, helping agencies align their services with public demands and safety needs.```
      * (2023) **Use of Large Language Models to Improve Transportation Services**, Not specified. [[Paper](https://www.morgan.edu/national-transportation-center/the-smarter-center-(2023-2029)/research/use-of-large-language-models-to-improve-transportation-services)] [[Code](Not found)]  
        * ```Institutional research on LLM deployment strategies for transportation service optimization.```

   * <span id="head-Dissemination-of-Real-Time-Information"> **Dissemination of Real-Time Information** </span> **[       «🎯Back To Top»       ](#)**
       ```LLMs can automate updates to transit system alerts on social media, provide personalized trip recommendations, and offer clear and tailored responses to policy-related user queries.```
      * (2024) **Leveraging Large Language Models for Enhancing Public Transit Services**, Not specified. [[Paper](https://arxiv.org/html/2410.14147v1)] [[Code](Not found)]  
        * ```Proposes LLM-based framework for real-time transit service adjustment using passenger feedback analysis.```


   * <span id="head-Co-pilot-for-Drivers"> **Co-pilot for Drivers** </span> **[       «🎯Back To Top»       ](#)** 
       ```LLMs can function as co-pilots for drivers, providing real-time coaching, warnings, and directives to reinforce positive driving behaviors and enhance safety.```
      * (2024) **Fusing Pretrained LLMs And LGMs With Driving Data To Improve Road Safety**, Forbes Tech Council. [[Paper](https://www.forbes.com/councils/forbestechcouncil/2024/11/08/fusing-pretrained-llms-and-lgms-with-driving-data-to-improve-road-safety/)] [[Code](Not found)]  
        * ```Industry perspective on integrating language and geometric models for advanced driver assistance systems.```


   * <span id="head-Autonomous-Vehicle-Control"> **Autonomous Vehicle Control** </span> **[       «🎯Back To Top»       ](#)**

       ```Companies like Tesla and Waymo are utilizing Transformer algorithms in self-driving cars for tasks like object detection, route optimization, and decision-making.```
      * (2025) **Transformer Algorithms Revolutionize AI: From Natural Language to Self-Driving Cars**, James Santana. [[Paper](https://medium.com/@jamesasantana/transformer-algorithms-revolutionize-ai-from-natural-language-to-self-driving-cars-cd0da43eff25)] [[Code](Not found)]  
        * ```Exploring multi-modal fusion strategies in autonomous driving using the Transformer architecture, and proposing a dynamic attention allocation mechanism.```
      * (2025) **Top LLM Development Companies**, SoluLab. [[Paper](https://www.solulab.com/top-llm-development-companies/)] [[Code](Not found)]  
        * ```Industry Analysis Report: A Comparison of the Technical Roadmaps of LLM Development Companies in the Transportation Sector in 2025. MLLMs can enhance the control systems of autonomous vehicles by integrating textual analysis with real-time video and audio inputs to facilitate ```   
      * (2024) **A Survey of Vision Transformers in Autonomous Driving**, Not specified. [[Paper](https://arxiv.org/html/2403.07542v1)] [[Code](Not found)]  
        * ```Systematic comparison of ViT and Swin Transformer architectures in lane detection tasks.```


   * <span id="head-Motion-Planning-and-Execution"> **Motion Planning and Execution** </span> **[       «🎯Back To Top»       ](#)**

       ```In autonomous vehicles, Transformers are employed for motion planning, transforming sensor data into calculated decisions that guide the vehicle's controller in shaping the optimal trajectory.```
      * (2024) **Transformers: Autopilot's Secret Weapon**, EE Times Editorial Team. [[Paper](https://www.eetimes.eu/transformers-autopilots-secret-weapon/)] [[Code](Not found)]  
        * ```Industry report analyzing hardware acceleration solutions for Transformers in automotive system chip design.```


     * <span id="head-Bird's-Eye-View-(BEV)-Perception"> **Bird's Eye View (BEV) Perception** </span> **[       «🎯Back To Top»       ](#)**
       ```Transformer are being used for "Bird's Eye View" (BEV) perception in autonomous driving. Tasks, for example, Lane Detection, are also included in BEV perception.``
      * (2023) **Accelerating Transformer Neural Networks for Autonomous Driving**, Ambarella Research. [[Paper](https://www.ambarella.com.tw/blog/accelerating-transformer-neural-networks-for-autonomous-driving/)] [[Code](Not found)]  
        * ```Proposed a Transformer model compression scheme based on FPGA for real-time inference on on-board systems.```
      * (2023 WACV) **Bevsegformer: Bird's eye view semantic segmentation from arbitrary camera rigs**, Peng, Lang, et al. [[Paper](https://openaccess.thecvf.com/content/WACV2023/papers/Peng_BEVSegFormer_Birds_Eye_View_Semantic_Segmentation_From_Arbitrary_Camera_Rigs_WACV_2023_paper.pdf)] [[Code](https://)] 
        * ```BEVSegFormer employ cross-attention mechanisms and CNNs in conjunction with Transformers to accurately detect lane markings and enhance BEV features, contributing to safer and more reliable autonomous navigation. ```
      * (2022 ECCV) **Persformer: 3d lane detection via perspective transformer and the openlane benchmark**, Chen, Li, et al. [[Paper](https://link.springer.com/chapter/10.1007/978-3-031-19839-7_32)] [[Code](https://)] 
        * ```PersFormer employ cross-attention mechanisms and CNNs in conjunction with Transformers to accurately detect lane markings and enhance BEV features, contributing to safer and more reliable autonomous navigation. ```


     * <span id="head-Route-Optimization"> **Route Optimization** </span> **[       «🎯Back To Top»       ](#)**
       ```Transformers are integrated for robot route optimization in smart logistics.```
      * (2025) **Multimodal LLM for Intelligent Transportation Systems**, Not specified. [[Paper](https://arxiv.org/html/2412.11683v1)] [[Code](Not found)]  
       ```Propose a cross-modal alignment loss function to address the semantic gap among text, image, and sensor data.```
      * (2023) **TrafFormer: A Transformer Model for Predicting Long-term Traffic**, Not specified. [[Paper](https://arxiv.org/abs/2302.12388)] [[Code](Not found)]  
        * ```A 72-hour traffic flow prediction framework for urban road networks incorporating spatiotemporal attention mechanisms.```
      * (2023) **Transformers for Trajectory Optimization with Application to Spacecraft Rendezvous**, Not specified. [[Paper](https://arxiv.org/html/2310.13831v3)] [[Code](Not found)]  
        * ```Extends transformer architecture to optimize spacecraft trajectories, demonstrating robustness in orbital mechanics.```
      * (2025) **Transformer Algorithms Revolutionize AI: From Natural Language to Self-Driving Cars**, James Santana. [[Paper](https://medium.com/@jamesasantana/transformer-algorithms-revolutionize-ai-from-natural-language-to-self-driving-cars-cd0da43eff25)] [[Code](Not found)]  
        * ```Discusses multi-modal fusion strategies of transformers in autonomous driving systems.```


     * <span id="head-Accident-Prediction"> **Accident Prediction** </span> **[       «🎯Back To Top»       ](#)**
       ```Predict accidents by analyzing various factors such as weather conditions, time of day, and driver behavior..```
      * (2024) **LLM Multimodal Traffic Accident Forecasting**, Not specified. [[Paper](https://www.mdpi.com/1424-8220/23/22/9225)] [[Code](Not found)]  
         * ```A multimodal accident prediction system integrating weather data and traffic cameras.```
      * (2024) **Data-Driven Traffic Management with LLMs**, RapidCanvas Team. [[Paper](https://www.rapidcanvas.ai/blogs/data-driven-traffic-management-leveraging-llms-for-real-time-decision-making)] [[Code](Not found)]  
        * ```Business Case Study: The Deployment Effect of LLM in Optimizing New York City Traffic Signals.```
        

     * <span id="head-Safety-Critical-Event-Detection"> **Safety-Critical Event Detection** </span> **[       «🎯Back To Top»       ](#)**
       ```MLLMs can analyze naturalistic driving videos to identify and understand safety-critical events, such as sudden changes in traffic patterns, unexpected obstacles, and potential collisions.```
          
     * <span id="head-Traffic-Scenario-Identification"> **Traffic Scenario Identification** </span> **[       «🎯Back To Top»       ](#)**
        ```Identify and define relevant scenario```
        * (2021 IEEE Intelligent Vehicles Symposium) **Novelty Detection and Analysis of Traffic Scenario Infrastructures in the Latent Space of a Vision Transformer-Based Triplet Autoencoder**, Jonas Wurst et al. [[Paper](https://ieeexplore.ieee.org/abstract/document/9575730)] [[Code](https://github.com/JWTHI/ViTAL-SCENE)] 
          * ```📚  This paper provides the triplet autoencoder architecture using vision transformer as encoder. ```  

  <!-- * <span id="head-Beyond-Transformer"> **Beyond Transformer**  </span> **[       «🎯Back To Top»       ](#)**
      * (arXiv preprint 2021) **Container: Context Aggregation Network**, Peng Gao et al. [[Paper](https://arxiv.org/pdf/2106.01401.pdf)]
        * ```🌱  A unified view of popular architectures for visual inputs – CNN, Transformer and MLP-mixer. ```
        * ```🌱  A novel network block – CONTAINER, which uses a mix of static and dynamic affinity matrices via learnable parameters. ```
        * 📚  Image Classification, Object Detection, Instance Segmentation,  Self-Supervised Representation Learning -->
      



## <span id="head3"> *3. [Survey](https://github.com/Yutong-Zhou-cv/Awesome-Survey-Papers)* </span> **[       «🎯Back To Top»       ](#)**

[**Transformers in Transportation: A Survey**](https://arxiv.org) 
<!-- (IJCAI'23 Survey Track) -->

<!-- [Q](https://), [Jun](https://) and [Liang Sun](https://). -->

#### If you find this repository helpful for your work, please kindly cite our survey paper.

```bibtex
Content Coming Soon

This is currently under active development. Check back soon for exciting updates and detailed information.

```

**Other Related Survey and Review:**

*  **A Comprehensive Survey on Applications of Transformers for Deep Learning Tasks** [[v1](https://arxiv.org/abs/2306.07303)](2023.06.11)
*  [🧩Segmentation] **Transformer-Based Visual Segmentation: A Survey** [[Awesome Repo](https://github.com/lxtGH/Awesome-Segmenation-With-Transformer)] [[v1](https://arxiv.org/abs/2304.09854)](2023.04.19)
*  [🖊GNN] **A Survey on Graph Neural Networks and Graph Transformers in Computer Vision: A Task-Oriented Perspective** [[v1](https://arxiv.org/abs/2209.13232)](2022.09.27)
*  [🏃‍Action Recognition] **Vision Transformers for Action Recognition: A Survey** [[v1](https://arxiv.org/abs/2209.05700)](2022.09.13)
*  [🌌Remote Sensing] **Transformers in Remote Sensing: A Survey** [[v1](https://arxiv.org/abs/2209.01206)](2022.09.02)


  
<!--## Stargazers over time
[![Stargazers over time](https://starchart.cc/Yutong-Zhou-cv/Awesome-Transformer-in-CV.svg)](https://starchart.cc/Yutong-Zhou-cv/Awesome-Transformer-in-CV)-->

<!--#comments * (arXiv preprint 2021) **Title**, firstauthor et al. [[Paper]()] [[Code]()] * ```🌱 tips ```-->

<!--#comments For fold: <details><summary> <b>Name</b> </summary> ... </details> -->

## <span id="head4"> *Contact Me* </span>

* Wenjuan Han in [CoLa Lab @ Beijing Jiaotong University.](https://github.com/cocacola-lab)

* Feel free to contact (💌: <wjhan@@bjtu.edu.cn>).
* Thanks to [YutongZhou's Github template](https://github.com/Yutong-Zhou-cv/Awesome-Transformer-in-CV.git).
