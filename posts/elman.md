# Elman Network 推導

$$
M_1 = \text{ReLU}\left(
\begin{bmatrix} 4 \\ 4 \end{bmatrix} +
\begin{bmatrix} 2 \\ 2 \end{bmatrix}
\right)
$$

```python
h_t = torch.relu(W_x @ x_t + W_h @ h_prev)
```
