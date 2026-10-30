---
title: "研究内容"
permalink: /research/
author_profile: true
---

当研究室では、宇宙軌道力学に関する以下のような研究テーマに取り組んでいます。  
<!--共同研究や研究相談についてはサイドバーに記載のメールアドレスにお問い合わせください。-->

## 安定・不安定多様体を用いた軌道解析・軌道設計

制限三体・四体問題のような二つ以上の天体の影響を同時に考慮する重力多体問題には一般解が存在しないため、平衡点（ラグランジュ点）や周期・準周期軌道、安定・不安定多様体をはじめとする特殊解を用いた軌道解析・軌道設計が有効です。私たちは、安定・不安定多様体が形成するtube構造やlobe構造に基づき、小天体の遷移現象の力学的メカニズムの解明や、燃料消費を抑えた月への遷移軌道の設計を行っています。また、軌道面外方向の不安定性に起因する安定・不安定多様体を用いることで、宇宙機の軌道傾斜角を効率的に変化させる手法を提案しました。  
### 関連論文
- [Jumping mechanisms of Trojan asteroids in the planar restricted three- and four-body problems](https://link.springer.com/article/10.1007/s10569-015-9609-4)
- [The roles of L4 and L5 axial orbits in transport among co-orbital orbits](https://academic.oup.com/mnras/article/480/3/2945/5062811)
- [The use of vertical instability of L1 and L2 planar Lyapunov orbits for transfers from near rectilinear halo orbits to planar distant retrograde orbits in the Earth-Moon system](https://link.springer.com/article/10.1007/s10569-019-9892-6)
- [Optimization-Aided, Low-Energy Transfers via Vertical Instability Around Earth–Moon L1](https://arc.aiaa.org/doi/10.2514/1.G005159)
- [Linking low- to high-energy dynamics of invariant manifolds, transit orbits, and singular collision orbits in the planar circular restricted three-body problem](https://link.springer.com/article/10.1007/s10569-019-9934-0)
- [共鳴重力アシストの力学的機構に基づく月への遷移軌道設計](https://www.researchgate.net/publication/404279614_Design_of_Earth-Moon_Transfer_Trajectories_Based_on_Dynamical_Mechanisms_of_Resonant_Gravity_Assists)
- [複数回の共鳴重力アシストおよび不変多様体tubeを用いた月遷移軌道の設計](https://www.researchgate.net/publication/404279619_Design_of_Earth-Moon_transfer_trajectories_using_multiple_resonance_gravity_assists_and_invariant_manifold_tubes)

## 重力ポテンシャルの特異点の正則化・衝突軌道を用いた軌道設計

適切な変数を追加して系を記述し直すことで、特異点を除去して不良問題を扱い易くする手法は、一般に正則化と呼ばれます。私たちは、従来利用されてきた安定・不安定多様体に加え、天体中心に衝突する特異的な軌道も、重力多体問題の軌道解析・設計に有用な特殊解であることを示し、地球–月間遷移軌道の設計に応用しました。また、運動方程式が時間に陽に依存する双円制限四体問題（bicircularモデル）における正則化法および月衝突軌道の計算手法を構築しました。  
### 関連論文
- [Levi-Civita and Kustaanheimo–Stiefel regularizations of the bicircular restricted four-body problem](https://www.sciencedirect.com/science/article/abs/pii/S1384107626001193)
- [Analysis of medium-energy transfers to the Moon](https://link.springer.com/article/10.1007/s10569-016-9727-7)
- [Linking low- to high-energy dynamics of invariant manifolds, transit orbits, and singular collision orbits in the planar circular restricted three-body problem](https://link.springer.com/article/10.1007/s10569-019-9934-0)

## 特異点フリーな軌道最適化手法の構築

宇宙機の軌道設計では、様々な制約条件を満たしつつ、燃料消費量や飛行時間など何らかのコストを最小化する軌道最適化問題を解く必要が生じます。当研究室では、重力ポテンシャルの特異点を除去するために従来用いられてきた正則化手法を、制御入力がゼロとなる状態を特異点にもつ燃料最小化問題に適用することで、特異点フリーな収束性の良い最適化手法を開発しました。提案手法を様々な軌道遷移問題に応用し、従来解と比較して燃料消費がより少ない解や、収束が難しいことで知られる三体・低推力・多周回の遷移軌道を求められることを示しました。  
### 関連論文
- [Regularizing fuel-optimal multi-impulse trajectories](https://link.springer.com/article/10.1007/s42064-023-0176-2)
- [Regularized direct method for low-thrust trajectory optimization: Minimum-fuel transfer between cislunar periodic orbits](https://www.sciencedirect.com/science/article/abs/pii/S027311772300426X)
- [The Impact of Second-Order Analytical Derivatives on Regularized Direct Multiple Shooting Method for Impulsive Spacecraft Trajectory Optimization](https://www.worldscientific.com/doi/10.1142/S2737480724500018?srsltid=AU7gw4U3dhT1TK-sCUVZz7AyR2AhZWOB9711dnq1kXZF53NaKX-PUjEG)

## 月スイングバイ・太陽潮汐力を利用した軌道設計

地球周回軌道を大きく変化させるには、月・太陽重力の利用が有効です。私たちは月スイングバイや太陽潮汐力を積極的に利用することで、様々な目的地（月，月近傍の準周期軌道など）に燃料消費を抑えて到達できる軌道を設計しています。また、複数回の月スイングバイや太陽潮汐力を利用するフェーズを含む複雑なシーケンスの軌道を体系的に設計するため、3次元モデルにおいて月から月に遷移する軌道のデータベース（3D Moon-to-Moon database）を作成し、軌道間輸送機の軌道設計に応用しました。
### 関連論文
- [Database Approach for Synthesizing a Ballistic OTV Flight Sequence Connecting Lunar NRHO to SEL2 Small Halo Orbit](https://www.researchgate.net/publication/398561211_Database_Approach_for_Synthesizing_a_Ballistic_OTV_Flight_Sequence_Connecting_Lunar_NRHO_to_SEL2_Small_Halo_Orbit)
- [Low-energy transfers to the Moon with long transfer time](https://link.springer.com/article/10.1007/s10569-019-9883-7)
- [EQUULEUS Trajectory Design](https://link.springer.com/article/10.1007/s40295-019-00206-y)
- [Transfer from Lunar Gateway to Sun-Earth Halo Orbits Using Solar Sails](https://arc.aiaa.org/doi/10.2514/1.A35559)

<!--
## エネルギー的な障壁構造の解析

障壁構造として、ゼロ速度曲線およびゼロ速度曲面がHill以降。
跳ね返る挙動を利用することで、。  
### 関連論文
- [A hidden barrier surface complementary to the zero velocity surface in the circular restricted three-body problem](https://link.springer.com/article/10.1007/s10569-024-10230-2)
- [On the concept of conditional barrier structures in the planar circular restricted three-body problem](https://link.springer.com/article/10.1007/s10569-025-10260-4)
- [Detailed Analysis on Barrier Surfaces Separating Regions of Possible and Impossible Motion in the Circular Restricted Three-Body Problem](https://www.jstage.jst.go.jp/article/jesa/4/0/4_272/_article/-char/ja)
-->

<!--
## 周期軌道の探索・分岐解析

無数に埋め込まれた周期軌道を同定し、その軌道特性を明らかにすることで、
また、分岐解析を行うことで体系的に同定。時間に陽に依存する双円制限四体問題や楕円制限三体問題においても、  。
### 関連論文
- [Multiple families of synodic resonant periodic orbits in the bicircular restricted four–body problem](https://www.sciencedirect.com/science/article/abs/pii/S0273117722004781)
- [Spatial unstable periodic quasi-satellite orbits and their applications to spacecraft trajectories](https://link.springer.com/article/10.1007/s10569-019-9901-9)
- [Continuation and stationkeeping analyses on planar retrograde periodic orbits around the Earth](https://www.sciencedirect.com/science/article/abs/pii/S0273117721009303)
- [3D stable and weakly unstable periodic orbits around the Earth near the retrograde co-orbital resonance with the Moon](https://link.springer.com/article/10.1007/s10509-022-04071-4)
- [Retrograde co-orbital orbits in the Earth–Moon system: planar stability region under solar gravitational perturbation](https://link.springer.com/article/10.1007/s10509-021-03994-8)
-->

<!--
## 深宇宙への中継軌道の提案

逆行周期軌道。  
### 関連論文
- [Extended analysis on stability, capture, and escape for planar retrograde periodic orbit around Earth](https://link.springer.com/article/10.1007/s10509-025-04434-7)
- [Interplanetary Trajectory Design from a Moon-Grazing Retrograde Periodic Orbit around Earth](https://www.researchgate.net/publication/405746991_Interplanetary_Trajectory_Design_from_a_Moon-Grazing_Retrograde_Periodic_Orbit_around_Earth)
- [Capture and escape analyses on planar retrograde periodic orbit around the Earth](https://www.sciencedirect.com/science/article/abs/pii/S0273117721005676?via%3Dihub)
-->

<!--
## 事前計算グラフを用いた軌道設計

相乗りミッションにおける打ち上げ条件の急な変更や、missed thrustのような不具合に対応するには、迅速な軌道設計が求められます。しかし、軌道面外の運動も考慮する空間問題や多数の制御入力を含む問題において、変数が増えすぎるため十分な探索が困難となります。そこで当研究室では、頂点と辺から構成されるグラフが、軌道を頂点、軌道どうしの接続に関する情報（航行時間や燃料消費量）を辺の重みとして表現できる性質に着目しました。本研究では近点から近点への遷移軌道を頂点とし、それら軌道どうしの接続に要する航行時間と燃料消費量から様々に辺の重みを定義したグラフを用いることで，特殊解に依存せず多様な軌道間遷移問題を多目的最適化問題として解くことに挑戦しています。  
### 関連論文
- [A graph-based framework of low-energy transfer design](https://www.sciencedirect.com/science/article/abs/pii/S0094576525000529)
- [事前計算グラフを用いた宇宙機の軌道設計](https://researchmap.jp/espresso/published_papers/50188589?lang=ja)
-->

<!--
## 共鳴軌道を利用した軌道設計

軌道共鳴現象を利用することで，月と会合することが可能になります。月への遷移に要する燃料を低減できる軌道を発見しました。
また、共鳴軌道を用いた月軌道投入のロバスト化を提案しました。  
### 関連論文
- [Robust Orbit Insertion Strategies for Low-Energy Lunar Transfer](https://www.researchgate.net/publication/405746990_Robust_Orbit_Insertion_Strategies_for_Low-Energy_Lunar_Transfer)
- [Global search for low-thrust transfers to the Moon in the planar circular restricted three-body problem](https://link.springer.com/article/10.1007/s10569-016-9748-2)
- [共鳴重力アシストの力学的機構に基づく月への遷移軌道設計](https://www.researchgate.net/publication/404279614_Design_of_Earth-Moon_Transfer_Trajectories_Based_on_Dynamical_Mechanisms_of_Resonant_Gravity_Assists)
- [複数回の共鳴重力アシストおよび不変多様体tubeを用いた月遷移軌道の設計](https://www.researchgate.net/publication/404279619_Design_of_Earth-Moon_transfer_trajectories_using_multiple_resonance_gravity_assists_and_invariant_manifold_tubes)
-->

<!--
## 低推力推進を用いた人工平衡点の生成
### 関連論文
-->
