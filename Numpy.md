# Numpy

### reshape

```python
#shape是查看数据有多少行多少列
#reshape()是数组array中的方法，作用是将数据重新组织
reshape(1,-1) #转成一行
reshape(-1,1) #转成一列
```

### mean

```python
#numpy.mean(a, axis, dtype, out，keepdims)
#axis 不设置值，对 m*n 个数求均值，返回一个实数
#axis = 0：压缩成行，对各列求均值，返回 1* n 矩阵
#axis = 1 ：压缩成列，对各行求均值，返回 m *1 矩阵
```

### std

```python
#计算标准差
#如mean
```

### zeros

```python
#zeros(shape, dtype=float, order=‘C’)
#返回来一个给定形状和类型的用0填充的数组
#shape:形状
#dtype:数据类型，可选参数
#order:可选参数，c代表与c语言类似，行优先；F代表列优先

```

### ones

```python
#类似zeros，1填充数组
```



### concatenate

```python
#数组拼接功能
numpy.concatenate((a1, a2, ...), axis=0, out=None)
#axis = 0 上下拼接 行增加了
#axis = 1 左右拼接
```

### astype

```python
#类型转换
```

### exp

```python
# e的x次方
```

### sqrt

```python
#求x的开方
```

### sum

> sum(a, axis=None, dtype=None, out=None, keepdims=np._NoValue)
>
> #axis的取值有三种情况：1.None，2.整数， 3.整数元组。
>
> #axis = None r return 一个值
>
> #类似mean
>
> #当axis为0时,是压缩行,即将每一列的元素相加,将矩阵压缩为一行
> #当axis为1时,是压缩列,即将每一行的元素相加,将矩阵压缩为一列