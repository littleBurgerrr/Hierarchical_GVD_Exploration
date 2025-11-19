# Hierarchical_GVD_exploration

**Paper has been submitted to IEEE Transactions on Automation Science and Engineering (TASE). We will release our code upon acceptance.** 🚀🚀🚀

**Abstract**: Topological maps are more suitable than metric maps for robotic exploration tasks. However, real-time updating of accurate and detail-rich environmental topological maps remains a challenge. This paper presents a topological map updating method based on the Generalized Voronoi Diagram (GVD). First, the newly observed areas are denoised to avoid low-efficiency GVD nodes misleading the topological structure. Subsequently, a multi-granularity hierarchical GVD generation method is designed to control the sampling granularity at both global and local levels. This not only ensures the accuracy of the topological structure but also enhances the ability to capture detail features, reduces the probability of path backtracking, and ensures no overlap between GVDs through the maintenance of a coverage map, thereby improving GVD utilization efficiency. Second, a node clustering method with connectivity constraints and a connectivity method based on a switching mechanism are designed to avoid the generation of unreachable nodes and erroneous nodes caused by obstacle attraction. A special cache structure is used to store all connectivity information, thereby improving exploration efficiency. Finally, to address the issue of frontiers misjudgment caused by obstacles within the scope of GVD units, a frontiers extraction method based on morphological dilation is designed to effectively ensure the reachability of frontiers. On this basis, a lightweight cost function is used to assess and switch to the next viewpoint in real time. This allows the robot to quickly adjust its strategy when signs of path backtracking appear, thereby escaping the predicament and increasing exploration flexibility. The performance of system for exploration task is verified through ablation experiments and comparative tests with SOTA methods.

<img width="995" height="657" alt="image" src="https://github.com/user-attachments/assets/7fccb318-b35f-40b6-b162-eeae1b6db9be" />
Fig.1 Graphic abstract

\



<img width="1441" height="439" alt="image" src="https://github.com/user-attachments/assets/9b6b33e8-4647-4dcc-8f30-da147dd19f4f" />

Fig.2 Pipeline
