# Productivity-and-Efficiency-Analysis
### **內容概述**

This webpage provides supporting materials for the course [Productivity and Efficiency Analysis](https://nol.ntu.edu.tw/nol/coursesearch/print_table.php?course_id=725%20U3680&class=&dpt_code=7050&ser_no=41440&semester=110-2&lang=CH)

Instructor: [Chia-Yen Lee, Ph.D.](http://polab.im.ntu.edu.tw/Bio.html)


### **助教**

|擔任年份|助教 TAs|信箱 :mailbox_closed:|
|----|----|----|
|2022|吳延東 (Yen-Tung Wu)<br>江采嬪 (Tsai-Pin Chiang)|r09725049@ntu.edu.tw<br>r10725034@ntu.edu.tw

----------------------------------------
# Data-Envelopment-Analysis
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)<br>

在此主要透過一些範例來說明如何利用Python-Gurobi來建構資料包絡分析模組(Data-Envelopment-Analysis, DEA)

### § Requirements

- python 3.6

- gurobipy 6.5.2 以上版本

### § DEA Models
此區文章主要針對以下DEA模型進行簡介，並說明Python-Gurobi的建模流程：

- CRS(constant return to scale; input-oriented) ：固定規模報酬投入導向模型

- VRS(variable return to scale; input-oriented) ：變動規模報酬投入導向模型

- Relational network DEA Model ：關聯網絡DEA模型

|更新時間|文章|
|---|---|
|2018-01-29|[CRS Model](https://github.com/wurmen/DEA/blob/master/CRS_Model/CRS%20model.md)|
|2018-02-05|[VRS Model](https://github.com/wurmen/DEA/blob/master/VAS_Model/VRS%20model.md)|
|2018-01-30|[Relational network DEA Model](https://github.com/wurmen/DEA/blob/master/Network_DEA/network_dea.md)|

### § DEA Models Functions
針對上述DEA模型建構幾個簡單的DEA擴充函數，讓使用者能夠更輕鬆的利用這些DEA函數來進行效率分析，或者可由這些已建好的函數去做延伸。<br>

以下連結分別對應到每個主題的說明文章、範例文章、程式碼以及檔案資料夾(內部包含該主題的所有資源)，可根據說明文章自行下載操作學習。

|更新時間|文章|連結|
|---|---|---|
|2018-03-23|DEA Functions Instructions|[Documentation](https://github.com/wurmen/DEA/blob/master/Functions/user's%20guide.md)|
|2018-03-23|Read data functions for basic DEA models|[Documentation](https://github.com/wurmen/DEA/blob/master/Functions/read_data_function.md) / [Example](https://github.com/wurmen/DEA/blob/master/Functions/basic_DEA_data%26code/read_data_example.ipynb) / [Code](https://github.com/wurmen/DEA/blob/master/Functions/basic_DEA_data%26code/DEA.py) / [Folder](https://github.com/wurmen/DEA/tree/master/Functions/basic_DEA_data%26code)|
|2018-03-23|Basic DEA functions|[Documentation](https://github.com/wurmen/DEA/blob/master/Functions/basic_dea_functions.md) / [Example](https://github.com/wurmen/DEA/blob/master/Functions/basic_DEA_data%26code/basic_DEA_function.ipynb) / [Code](https://github.com/wurmen/DEA/blob/master/Functions/basic_DEA_data%26code/DEA.py) / [Folder](https://github.com/wurmen/DEA/tree/master/Functions/basic_DEA_data%26code)|
|2018-03-23|Read data function for network DEA|[Documentation](https://github.com/wurmen/DEA/blob/master/Functions/read_data_for_networkDEA.md) / [Example](https://github.com/wurmen/DEA/blob/master/Functions/network_data%26code/Read_data_for_network_DEA_function%20example.ipynb) / [Code](https://github.com/wurmen/DEA/blob/master/Functions/network_data%26code/network_function.py) / [Folder](https://github.com/wurmen/DEA/tree/master/Functions/network_data%26code)|
|2018-03-23|Relational network DEA function|[Documentation](https://github.com/wurmen/DEA/blob/master/Functions/network_DEA_function.md) / [Example](https://github.com/wurmen/DEA/blob/master/Functions/network_data%26code/Network_DEA_function_example.ipynb) / [Code](https://github.com/wurmen/DEA/blob/master/Functions/network_data%26code/network_function.py) / [Folder](https://github.com/wurmen/DEA/tree/master/Functions/network_data%26code)|
--------

### **Data Envelopment Analysis (DEA) Examples**
1. [數據包絡分析概論(Introduction to Data Envelopment Analysis)](https://github.com/gary60405/Data-Envelopment-Analysis-Tutorial)
2. [數據包絡分析(Data Envelopment Analysis)](https://github.com/PO-LAB/Data-Envelopment-Analysis)
3. [網路數據包絡分析(Network Data Envelopment Analysis)](https://github.com/wurmen/DEA/blob/master/Network_DEA/network_dea.md)
4. [隨機無母數數據包絡(Stochastic Nonparametric Envelopment of Data, StoNED)](https://pystoned.readthedocs.io/en/latest/#)
5. [汙染物邊際減排成本估計(Marginal Abatement Cost Estimation of CO2, SO2, and NOx)](https://github.com/JaneChien-42/DSP-Estimation-of-Pollutants)
6. [保險業效率分析-網路DEA(Efficiency Measure in Insurance Industry- Network DEA)](https://github.com/wuyentung/ORA_final_project/blob/main/Efficiency%20Measure%20in%20Insurance%20Industry%20–%20A%20Network%20DEA%20Model.md)

### :triangular_flag_on_post: Python+Pulp
|更新時間|文章|
|---|---|
|2018-10-03|[Pulp簡介與下載](https://github.com/jasonyoyo/python-pulp/blob/master/Pulp%20%E7%B0%A1%E4%BB%8B%E8%88%87%E4%B8%8B%E8%BC%89.md)|
|2018-11-03|[Python+Pulp基本架構](https://github.com/jasonyoyo/python-pulp/blob/master/Python%2BPulp%E5%9F%BA%E6%9C%AC%E6%9E%B6%E6%A7%8B.md)|
|2018-10-03|[Python+Pulp建模](https://github.com/jasonyoyo/python-pulp/blob/master/Python%2BPulp%E5%BB%BA%E6%A8%A1.md)|
|2018-11-03|[Python+Pulp特殊資料結構](https://github.com/jasonyoyo/python-pulp/blob/master/Python%2BPulp%E7%89%B9%E6%AE%8A%E8%B3%87%E6%96%99%E7%B5%90%E6%A7%8B.ipynb)|

### :triangular_flag_on_post: Python+Pulp範例
|更新時間|文章|
|-----|-----|
|2018-11-08|[A blending problem](https://github.com/jasonyoyo/python-pulp/blob/master/A%20blending%20problem.md)|

### :triangular_flag_on_post: Gurobi介紹
|更新時間|文章|
|---|---|
|2018-04-03|[Gurobi簡介](https://github.com/wurmen/Gurobi-Python/blob/master/gurobi_introduction.md)|

### :triangular_flag_on_post: 環境建置
|更新時間|文章|
|-----|-----|
|2017-09-27|[安裝教學](https://github.com/wurmen/Gurobi-Python/blob/master/Installation/%E5%AE%89%E8%A3%9D%E6%95%99%E5%AD%B8.md)|
|2017-11-03|[Linux安裝](https://github.com/PO-LAB/Python-Gurobi/blob/master/Installation/installation-for-linux.md)|

### :triangular_flag_on_post: Python+Gurobi建模
|更新時間|文章|
|-----|-----|
|2017-09-27|[Python+Gurobi基本架構](https://github.com/wurmen/Gurobi-Python/blob/master/python-gurobi%20%20model/Python+Gurobi%E5%9F%BA%E6%9C%AC%E6%9E%B6%E6%A7%8B.md)|
|2017-10-08|[Python+Gurobi建模](https://github.com/wurmen/Gurobi-Python/blob/master/python-gurobi%20%20model/Python+Gurobi%E5%BB%BA%E6%A8%A1.md)|
|2017-10-30|[Python+Gurobi特殊資料結構](https://github.com/wurmen/Gurobi-Python/blob/master/python-gurobi%20%20model/Python%2BGurobi%E7%89%B9%E6%AE%8A%E8%B3%87%E6%96%99%E7%B5%90%E6%A7%8B.ipynb)|

### :triangular_flag_on_post: Python+Gurobi範例
|更新時間|文章|
|-----|-----|
|2017-10-08|[Prototype example type1](https://github.com/wurmen/Gurobi-Python/blob/master/python-gurobi%20%20model/Prototype%20example_type1.md)| 
|2017-10-08|[Prototype example type2](https://github.com/wurmen/Gurobi-Python/blob/master/python-gurobi%20%20model/Prototype%20example_type2.md)|
|2017-10-08|[Controlling Air Pollution type1](https://github.com/wurmen/Gurobi-Python/blob/master/python-gurobi%20%20model/Controlling%20Air%20Pollution_type1.md)|
|2017-10-08|[Controlling Air Pollution type2](https://github.com/wurmen/Gurobi-Python/blob/master/python-gurobi%20%20model/Controlling%20Air%20Pollution_type2.md)|
|2017-10-30|[Dual example](https://github.com/wurmen/Gurobi-Python/blob/master/python-gurobi%20%20model/Dual%20example.md)|
|2017-10-30|[Optimal Employee Work Schedule](https://github.com/wurmen/Gurobi-Python/blob/master/python-gurobi%20%20model/Optimal%20Employee%20Work%20Schedule.md)|
|2017-11-04|[Netflow problem](https://github.com/wurmen/Gurobi-Python/blob/master/python-gurobi%20%20model/Netflow%20problem.md)|

