# Markdown Reference

## Math Blocks

You can render *Latex* mathematical expressions using **MathJax**.

Input $$, then press `Return` key will trigger an input field with accept *Tex/Latex* source. Following is a example:
$$
\mathbf{V}_1\times \mathbf{V}_2=\left|\begin{array}{c}
\boldsymbol{i} & \boldsymbol{j} & \boldsymbol{k} \\
\frac{\partial X}{\partial \boldsymbol{u}} & \frac{\partial Y}{\partial \boldsymbol{u}} & 0 \\
\frac{\partial X}{\partial \boldsymbol{v}} & \frac{\partial Y}{\partial \boldsymbol{v}} & 0 \\
\end{array}\right|
\tag{1}
$$
In markdown source file, math block is *Latex* expression wrapped by `$$` mark:

```latex
$$
\mathbf{V}_1 \times \mathbf{V}_2=\left|\begin{array}{c}
\boldsymbol{i} & \boldsymbol{j} & \boldsymbol{k} \\
\frac{\partial X}{\partial \boldsymbol{u}} & \frac{\partial Y}{\partial \boldsymbol{u}} & 0 \\
\frac{\partial X}{\partial \boldsymbol{v}} & \frac{\partial Y}{\partial \boldsymbol{v}} & 0 \\
\end{array}\right| \tag{1}
$$
```

## Quote Examples

> This is a quote block example

