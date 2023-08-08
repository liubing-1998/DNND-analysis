# DNND-analysis

1、修改[draw_MLP_MLP_A_twoNode.py](https://github.com/liubing-1998/DNND-analysis/blob/main/draw_MLP_MLP_A_twoNode.py)文件中第364、365行代码路径加载不同k值训练的模型参数，绘制F、G图

```python

# DNND原始结果  HeatDynamics  k=0.1 
# python HeatDynamics.py --dynamic HeatDynamics --hidden_A_list 2 8 1 --hidden_list 0 --network grid --viz --dump --init_random --seed 456 --count 0 
filepath = r".\results/HeatDynamics/grid/result_HeatDynamics_grid_0802-231540_0.pth"
filename = r"grid/result_HeatDynamics_grid_0802-231540_0"

# HeatDynamics  k=1
filepath = r".\results\HeatDynamics\grid\result_HeatDynamics_grid_0802-232810_0_1.pth"
filename = r"result_HeatDynamics_grid_0802-232810_0_1"

# HeatDynamics  k=0.01
filepath = r".\results/HeatDynamics/grid/result_HeatDynamics_grid_0802-234155_0_2.pth"
filename = r"result_HeatDynamics_grid_0802-234155_0_2"

# k=5
filepath = r".\results/HeatDynamics/grid/result_HeatDynamics_grid_0808-015717_0_3.pth"
filename = r"result_HeatDynamics_grid_0808-015717_0_3"

# k=2
filepath = r".\results/HeatDynamics/grid/result_HeatDynamics_grid_0808-093420_0_4.pth"
filename = r"result_HeatDynamics_grid_0808-093420_0_4"

# k=1.5
filepath = r".\results/HeatDynamics/grid/result_HeatDynamics_grid_0808-094801_0_5.pth"
filename = r"result_HeatDynamics_grid_0808-094801_0_5"

# k=0.8
filepath = r".\results/HeatDynamics/grid/result_HeatDynamics_grid_0808-100743_0_6.pth"
filename = r"result_HeatDynamics_grid_0808-100743_0_6"

# k=0.5
filepath = r".\results/HeatDynamics/grid/result_HeatDynamics_grid_0808-102045_0_7.pth"
filename = r"result_HeatDynamics_grid_0808-102045_0_7"

```

