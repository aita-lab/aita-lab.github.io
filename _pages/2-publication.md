---
layout: page
title: Publication
permalink: /publication/
# image: Bib_Network.png
description: Academic publications and other types of research output from the AI Technology and Application Research Lab at the FPT University, Ho Chi Minh Campus
toc: true
toc_sticky: true
toc_label: "Table of Contents"
---
<h5>Table of Contents</h5>
* TOC
{:toc}

---

<script async src="https://badge.dimensions.ai/badge.js" charset="utf-8"></script>

<div class="aita-network-wrapper" style="margin-bottom: 40px; margin-top: 20px;">
  <div id="author-network" style="width: 100%; height: 500px; background-color: #f8f9fa; border-radius: 12px; border: 1px solid #eaebed; box-shadow: 0 4px 12px rgba(0,0,0,0.05); margin-bottom: 20px;"></div>
</div>

<script src="https://cdn.jsdelivr.net/npm/echarts@5.5.0/dist/echarts.min.js"></script>
<script>
  document.addEventListener("DOMContentLoaded", function() {
    var chartDom = document.getElementById('author-network');
    var myChart = echarts.init(chartDom);
    var option;

    // Data extracted from your recent publications
    const graphData = {
      nodes: [
        { id: '0', name: 'Duc Ngoc Minh Dang', symbolSize: 60, itemStyle: { color: '#ed8428' } },
        { id: '1', name: 'Nhut Minh Nguyen', symbolSize: 45, itemStyle: { color: '#0891b2' } },
        { id: '2', name: 'Phuong-Nam Tran', symbolSize: 45, itemStyle: { color: '#0891b2' } },
        { id: '3', name: 'Nhat Truong Pham', symbolSize: 35, itemStyle: { color: '#059669' } },
        { id: '4', name: 'Duc Tai Phan', symbolSize: 35, itemStyle: { color: '#7c3aed' } },
        { id: '5', name: 'Thanh Trung Nguyen', symbolSize: 35, itemStyle: { color: '#db2777' } },
        { id: '6', name: 'Thu Thuy Le', symbolSize: 30, itemStyle: { color: '#d97706' } },
        { id: '7', name: 'Anh Khoa Tran', symbolSize: 30, itemStyle: { color: '#4b5563' } },
        { id: '8', name: 'Khang Phuc Nguyen', symbolSize: 25, itemStyle: { color: '#8b5cf6' } },
        { id: '9', name: 'Linh Le', symbolSize: 25, itemStyle: { color: '#ec4899' } },
        { id: '10', name: 'Choong Seon Hong', symbolSize: 25, itemStyle: { color: '#3b82f6' } },
        { id: '11', name: 'Minh Trung Nguyen', symbolSize: 25, itemStyle: { color: '#10b981' } },
        { id: '12', name: 'Lam Thanh Hien', symbolSize: 25, itemStyle: { color: '#f59e0b' } },
        { id: '13', name: 'Vo Phuc Tinh', symbolSize: 25, itemStyle: { color: '#6366f1' } },
        { id: '14', name: 'Nguyen Hoang Nam', symbolSize: 25, itemStyle: { color: '#14b8a6' } },
        { id: '15', name: 'Duong Thanh Tran', symbolSize: 25, itemStyle: { color: '#ef4444' } },
        { id: '16', name: 'Nguyen Doan Hieu Nguyen', symbolSize: 30, itemStyle: { color: '#f97316' } },
        { id: '17', name: 'Trung Thanh Pham', symbolSize: 30, itemStyle: { color: '#06b6d4' } },
        { id: '18', name: 'Thuy-Duong Thi Vu', symbolSize: 25, itemStyle: { color: '#eab308' } },
        { id: '19', name: 'Cuong Tuan Nguyen', symbolSize: 25, itemStyle: { color: '#a855f7' } },
        { id: '20', name: 'Hanh Dang-Ngoc', symbolSize: 30, itemStyle: { color: '#ec4899' } },
        { id: '21', name: 'Quang Nhan Hoang', symbolSize: 25, itemStyle: { color: '#10b981' } },
        { id: '22', name: 'Minh Tri Pham', symbolSize: 25, itemStyle: { color: '#14b8a6' } },
        { id: '23', name: 'Nam Van Hai Phan', symbolSize: 30, itemStyle: { color: '#3b82f6' } },
        { id: '24', name: 'Vo Duc Tai', symbolSize: 25, itemStyle: { color: '#6366f1' } },
        { id: '25', name: 'Duc-Hieu Hoang', symbolSize: 25, itemStyle: { color: '#f43f5e' } },
        { id: '26', name: 'Dinh Thuan Nguyen', symbolSize: 25, itemStyle: { color: '#8b5cf6' } }
      ],
      links: [
        // From 0 (PI: Duc Ngoc Minh Dang)
        { source: '0', target: '1' },
        { source: '0', target: '2' },
        { source: '0', target: '3' },
        { source: '0', target: '4' },
        { source: '0', target: '5' },
        { source: '0', target: '6' },
        { source: '0', target: '7' },
        { source: '0', target: '8' },
        { source: '0', target: '9' },
        { source: '0', target: '10' },
        { source: '0', target: '11' },
        { source: '0', target: '12' },
        { source: '0', target: '13' },
        { source: '0', target: '14' },
        { source: '0', target: '15' },
        { source: '0', target: '16' },
        { source: '0', target: '17' },
        { source: '0', target: '18' },
        { source: '0', target: '19' },
        { source: '0', target: '20' },
        { source: '0', target: '21' },
        { source: '0', target: '22' },
        { source: '0', target: '23' },
        { source: '0', target: '24' },
        { source: '0', target: '25' },
        { source: '0', target: '26' },

        // From 1 (Nhut Minh Nguyen)
        { source: '1', target: '2' },
        { source: '1', target: '3' },
        { source: '1', target: '4' },
        { source: '1', target: '5' },
        { source: '1', target: '6' },
        { source: '1', target: '7' },
        { source: '1', target: '8' },
        { source: '1', target: '9' },
        { source: '1', target: '10' },
        { source: '1', target: '11' },
        { source: '1', target: '12' },
        { source: '1', target: '16' },
        { source: '1', target: '25' },
        { source: '1', target: '26' },

        // From 2 (Phuong-Nam Tran)
        { source: '2', target: '3' },
        { source: '2', target: '4' },
        { source: '2', target: '5' },
        { source: '2', target: '6' },
        { source: '2', target: '8' },
        { source: '2', target: '9' },
        { source: '2', target: '10' },
        { source: '2', target: '11' },
        { source: '2', target: '15' },
        { source: '2', target: '16' },
        { source: '2', target: '17' },
        { source: '2', target: '18' },
        { source: '2', target: '19' },
        { source: '2', target: '20' },

        // From 3 (Nhat Truong Pham)
        { source: '3', target: '4' },
        { source: '3', target: '5' },
        { source: '3', target: '6' },
        { source: '3', target: '8' },
        { source: '3', target: '9' },
        { source: '3', target: '10' },
        { source: '3', target: '11' },
        { source: '3', target: '16' },

        // From 4 (Duc Tai Phan)
        { source: '4', target: '5' },
        { source: '4', target: '6' },
        { source: '4', target: '7' },
        { source: '4', target: '8' },
        { source: '4', target: '9' },
        { source: '4', target: '10' },

        // From 5 (Thanh Trung Nguyen)
        { source: '5', target: '6' },
        { source: '5', target: '7' },
        { source: '5', target: '9' },
        { source: '5', target: '11' },
        { source: '5', target: '25' },
        { source: '5', target: '26' },

        // From 6 (Thu Thuy Le)
        { source: '6', target: '7' },
        { source: '6', target: '12' },
        { source: '6', target: '16' },

        // From 13 (Vo Phuc Tinh)
        { source: '13', target: '14' },
        { source: '13', target: '7' },

        // From 15 (Duong Thanh Tran)
        { source: '15', target: '16' },
        { source: '15', target: '17' },
        { source: '15', target: '18' },
        { source: '15', target: '19' },
        { source: '15', target: '20' },

        // From 16 (Nguyen Doan Hieu Nguyen)
        { source: '16', target: '17' },
        { source: '16', target: '18' },
        { source: '16', target: '19' },
        { source: '16', target: '20' },
        { source: '16', target: '23' },

        // From 17 (Trung Thanh Pham)
        { source: '17', target: '18' },
        { source: '17', target: '19' },
        { source: '17', target: '20' },

        // From 18 (Thuy-Duong Thi Vu)
        { source: '18', target: '19' },
        { source: '18', target: '20' },

        // From 19 (Cuong Tuan Nguyen)
        { source: '19', target: '20' },

        // From 20 (Hanh Dang-Ngoc)
        { source: '20', target: '24' },

        // From 21 (Quang Nhan Hoang)
        { source: '21', target: '22' },

        // From 25 (Duc-Hieu Hoang)
        { source: '25', target: '26' }
      ]
    };

    option = {
      title: {
        text: 'Lab Co-Authorship Network',
        subtext: 'Drag nodes to interact',
        top: '10',
        left: '10',
        textStyle: { fontFamily: 'Inter, sans-serif', color: '#2b2b2b' }
      },
      tooltip: {
        formatter: '{b}'
      },
      animationDurationUpdate: 1500,
      animationEasingUpdate: 'quinticInOut',
      series: [
        {
          type: 'graph',
          layout: 'force',
          data: graphData.nodes,
          links: graphData.links,
          roam: true,
          label: {
            show: true,
            position: 'right',
            formatter: '{b}',
            fontFamily: 'Inter, sans-serif'
          },
          force: {
            repulsion: 400,
            edgeLength: [50, 150]
          },
          lineStyle: {
            color: '#a0aab5',
            curveness: 0.2,
            width: 2
          }
        }
      ]
    };

    option && myChart.setOption(option);
    
    // Make chart responsive
    window.addEventListener('resize', function() {
        myChart.resize();
    });
  });
</script>

---


# Journal Publications

---

* Duc Tai Phan, Nhut Minh Nguyen, Khang Phuc Nguyen, Phuong-Nam Tran, Nhat Truong Pham, Linh Le, Choong Seon Hong, and Duc Ngoc Minh Dang, [&#34;From object difficulty to image scoring: A strategy for active learning in object detection,&#34;](https://doi.org/10.1016/j.knosys.2026.115946) Knowledge-Based Systems, 2026, DOI: 10.1016/j.knosys.2026.115946 <span class="__dimensions_badge_embed__" data-doi="10.1016/j.knosys.2026.115946" data-style="small_rectangle"></span>
* Nhut Minh Nguyen, Trung Thanh Nguyen, Thu Thuy Le, Ngoc-Hanh Dang, Phuong Luu Vo, Lam Thanh Hien, and Duc Ngoc Minh Dang, [“HyperDyG: Hypergraph-Driven Dynamic Fusion for Semi-Supervised Multimodal Emotion Recognition,”](https://doi.org/10.4108/eetinis.131.10903) EAI Endorsed Transactions on Industrial Networks and Intelligent Systems, 2026, DOI: 10.4108/eetinis.131.10903 <span class="__dimensions_badge_embed__" data-doi="10.4108/eetinis.131.10903" data-style="small_rectangle"></span>
* Nhut Minh Nguyen, Minh Trung Nguyen, Thanh Trung Nguyen, Phuong-Nam Tran, Nhat Truong Pham, Linh Le, Alice Othmani, Abdulmotaleb El Saddik, and Duc Ngoc Minh Dang, [“Enhancing multimodal emotion recognition with dynamic fuzzy membership and attention fusion,”](https://doi.org/10.1016/j.engappai.2025.113396) Engineering Applications of Artificial Intelligence, 2026, DOI: 10.1016/j.engappai.2025.113396 <span class="__dimensions_badge_embed__" data-doi="10.1016/j.engappai.2025.113396" data-style="small_rectangle"></span>
* Nhut Minh Nguyen, Thanh Trung Nguyen, Phuong-Nam Tran, Chee Peng Lim, Nhat Truong Pham, and Duc Ngoc Minh Dang, [&#34;Multimodal fusion in speech emotion recognition: A comprehensive review of methods and technologies&#34;](https://doi.org/10.1016/j.engappai.2025.112624), Engineering Applications of Artificial Intelligence, 2025, DOI: 10.1016/j.engappai.2025.112624 <span class="__dimensions_badge_embed__" data-doi="10.1016/j.engappai.2025.112624" data-style="small_rectangle"></span>
* Vo Phuc Tinh, Hoang Hai Son, Duc Ngoc Minh Dang, Nguyen Hoang Nam, Duy-Dong Le, Thai-Binh Nguyen, Thanh-Qui Pham, Van-Luong Nguyen, Duy-Thanh Huynh, and Tran Anh Khoa, [&#34;CroSSHeteroFL: Cross-Stratified Sampling Composition-Fitting to Federated Learning for Heterogeneous Clients&#34;](https://doi.org/10.1109/ACCESS.2024.3475737), IEEE Access, 2024, DOI: 10.1109/ACCESS.2024.3475737 <span class="__dimensions_badge_embed__" data-doi="10.1109/ACCESS.2024.3475737" data-style="small_rectangle"></span>
* Duc Ngoc Minh Dang, [&#34;Enhancing IEEE 802.11ah Networks: A Spatial Multi-Channel MAC Protocol&#34;](https://doi.org/10.15598/aeee.v23i2.240513), Advances in Electrical and Electronic Engineering, 2025, DOI: 10.15598/aeee.v23i2.240513 <span class="__dimensions_badge_embed__" data-doi="10.15598/aeee.v23i2.240513" data-style="small_rectangle"></span>
* Duong Thanh Tran, Nguyen Doan Hieu Nguyen, Trung Thanh Pham, Phuong-Nam Tran, Thuy-Duong Thi Vu, Cuong Tuan Nguyen, Hanh Dang-Ngoc, and Duc Ngoc Minh Dang, [&#34;SwinTExCo: Exemplar-based Video Colorization using Swin Transformer&#34;](https://doi.org/10.1016/j.eswa.2024.125437), Expert Systems with Applications, 2024, DOI: 10.1016/j.eswa.2024.125437 <span class="__dimensions_badge_embed__" data-doi="10.1016/j.eswa.2024.125437" data-style="small_rectangle"></span>
* Tran Anh Khoa, Trac Nguyen Dang, Tinh Vo Phuc, Nam Nguyen Hoang, Duc Ngoc Minh Dang, Son Hoang Hai, and Lam Pham Duc, [&#34;Safety Is Our Friend: A Federated Learning Framework Toward Driver’s State and Behavior Detection&#34;](https://doi.org/10.1109/TCSS.2023.3273727), IEEE Transactions on Computational Social Systems, 2023, DOI: 10.1109/TCSS.2023.3273727 <span class="__dimensions_badge_embed__" data-doi="10.1109/TCSS.2023.3273727" data-style="small_rectangle"></span>
* Nhat Truong Pham, Duc Ngoc Minh Dang, Ngoc Duy Nguyen, Thanh Thi Nguyen, Hai Nguyen, Balachandran Manavalan, Chee Peng Lim, and Sy Dzung Nguyen, [&#34;Hybrid data augmentation and deep attention-based dilated convolutional-recurrent neural networks for speech emotion recognition&#34;](https://doi.org/10.1016/j.eswa.2023.120608), Expert Systems with Applications, 2023, DOI: j.eswa.2023.120608 <span class="__dimensions_badge_embed__" data-doi="10.1016/j.eswa.2023.120608" data-style="small_rectangle"></span>
* Nhat Truong Pham, Sy Dzung Nguyen, Vu Song Thuy Nguyen, Bich Ngoc Hong Pham, and Duc Ngoc Minh Dang [“Speech emotion recognition using overlapping sliding window and Shapley additive explainable deep neural network”](https://doi.org/10.1080/24751839.2023.2187278), Journal of Information and Telecommunication, 2023, DOI: 10.1080/24751839.2023.2187278 <span class="__dimensions_badge_embed__" data-doi="10.1080/24751839.2023.2187278" data-style="small_rectangle"></span>

---

# Conference Proceedings

---

* Quang Nhan Hoang, Minh Tri Pham, and Duc Ngoc Minh Dang, “HQM-Net: A Hybrid Quantum-Classical Medical Imaging Architecture for Multi-Disease Classification across Heterogeneous Modalities”, The 7th International Conference on Machine Learning and Human-Computer Interaction (MLHMI 2026), Tokyo, Japan, March 2026.
* Nhut Minh Nguyen, Thu Thuy Le, Thanh Trung Nguyen, and Duc Ngoc Minh Dang, “SemiFedER: Semi-supervised Federated Averaging for Multimodal Emotion Recognition”, The 7th International Conference on Machine Learning and Human-Computer Interaction (MLHMI 2026), Tokyo, Japan, March 2026.
* Nam Van Hai Phan, Khoa Minh Nguyen, Phu Nguyen Ngoc Thien, Nguyen Doan Hieu Nguyen, Tri Minh Pham, and Duc Ngoc Minh Dang, [“ChemAligner-T5: A Unified Text-to-Molecule Model via Representation Alignment”](https://doi.org/10.1007/978-3-032-21625-0_16), The 2nd International Conference on Computational Intelligence in Engineering Science (ICCIES 2026), Nha Trang, Khanh Hoa, Viet Nam, April 2-4, 2026, DOI: 10.1007/978-3-032-21625-0_16 <span class="__dimensions_badge_embed__" data-doi="10.1007/978-3-032-21625-0_16" data-style="small_rectangle"></span>
* Phuong Lam Nguyen, Duc Tai Phan, Thanh Trung Nguyen, Nhut Minh Nguyen, and Duc Ngoc Minh Dang, [“YOLOv5-powered Smart Parking System with IoT-based Real-Time Slot Monitoring”](https://doi.org/10.1109/RIVF68649.2025.11365041), The 19th International Conference on Computing and Communication Technologies (RIVF 2025), Vietnam, Dec 18-20, 2025, DOI: 10.1109/RIVF68649.2025.11365041 <span class="__dimensions_badge_embed__" data-doi="10.1109/RIVF68649.2025.11365041" data-style="small_rectangle"></span>
* Quang Nhan Hoang, Thanh Trung Pham, and Duc Ngoc Minh Dang, “Efficient Hybrid Quantum-Classical Convolutional Neural Network with Feature Propagation Layer for Multi-Class Image Classification”, The 10th International Conference on Advanced Engineering – Theory and Applications (AETA 2025), Vietnam, 2025.
* Thu Thuy Le, Nhut Minh Nguyen, Nhat Truong Pham, Phuong-Nam Tran, Nguyen Doan Hieu Nguyen, Phuong Luu Vo, Balachandran Manavalan, Duc Ngoc Minh Dang, [&#34;Federated Semi-Supervised FixMatch: Enhancing CutMix for Medical Image Segmentation&#34;](https://doi.org/10.1109/BigData66926.2025.11402514), 2025 IEEE International Conference on Big Data, Macau SAR, China, Dec 8-11, 2025, DOI: 10.1109/BigData66926.2025.11402514 <span class="__dimensions_badge_embed__" data-doi="10.1109/BigData66926.2025.11402514" data-style="small_rectangle"></span>
* Duc Tai Phan, Nhut Minh Nguyen, and Duc Ngoc Minh Dang, “DAAL: Dual Ambiguity in Active Learning for Object Detection with YOLOE”, The 17th International Conference on Management of Digital EcoSystems (MEDES 2025), Ho Chi Minh City, Vietnam, Nov 24–26, 2025.
* Nhut Minh Nguyen, Duc Tai Phan, and Duc Ngoc Minh Dang, “GloMER: Towards Robust Multimodal Emotion Recognition via Gated Fusion and Contrastive Learning”, The 17th International Conference on Management of Digital EcoSystems (MEDES 2025), Ho Chi Minh City, Vietnam, Nov 24–26, 2025.
* Tran Ngoc Phuong Linh, Nguyen Khanh Ly, Hanh Dang-Ngoc, Long Kam Kim, and Duc Ngoc Minh Dang, [“Towards Scalable EEG-Based Emotion Recognition for Mental Health: A Multi-Task Learning Approach”](https://ieeexplore.ieee.org/document/11223426), The 2025 International Symposium on Electrical and Electronics Engineering (ISEE 2025), Ho Chi Minh City, Vietnam, Oct 23-24, 2025, DOI: 10.1109/ISEE68370.2025.11223426 <span class="__dimensions_badge_embed__" data-doi="10.1109/ISEE68370.2025.11223426" data-style="small_rectangle"></span>
* Vo Duc Tai, Nguyen Xuan Tuyen, Hanh Dang-Ngoc, Vo Que Son, and Duc Ngoc Minh Dang, [“Enhancing Urban Traffic Safety with VANET: A Simulation-Based Multi-Scenario Alert System”](https://ieeexplore.ieee.org/document/11223481), The 2025 International Symposium on Electrical and Electronics Engineering (ISEE 2025), Ho Chi Minh City, Vietnam, Oct 23-24, 2025, DOI: 10.1109/ISEE68370.2025.11223481 <span class="__dimensions_badge_embed__" data-doi="10.1109/ISEE68370.2025.11223481" data-style="small_rectangle"></span>
* Duc-Hieu Hoang, Dinh Thuan Nguyen, Quoc Huy Tran, Thanh Trung Nguyen, Nhut Minh Nguyen, and Duc Ngoc Minh Dang, [&#34;YOLO-Powered Traffic Sign Detection and OpenStreetMap Integration for Intelligent Navigation&#34;](https://doi.org/10.23919/APNOMS67058.2025.11181312), The 2025 Asia-Pacific Network Operations and Management Symposium (APNOMS), Kaohsiung, Taiwan, Sep 22-24, 2025, DOI: 10.23919/APNOMS67058.2025.11181312 <span class="__dimensions_badge_embed__" data-doi="10.23919/APNOMS67058.2025.11181312" data-style="small_rectangle"></span>
* Nhut Minh Nguyen, Thu Thuy Le, Thanh Trung Nguyen, Duc Tai Phan, Anh Khoa Tran, and Duc Ngoc Minh Dang, [&#34;CemoBAM: Advancing Multimodal Emotion Recognition through Heterogeneous Graph Networks and Cross-Modal Attention Mechanisms&#34;](https://doi.org/10.23919/APNOMS67058.2025.11181320), The 2025 Asia-Pacific Network Operations and Management Symposium (APNOMS), Kaohsiung, Taiwan, Sep 22-24, 2025, DOI: 10.23919/APNOMS67058.2025.11181320 <span class="__dimensions_badge_embed__" data-doi="10.23919/APNOMS67058.2025.11181320" data-style="small_rectangle"></span>
* Duc Tai Phan, Nhut Minh Nguyen, Khang Phuc Nguyen, Tri Pham, and Duc Ngoc Minh Dang, [&#34;ALMUS: Enhancing Active Learning for Object Detection with Metric-Based Uncertainty Sampling&#34;](https://doi.org/10.23919/APNOMS67058.2025.11181447), The 2025 Asia-Pacific Network Operations and Management Symposium (APNOMS), Kaohsiung, Taiwan, Sep 22-24, 2025, DOI: 10.23919/APNOMS67058.2025.11181447 <span class="__dimensions_badge_embed__" data-doi="10.23919/APNOMS67058.2025.11181447" data-style="small_rectangle"></span>
* Nam Van Hai Phan, Minh-Khoa Nguyen, Trung Thanh Nguyen, Trung Thanh Pham, Phuong-Nam Tran, and Duc Ngoc Minh Dang, [&#34;Mask CoMER: Enhancing Handwritten Mathematical Expression Recognition with Masked Language Pretraining and Regularization&#34;](https://doi.org/10.1007/978-3-032-04624-6_22), ICDAR 2025 (rank A), Wuhan, Hubei, China, Sep 16-21, 2025, DOI: 10.1007/978-3-032-04624-6_22 <span class="__dimensions_badge_embed__" data-doi="10.1007/978-3-032-04624-6_22" data-style="small_rectangle"></span>
* Binh Huynh Thanh Phan, Hai Hoang Son Vu, Xuyen Le Bao Nguyen, Tinh Duc Huynh, Duong Thi Thuy Vu, and Duc Ngoc Minh Dang, [&#34;LLM-Guided Multi-Object Tracking: Enhancing Retail Insights with TempRMOT&#34;](https://doi.org/10.1109/MLHMI66056.2025.00018), The 6th International Conference on Machine Learning and Human-Computer Interaction (MLHMI), Kawasaki, Japan, Mar 4-6, 2025, DOI: 10.1109/MLHMI66056.2025.00018 <span class="__dimensions_badge_embed__" data-doi="10.1109/MLHMI66056.2025.00018" data-style="small_rectangle"></span>
* Phuong-Nam Tran, Duc Ngoc Minh Dang, Eui-Nam Huh, and Choong Seon Hong, [&#34;Additive Angular Margin Loss for Federated Learning in Image Classification&#34;](https://ieeexplore.ieee.org/document/10993113), 39th International Conference on Information Networking (ICOIN), Chiang Mai, Thailand, Jan 15-17, 2025, DOI: 10.1109/ICOIN63865.2025.10993113 <span class="__dimensions_badge_embed__" data-doi="10.1109/ICOIN63865.2025.10993113" data-style="small_rectangle"></span>
* Duc Tai Phan, Phuong-Nam Tran, and Duc Ngoc Minh Dang, [“Improving Face Attendance Checking System with Ensemble Learning”](https://ieeexplore.ieee.org/document/11009085), 2024 RIVF International Conference on Computing and Communication Technologies (RIVF), Da Nang, Vietnam, Dec 21-23, 2024, DOI: 10.1109/RIVF64335.2024.11009085 <span class="__dimensions_badge_embed__" data-doi="10.1109/RIVF64335.2024.11009085" data-style="small_rectangle"></span>
* Nhut Minh Nguyen, Thanh Trung Nguyen, Hua Hiep Nguyen, Phuong-Nam Tran, and Duc Ngoc Minh Dang, [“Voice-Based Age and Gender Recognition: A Comparative Study of LSTM, RezoNet and Hybrid CNNs-BiLSTM Architecture”](https://ieeexplore.ieee.org/document/10827387), The 15th International Conference on ICT Convergence (ICTC 2024), Jeju, Korea, Oct 16-18, 2024, DOI: 10.1109/ICTC62082.2024.10827387 <span class="__dimensions_badge_embed__" data-doi="10.1109/ICTC62082.2024.10827387" data-style="small_rectangle"></span>
* Thu Thuy Le, Nhat Truong Pham, Phuong-Nam Tran, and Duc Ngoc Minh Dang, [“Federated Learning with U-Net for Brain Tumor Segmentation: Impact of Client Numbers and Data Distribution”](https://ieeexplore.ieee.org/document/10826674), The 15th International Conference on ICT Convergence (ICTC 2024), Jeju, Korea, Oct 16-18, 2024, DOI: 10.1109/ICTC62082.2024.10826674 <span class="__dimensions_badge_embed__" data-doi="10.1109/ICTC62082.2024.10826674" data-style="small_rectangle"></span>
* Phuong-Nam Tran, Nhat Truong Pham, Hai Nam Phan Van, Duc Tai Phan, Tuan Cuong Nguyen, and Duc Ngoc Minh Dang, [“Towards Real-time Vietnamese Traffic Sign Recognition on Embedded Systems”](https://ieeexplore.ieee.org/document/10827558), The 15th International Conference on ICT Convergence (ICTC 2024), Jeju, Korea, Oct 16-18, 2024, DOI: 10.1109/ICTC62082.2024.10827558 <span class="__dimensions_badge_embed__" data-doi="10.1109/ICTC62082.2024.10827558" data-style="small_rectangle"></span>
* Trung Nguyen Minh, Phuong-Nam Tran, and Duc Ngoc Minh Dang, [“Enhancing Speech Emotion Recognition through Knowledge Distillation”](https://ieeexplore.ieee.org/document/10826904), The 15th International Conference on ICT Convergence (ICTC 2024), Jeju, Korea, Oct 16-18, 2024, DOI: 10.1109/ICTC62082.2024.10826904 <span class="__dimensions_badge_embed__" data-doi="10.1109/ICTC62082.2024.10826904" data-style="small_rectangle"></span>
* Nam Van Hai Phan, Tha Thanh Le, Tuan Phu Phan, Thuy Thu Le, Phuong-Nam Tran, Nhat Truong Pham, and Duc Ngoc Minh Dang, [“Deep Learning-Based Automated Cashier System for Bakeries”](https://dl.acm.org/doi/10.1145/3654522.3654538), 9th International Conference on Intelligent Information Technology (ICIIT 2024), Feb 23-25, 2024, DOI: 10.1145/3654522.3654538 <span class="__dimensions_badge_embed__" data-doi="10.1145/3654522.3654538" data-style="small_rectangle"></span>
* Dang Khoa Phan, Phuong-Nam Tran, Nhat Truong Pham, Tra Huong Thi Le, and Duc Ngoc Minh Dang, [“Innovative Multi-Modal Control for Surveillance Spider Robot: An Integration of Voice and Hand Gesture Recognition”](https://dl.acm.org/doi/10.1145/3654522.3654544), 9th International Conference on Intelligent Information Technology (ICIIT 2024), Feb 23-25, 2024, DOI: 10.1145/3654522.3654544 <span class="__dimensions_badge_embed__" data-doi="10.1145/3654522.3654544" data-style="small_rectangle"></span>
* Dinh Thuan Nguyen, Minh Khanh Phan, Phuong-Nam Tran, and Duc Ngoc Minh Dang, [“Vietnamese Traffic Sign Recognition Using Deep Learning”](https://dl.acm.org/doi/10.1145/3654522.3654528), 9th International Conference on Intelligent Information Technology (ICIIT 2024), Feb 23-25, 2024, DOI: 10.1145/3654522.3654528 <span class="__dimensions_badge_embed__" data-doi="10.1145/3654522.3654528" data-style="small_rectangle"></span>
* Chi Hung Le, Hung Phat Ly, Duc Tien Nguyen, Hanh Dang-Ngoc, Thuy-Duong Thi Vu, and Duc Ngoc Minh Dang, [“Deep Learning Based Attendance Check System At FPT University”](https://dl.acm.org/doi/10.1145/3654522.3654584), 9th International Conference on Intelligent Information Technology (ICIIT 2024), Feb 23-25, 2024, DOI: 10.1145/3654522.3654584 <span class="__dimensions_badge_embed__" data-doi="10.1145/3654522.3654584" data-style="small_rectangle"></span>
* Triet Minh Huynh, Duy Linh Nguyen, Thanh Tri Nguyen, Thuy-Duong Thi Vu, Hanh Dang-Ngoc, and Duc Ngoc Minh Dang, [“CLIP-Prefix for Image Captioning and an Experiment on Blind Image Guessing”](https://link.springer.com/chapter/10.1007/978-3-031-67357-3_14), The 10th EAI International Conference on Industrial Networks and Intelligent Systems (INISCOM 2024), Feb 20-21, 2024, DOI: 10.1007/978-3-031-67357-3_14 <span class="__dimensions_badge_embed__" data-doi="10.1007/978-3-031-67357-3_14" data-style="small_rectangle"></span>
* Binh Dang Hai, Huu Duc Nguyen, Thanh Nam Vo, Phuong-Nam Tran, Cuong Tuan Nguyen, and Duc Ngoc Minh Dang, [“Performance Comparison in Traffic Sign Recognition using Deep Learning”](https://link.springer.com/chapter/10.1007/978-3-031-67357-3_9), The 10th EAI International Conference on Industrial Networks and Intelligent Systems (INISCOM 2024), Feb 20-21, 2024, DOI: 10.1007/978-3-031-67357-3_9 <span class="__dimensions_badge_embed__" data-doi="10.1007/978-3-031-67357-3_9" data-style="small_rectangle"></span>
* Quan Bao Le, Kiet Tuan Trinh, Nguyen Dinh Hung Son, Phuong-Nam Tran, Cuong Tuan Nguyen, and Duc Ngoc Minh Dang, [“MERSA: Multimodal Emotion Recognition with Self-Align Embedding”](https://ieeexplore.ieee.org/document/10572116), The 38th International Conference on Information Networking (ICOIN 2024), Jan 17-19, 2024, DOI: 10.1109/ICOIN59985.2024.10572116 <span class="__dimensions_badge_embed__" data-doi="10.1109/ICOIN59985.2024.10572116" data-style="small_rectangle"></span>
* Nhat Truong Pham, Le Thi Phan, Duc Ngoc Minh Dang, and Balachandran Manavalan, [“SER-Fuse: An Emotion Recognition Application Utilizing Multi-Modal, Multi-Lingual, and Multi-Feature Fusion”](https://dl.acm.org/doi/10.1145/3628797.3628887), The 12th International Symposium on Information and Communication Technology (SoICT 2023), Ho Chi Minh City, Vietnam, Dec 7-8, 2023, DOI: 10.1145/3628797.3628887 <span class="__dimensions_badge_embed__" data-doi="10.1145/3628797.3628887" data-style="small_rectangle"></span>
* Duong Thanh Tran, Nguyen Doan Hieu Nguyen, Trung Thanh Pham, Phuong-Nam Tran, Thuy-Duong Thi Vu, and Duc Ngoc Minh Dang, [“Vitexco: Exemplar-based Video Colorization using Vision Transformer”](https://ieeexplore.ieee.org/document/10393505), The 14th International Conference on ICT Convergence (ICTC 2023), Jeju, Korea, Oct 11 -13, 2023, DOI: 10.1109/ICTC58733.2023.10393505 <span class="__dimensions_badge_embed__" data-doi="10.1109/ICTC58733.2023.10393505" data-style="small_rectangle"></span>
* Duc-Hieu Hoang, Duc Ngoc Minh Dang, Hanh Dang-Ngoc, Anh-Khoa Tran, Phuong-Nam Tran, and Cuong Tuan Nguyen, [“RBBA: ResNet - BERT - Bahdanau Attention for Image Caption Generator”](https://ieeexplore.ieee.org/document/10392496), The 14th International Conference on ICT Convergence (ICTC 2023), Jeju, Korea, Oct 11 -13, 2023, DOI: 10.1109/ICTC58733.2023.10392496 <span class="__dimensions_badge_embed__" data-doi="10.1109/ICTC58733.2023.10392496" data-style="small_rectangle"></span>
* Phuong-Nam Tran, Thuy-Duong Thi Vu, Nhat Truong Pham, Hanh Dang-Ngoc, and Duc Ngoc Minh Dang, [“Comparative analysis of multi-loss functions for enhanced multi-modal speech emotion recognition”](https://ieeexplore.ieee.org/document/10392928), The 14th International Conference on ICT Convergence (ICTC 2023), Jeju, Korea, Oct 11 -13, 2023, DOI: 10.1109/ICTC58733.2023.10392928 <span class="__dimensions_badge_embed__" data-doi="10.1109/ICTC58733.2023.10392928" data-style="small_rectangle"></span>
* Nam Phuong Tran, Thuy-Duong Vu, Duc Ngoc Minh Dang, Nhat Truong Pham, and Anh Khoa Tran, [“Multi-modal Speech Emotion Recognition: Improving Accuracy through Fusion of VGGish and BERT Features with Multi-head Attention”](https://link.springer.com/chapter/10.1007/978-3-031-47359-3_11), 9th EAI International Conference on Industrial Networks and Intelligent Systems (INISCOM 2023), Ho Chi Minh City, Vietnam, Aug 2-3, 2023, DOI: 10.1007/978-3-031-47359-3_11 <span class="__dimensions_badge_embed__" data-doi="10.1007/978-3-031-47359-3_11" data-style="small_rectangle"></span>
* Phuc Tinh Vo, Viet Anh Nguyen, Xuyen Bao Le Nguyen, Duc Ngoc Minh Dang, and Anh Khoa Tran, [“Performance Analysis of Distributed Learning in Edge Computing on Handwritten Digits Dataset”](https://link.springer.com/chapter/10.1007/978-3-031-47359-3_12), 9th EAI International Conference on Industrial Networks and Intelligent Systems (INISCOM 2023), Ho Chi Minh City, Vietnam, Aug 2-3, 2023, DOI: 10.1007/978-3-031-47359-3_12 <span class="__dimensions_badge_embed__" data-doi="10.1007/978-3-031-47359-3_12" data-style="small_rectangle"></span>
* Nhat Truong Pham, Duc Ngoc Minh Dang, Bich Ngoc Hong Pham, and Sy Dzung Nguyen, [&#34;SERVER: Multi-modal Speech Emotion Recognition using Transformer-based and Vision-based Embeddings&#34;](https://dl.acm.org/doi/10.1145/3591569.3591610), 2023: 8th International Conference on Intelligent Information Technology (ICIIT 2023), Da Nang, Vietnam, Feb 24 - 26, 2023, DOI: 10.1145/3591569.3591610 <span class="__dimensions_badge_embed__" data-doi="10.1145/3591569.3591610" data-style="small_rectangle"></span>
* Nhat Truong Pham, Anh-Tuan Tran, Bich Ngoc Hong Pham, Hanh Dang-Ngoc, Sy Dzung Nguyen, and Duc Ngoc Minh Dang, [&#34;Speech Emotion Recognition: A Brief Review of Multi-modal Multi-task Learning Approaches&#34;](https://link.springer.com/chapter/10.1007/978-981-99-8703-0_50), The 7th International Conference on Advanced Engineering – Theory and Applications (AETA-2022), Vietnam, Dec 8-10, 2022, DOI: 10.1007/978-981-99-8703-0_50 <span class="__dimensions_badge_embed__" data-doi="10.1007/978-981-99-8703-0_50" data-style="small_rectangle"></span>

<!-- *** -->

<!-- # Book Chapters -->

<!-- *** -->

<!-- * Nam Bui Khac Hoai, Sungrae Cho, Jason J. Jung, Joongheon Kim, O-Joun Lee, Woongsoo Na: Network Engineering: Towards Data-Driven Framework for Network Configuration. Big Data Technologies and Applications, 11/2018: pages 60-65; Springer, Cham., ISBN: 978-3-319-98751-4, DOI:10.1007/978-3-319-98752-1_7 <span class="__dimensions_badge_embed__" data-doi="10.1007/978-3-319-98752-1_7" data-style="small_rectangle"></span><script async src="https://badge.dimensions.ai/badge.js" charset="utf-8"></script>

* Quang Dieu Tran, Dosam Hwang, O.-Joun Lee, Jason J. Jung: A Novel Method for Extracting Dynamic Character Network from Movie. Big Data Technologies and Applications, Edited by Jason J. Jung, Pankoo Kim, 06/2017: pages 48-53; Springer International Publishing., ISBN: 978-3-319-58967-1, DOI:10.1007/978-3-319-58967-1_6 <span class="__dimensions_badge_embed__" data-doi="10.1007/978-3-319-58967-1_6" data-style="small_rectangle"></span><script async src="https://badge.dimensions.ai/badge.js" charset="utf-8"></script>

* Khac-Hoai Nam Bui, O-Joun Lee, Jason J. Jung, David Camacho: Dynamic Traffic Light Control System Based on Process Synchronization Among Connected Vehicles. Ambient Intelligence- Software and Applications – 7th International Symposium on Ambient Intelligence (ISAmI 2016), Edited by Helena Lindgren, Juan F. De Paz, Paulo Novais, Antonio Fernández-Caballero, Hyun Yoe, Andres Jiménez Ramírez, Gabriel Villarrubia, 05/2016: pages 77-85; Springer., ISBN: 978-3-319-40113-3, DOI:10.1007/978-3-319-40114-0_9 <span class="__dimensions_badge_embed__" data-doi="10.1007/978-3-319-40114-0_9" data-style="small_rectangle"></span><script async src="https://badge.dimensions.ai/badge.js" charset="utf-8"></script>

* Khac-Hoai Nam Bui, Xuan Hau Pham, Jason J. Jung, O-Joun Lee, Min-Sung Hong: Context-Based Traffic Recommendation System. Context-Aware Systems and Applications, Edited by Cong Vinh Phan, Alagar Vangalur, 04/2016: pages 122-131; Springer International Publishing., ISBN: 978-3-319-29235-9, DOI:10.1007/978-3-319-29236-6_13 <span class="__dimensions_badge_embed__" data-doi="10.1007/978-3-319-29236-6_13" data-style="small_rectangle"></span><script async src="https://badge.dimensions.ai/badge.js" charset="utf-8"></script>

* Myeong-Yeon Yi, O-Joun Lee, Jason J. Jung: MBTI-based Collaborative Recommendation System: A Case Study of Webtoon Contents. Context-Aware Systems and Applications, Edited by Cong Vinh Phan, Alagar Vangalur, 04/2016: pages 101-110; Springer International Publishing., ISBN: 978-3-319-29236-6, DOI:10.1007/978-3-319-29236-6_11 <span class="__dimensions_badge_embed__" data-doi="10.1007/978-3-319-29236-6_11" data-style="small_rectangle"></span><script async src="https://badge.dimensions.ai/badge.js" charset="utf-8"></script>

* O-Joun Lee, Eunsoon You, Min-Sung Hong, Jason J. Jung: Adaptive Complex Event Processing Based on Collaborative Rule Mining Engine. Intelligent Information and Database Systems, Edited by Ngoc Thanh Nguyen, Bogdan Trawiński, Raymond Kosala, 03/2015: pages 430–439; Springer International Publishing., ISBN: 978-3-319-15701-6, DOI:10.1007/978-3-319-15702-3_42 <span class="__dimensions_badge_embed__" data-doi="10.1007/978-3-319-15702-3_42" data-style="small_rectangle"></span><script async src="https://badge.dimensions.ai/badge.js" charset="utf-8"></script> -->

---

# Unpublished Manuscripts

---

* Hoang Khang Trang, Bao Quoc Nguyen, Viet Vinh Khanh Dinh, Nhut Minh Nguyen, Nhat Truong Pham, Phuong-Nam Tran, Phuong Luu Vo, and Duc Ngoc Minh Dang, "Towards effective multimodal emotion recognition in conversations via joint multi-graph learning and self-distillation", Available at [SSRN](https://dx.doi.org/10.2139/ssrn.6103427) (Preprint)
* Phuong-Nam Tran, Nhat Truong Pham, Duc Ngoc Minh Dang, Eui-Nam Huh, Choong Seon Hong, "QTSeg: A Query Token-Based Dual-Mix Attention Framework with Multi-Level Feature Distribution for Medical Image Segmentation", Available at [arXiv:2412.17241](https://doi.org/10.48550/arXiv.2412.17241) (Preprint)

<!-- * Hyeon-Ju Jeon, Jeon-Ho Kang, In-Hyuk Kwon, O-Joun Lee: CloudNine: Analyzing Meteorological Observation Impact on Weather Prediction Using Explainable Graph Neural Networks. arXiv preprint 02/2024; arXiv:2402.14861. (Preprint)

* Van Thuy Hoang, O-Joun Lee: A Survey on Structure-Preserving Graph Transformers. arXiv preprint 01/2024; arXiv:2401.16176. (Preprint)

* Van Thuy Hoang, O-Joun Lee: Mitigating Degree Biases in Message Passing Mechanism by Utilizing Community Structures. arXiv preprint 12/2023; arXiv:2312.16788. (Preprint)

* Van Thuy Hoang, Sang Thanh Nguyen, Sangmyeong Lee, Jooho Lee, Luong Vuong Nguyen, O-Joun Lee: Companion Animal Disease Diagnostics based on Literal-aware Medical Knowledge Graph Representation Learning. arXiv preprint 09/2023; arXiv:2309.03219. (Preprint)

* Van Thuy Hoang, O-Joun Lee: Transitivity-Preserving Graph Representation Learning for Bridging Local Connectivity and Role-based Similarity. arXiv preprint 08/2023; arXiv:2308.09517. (Preprint)

* Thanh Sang Nguyen, Jooho Lee, Van Thuy Hoang, O-Joun Lee: Connector 0.5: A unified framework for graph representation learning. arXiv preprint 04/2023; arXiv:2304.13195. (Preprint) -->

<!-- *** -->

<!-- # Open Datasets -->

<!-- *** -->

<!-- * Jooho Lee, Yoewon Yoon, O-Joun Lee: Korean News Corpus for Changes in Child Abuse before and after COVID-19 Outbreak. Figshare 08/2023. DOI:10.6084/m9.figshare.24025491.v1 (Dataset)

* Eun-Soon You, Hyeon-Ju Jeon, O-Joun Lee: A Social Network of Characters Appeared in the French Novel Series "La Comédie humaine" and An Interaction Network of Novels in the Series. Figshare 08/2023. DOI:10.6084/m9.figshare.23994078.v1 (Dataset)

* Eun-Soon You, Hyeon-Ju Jeon, O-Joun Lee: A Dynamic Social Network of Characters Appeared in the French Novel "Les Liaisons Dangereuses". Figshare 08/2023. DOI:10.6084/m9.figshare.23993748.v1 (Dataset) -->

<!-- *** -->

<!-- # Patents -->

<!-- *** -->

<!-- * O-Joun Lee, Van Thuy Hoang, Ho Beom Kim, Jinho Seo, Seung Charlie Kim, Nox Kim: System and Method for Predicting Availability based on Knowledge Graph. Ref. No: KR 1020230171167, 11/2022

* Young Man Kwon, Seok Jeong, O-Joun Lee, [Joo-Ho Lee](https://aita-lab.github.io/member/jhlee), [Ji-Yoon Song](https://aita-lab.github.io/member/jysong): System for Providing Context Awareness based Cross-Domain Recommendation Service for Retail Kiosk. Ref. No: KR 1020220087796, 07/2022

* Jason J. Jung, O-Joun Lee: Method and apparatus for content analysis including story. Ref. No: KR 1020180058510, 05/2018

* Jason J. Jung, Jaehong Park, O-Joun Lee, Min-Sung Hong: Server and Method for providing search results using SNS date, Recording medium for performing the method. Ref. No: KR 1020170165067, 12/2017

* Jason J. Jung, Min-Sung Hong, O-Joun Lee: Apparatus and Method for recommending item to user group using emotion information. Ref. No: KR1020170042015, 03/2017

* Jason J. Jung, Min-Sung Hong, O-Joun Lee: Apparatus and Method for recommending item for user group. Ref. No: KR1020170033241, 03/2017

* Jason J. Jung, O-Joun Lee: Method and Apparatus for matching identification information of plurality of SNS. Ref. No: KR 1020150128425, 09/2015

* Jason J. Jung, O-Joun Lee: Event processing system, Event processing method and Computer program. Ref. No: KR1020150099077, 07/2015

* Hyun-Sik Kim, Seung-Bo Park, Eun-Soon You, O-Joun Lee, Byung Joon Cho: APPARATUS AND METHOD FOR SUPPORTING WRITER BY TRACING CONVERSATION BASED ON TEXT ANALYSIS. Ref. No: KR1020150057199, 04/2015

* O-Joun Lee, Eun-Soon You, Byung Joon Cho: APPARATUS AND METHOD FOR PREDICTIVE CLUSTERING-BASED COLLABORATIVE FILTERING. Ref. No: KR1020150042144, 03/2015

* Jae-Dong Lee, Seung-Hun Kim, Min-Sung Hong, Kee-Won Kim, O-Joun Lee, Won-Jin Lee: APPARATUS FOR ANALYZING CONTENTS AND METHOD THEREOF. Ref. No: KR1020140093024, 07/2014

* O-Joun Lee, Jae-Dong Lee, Won-Jin Lee, Seung-Bo Park, Min-Sung Hong, Gyu-Chan Lim: APPARATUS AND METHOD FOR HYBRID FILTERING CONTENT RECOMMENDATION USING USER PROFILE AND CONTEXT INFORMATION BASED ON PREFERENCE. Ref. No: KR1020140027866, 03/2014

* O-Joun Lee, Jae-Dong Lee, Seung-Hun Kim, Won-Jin Lee, Seung-Bo Park, Min-Sung Hong, Se-Jun Park: APPARATUS AND METHOD FOR PREDICTING USER FEED BACK IN COLLABORATIVE RECOMMENDATION SYSTEM. Ref. No: KR1020140027865, 03/2014 -->

<!-- *** -->

<!-- # Awards & Grants -->

<!-- *** -->

<!-- * Dec 2023: Van Thuy Hoang, "Excellence in Research Award", The 2nd CUK Annual Colloquium on Artificial Intelligence (CUK AI Colloquium 2023), Bucheon, Korea

<p align="center"><img width="700" src="/images/EiR2023_Hoang.webp" margin="10px"></p>

* Dec 2022: Sang Thanh Nguyen, "Excellence in Research Award", The 1st CUK Annual Colloquium on Artificial Intelligence (CUK AI Colloquium 2022), Seoul, Korea

* Jun 2022: Jiyoon Song, Se Eun Cho, Jooho Lee, Yeongmin Kim, Hyebin Ahn, O-Joun Lee, "[Best Paper Award](https://drive.google.com/file/d/1vMnVNUzf29TECy6coVAU-oL2PftihMt3/view?usp=sharing)", The 2022 Conference of Korea Institute of Smart Media (KISM), Daejeon, Korea

<p align="center"><img width="700" src="/images/BP1.jpg" margin="10px"></p> -->

<!-- *** -->

<!-- # Invited Talks -->

<!-- *** -->

<!-- 
* O-Joun Lee: An Overview of Graph Learning Models in Molecular Structure Analysis. [The 9th IEEE/IEIE International Conference on Consumer Electronics Asia (ICCE-Asia 2024)](https://icce-asia2024.org/2024/), Danang, Vietnam, 11/2024 

* O-Joun Lee: Analyzing Molecular Structures with Graph Neural Networks. [The 2024 Summer Annual Conference of the Institute of Electronics and Information Engineers](https://conf.theieie.org/2024s/pages/special_session.vm), Jeju, Korea, 06/2024

<p align="center">
  <img width="90%" data-action="zoom" src="/images/Talk-IEIE-2024s.jpg" alt="absolute">
</p>

* O-Joun Lee: Knowledge Graph Reasoning and its Applications. [Telecommunications Technology Association](https://www.tta.or.kr/eng/index.do), Seongnam, Korea, 09/2023

* O-Joun Lee: Semiconductor Design with Graph Neural Networks. [The 2023 Summer Annual Conference of the Institute of Electronics and Information Engineers](https://conf.theieie.org/2023s/pages/guest_lecture.vm), Jeju, Korea, 06/2023

<p align="center">
  <img width="90%" data-action="zoom" src="/images/Talk-IEIE-2023s.jpg" alt="absolute">
</p>

* O-Joun Lee: Spatio-Temporal Forecasting Models for Renewable Energy. [The 1st International Conference on Intelligence of Things (ICIT 2022)](https://icit2022.humg.edu.vn/), Hanoi, Vietnam, 08/2022

* O-Joun Lee: The 2022 Summer Workshop of Korean Institute of Next Generation Computing, Pyeongchang, Korea, 07/2022

* O-Joun Lee: Trends in Interdisciplinary Research and Collaboration Opportunities. Vietnam National University, Hanoi - International School (VNU - IS), Virtual, 09/2021

<p align="center">
  <img width="700" data-action="zoom" src="/images/Talk-VNUIS.jpg" alt="absolute">
</p> -->

<!-- *** -->

<!-- # Posters -->

<!-- *** -->

<!-- 
<p align="center">
  <img width="700" src="/images/AAAI2024_poster_Thuy.webp">
</p>
 
<br>
 
<p align="center">
  <img width="700" src="/images/AAAIw2024_Poster_HJ.webp">
</p>
 
<br>
 
<p align="center">
  <img width="700" src="/images/IUS2023_Poster_JL.webp">
</p>
 
<br>
 
<p align="center">
  <img width="700" src="/images/IUS2023_poster_JN.webp">
</p>
 
<br>
 
<p align="center">
  <img width="700" src="/images/ASK2023_poster_JL.webp">
</p>
 
<br>
 
<p align="center">
  <img width="700" src="/images/ASK2023_poster_JN.webp">
</p>
 
<br>
 
<p align="center">
  <img width="700" src="/images/Samsung2023_poster_JL.webp">
</p>
 
<br>
 
<p align="center">
  <img width="700" src="/images/ACK2023_poster_DK.webp">
</p>
 
<br>
 
<p align="center">
  <img width="700" src="/images/ASK2023_poster_DK.webp">
</p>
 
<br>
 
<p align="center">
  <img width="700" src="/images/AWAD2023_Poster.webp">
</p>
 
<br>
 
<p align="center">
  <img width="700" src="/images/ACK2023_poster_SM.webp">
</p>
 
<br>
  -->