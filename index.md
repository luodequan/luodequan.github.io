# 个人信息
<table border="0">
  <tr>
    <td width="75%">
      <h2>罗志兴</h2>
      <p>博士、副教授</p>
      <p>南京大学工程管理学院</p>
      <p>邮箱：luozx@nju.edu.cn</p>
      <p>地址：江苏省南京市鼓楼区平仓5号</p>
    </td>
    <td width="25%">
      <img src="/image/罗志兴照片.png" width="100%">     
    </td>
  </tr>
</table>

# 获得荣誉

- 2018，获得京东[全球运筹优化挑战赛](https://jdata.jd.com/html/detail.html?tab=myteam&id=5)冠军
- 2019，入选年第五届中国科协青年人才托举工程
- 2021，获得江苏省系统工程青年科技奖

# 教育背景
- 2010.9 - 2014.7，香港城市大学商学院，博士
- 2007.9 - 2010.7，华南理工大学计算机科学与工程学院，学士

# 工作经历
- 2014.11 - 至今，[南京大学工程管理学院](https://sme.nju.edu.cn)，助理研究员、副教授


# 研究兴趣

1. **运筹优化算法设计**，包括branch-and-price、branch-and-cut、Benders decomposition、Lagrangian relaxation、tabu search、adaptive large neighborhood search等。
2. **组合优化问题**，包括车辆路径问题、装箱问题、网络规划问题、排产问题、排班问题等。

# 学术研究

## 代表论文

1. Sheng Liu and **Zhixing Luo\***. On-demand delivery from stores: dynamic dispatching and routing with random demand. [Manufacturing & Service Operations Management](https://pubsonline.informs.org/doi/abs/10.1287/msom.2022.1171), forthcoming, 2022.
2. Jiliu Li, **Zhixing Luo**, Roberto Baldacci, Hu Qin andZhou Xu. A new exact algorithm for single-commodity vehicle routing with split pickups and deliveries. [INFORMS Journal on Computing](https://pubsonline.informs.org/doi/abs/10.1287/ijoc.2022.1249), forthcoming, 2022.
3. **Zhixing Luo**, Hu Qin, T.C. Cheng, Qinghua Hu and Andrew Lim. A branch-and-price-and-cut algorithm for the cable routing problem in solar power plants. [INFORMS Journal on Computing](https://pubsonline.informs.org/doi/abs/10.1287/ijoc.2020.0981), 33 (2), 452-476, 2021.
4. Zhenzhen Zhang, **Zhixing Luo\***, Roberto Baldacci and Andrew Lim. A Benders decomposition approach for the multi-vehicle production routing problem. [Transportation Science]()，55 (1), 160-178, 2021.
5. Lijun Wei, **Zhixing Luo\***, Roberto Baldacci and Andrew Lim. A new branch-and-price-and-cut algorithm for one-dimensional bin packing problems. [INFORMS Journal on Computing](https://pubsonline.informs.org/doi/abs/10.1287/ijoc.2018.0867) 32 (2), 428-443, 2020.
6. Zhenzhen Zhang, **Zhixing Luo\***, Hu Qin and Andrew Lim. Exact Algorithms for the Vehicle Routing Problem with Time Windows and Combinatorial Auction. [Transportation Science](https://pubsonline.informs.org/doi/abs/10.1287/trsc.2018.0835) 53 (2), 427-441, 2019.
7. **Zhixing Luo\***,  Mengyang Liu and Andrew Lim. A two-phase branch-and-price-and-cut for a dial-a-ride problem in patient transportation. [Transportation Science](https://pubsonline.informs.org/doi/abs/10.1287/trsc.2017.0772) 53 (1), 113-130, 2019.
8. **Zhixing Luo**, Hu Qin, Wenbin Zhu and Andrew Lim, Branch-and-price-and-cut for the split-delivery vehicle routing problem with time windows and linear weight-related cost. [Transportation Science](https://pubsonline.informs.org/doi/abs/10.1287/trsc.2015.0666) 51 (2), 668-687, 2016.

关于本人全部论文请访问[Google Scholar](https://scholar.google.com.hk/citations?user=7t1AjR8AAAAJ&hl=en)。

## 科研项目

- 电子商务企业物流配送车辆调度研究，国家自然科学基金青年项目， 2016-2018， 主持人
- 大型连锁商超复杂车辆调度优化问题研究，国家自然科学基金面上项目，2022-2025， 主持人
- 物流系统建模和算法设计，国家自然科学基金优秀青年项目，2023-2025，主持人

# 社会服务

1. 开发[车辆路径问题](https://wiki.mbalib.com/wiki/%E8%BD%A6%E8%BE%86%E8%B7%AF%E5%BE%84%E9%97%AE%E9%A2%98)和[装箱问题](https://baike.baidu.com/item/%E8%A3%85%E7%AE%B1%E9%97%AE%E9%A2%98)算法包，服务广大企业

该算法包基于10多年关于车辆路径问题和三维装箱问题研究积累，于2018年获得[京东全球运筹优化挑战赛](https://jdata.jd.com/html/detail.html?tab=myteam&id=5)冠军，具有以下特性：
1. **基于配送模式、约束和目标函数的问题建模**。
2. **内置丰富的约束条件和目标函数**，支持丰富的业务场景。
3. **支持多线程并发**，既适用于计算时间要求苛刻的业务场景，也适用计算时间要求相对宽松但追求高质量解的业务场景。
4. **支持二次开发**，只需要实现给定的接口就可以轻松处理新的约束和目标函数。
5. **支持远程API调用**，关于API格式请联系本人。

目前算法包内置的约束条件和目标函数包括但不限于：

  | 问题 | 约束条件和目标函数 |
  | --- | --- |
  | 车辆路径 | 常规配送模式 |
  |  | 取货送货模式 |
  |  | 需求可拆分模式 |
  |  | 各类容量约束和智能拆单，包括三维装箱约束 |
  |  | 各类时间窗约束，包括订单的备货和送达时间窗、仓库的工作时间窗、车辆的工作时间窗等 |
  |  | 各类匹配约束，包括订单-车型、订单-仓库、车型-区域等 |
  |  | 多车型、多仓库、多行程 | 
  |  | 各种复杂的成本计算方式 |
  | 三维装箱 | 各类支撑约束，包括支撑面积、支撑重量等 |
  |  | 各类装车约束，包括LIFO装箱规则、叉车进出宽度等 |
  |  | 各类摆放约束，包括物品摆放高度、堆叠层数等 |
  |  | 成套装载 |
  |  | 各类目标函数，包括最大化装载率、最小化箱子数量、平衡车辆重心等 |

### 案例

目前已经落地的代表项目包括：
1. 某头部电信设备制造企业三维装载与车辆路径规划项目。
2. 某头部家电制造企业智能车辆调度项目。
3. 某医药企业药物配送项目。
