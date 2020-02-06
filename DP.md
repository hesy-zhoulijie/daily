# 动态规划
## 斐波那契数列
1 2 3 4 5 6  7  8
1 1 2 3 5 8 13 21

fib(n)={1(n=1 or n=2),fib(n-1)+fib(4)}
### O( 2ˆn )
```cpp
fib(7){
    fib(6){
        fib(5){
            fib(4){
                fib(3){
                    fib(2)
                    fib(1)
                }
                fib(2)
            }
            fib(3){
                fib(2)
                fib(1)
            }
        }
    }
    fib(5){
        fib(4){
            fib(3){
                fib(2)
                fib(1)
            }
            fib(2)
        }
        fib(3){
            fib(2)
            fib(1)
        }
    }
}
```
![image.png](https://i.loli.net/2020/01/31/EolYBri7yW9fnq3.png)

## DP经典题目：最大值
$$ OPT(i)  $$
```math
OPT(8):
\{ 
\text{选}4+OPT(5),\text{不选}OPT(7);
```
![image.png](https://i.loli.net/2020/01/31/oEajnh7xeDUymB2.png)
