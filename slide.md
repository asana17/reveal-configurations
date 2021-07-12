### 7/15 mtg
#### Akihiro Sakurai

---
### 研究の方向性
- 対象: メニーコア, Linux上のCycloneDDS
- 内容:  
オブジェクトや状態をマルチコア間で共有する代わりに複製し、ROS2アプリケーション(autoware)の高速化を目指す

---
### CycloneDDSの注目点
CPU使用時間をflamegraphにしたものを見ると、

note: flame graphを貼付け

---
### 論文: Modeling Fuctional Behaviors of DDS
OMGによる標準モデルに足りない部分をモデル化
1. DCPS objects の作成と削除
2. Publishing Data
3. Subscribing Data

note: #### 1. DCPS objects の作成と削除
### A. DomainParticipant Objects

#### DCPS objects の作成と削除
### B. Publication Objects

#### DCPS objects の作成と削除
### C. Subscription Objects

---
### 論文: 

---
### 現状
具体的にコア間で複製するオブジェクトや状態が決まっていない  
→ モデル化されたうちのどのオブジェクトに注目するか  


### やること
