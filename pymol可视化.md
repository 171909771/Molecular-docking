## 寻找ligand周围5A的所有残基或则原子
![image](https://user-images.githubusercontent.com/41554601/219908496-73420f37-ecac-440b-8395-1c6894e32f41.png)

## 寻找ligand周围3.2A距离的H2O分子
### 2.8-3.2之间的是氢键
```
select ligand_water, ((ligand)around 3.2) and (resn HOH)
```

## 寻找pi-cation interaction,设定假原子
### 6.6A内都可以
```pseudoatom C25_center, sele```
