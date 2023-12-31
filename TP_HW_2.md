
## ������ 1  

> ����������� ����, ��� ������� ������� � ������, ��������� ���� ���, ����� 0.8.
> ������� ��������� 100 ���.
>
>- ������� ����������� ����, ��� ������� ������� � ���� ����� 85 ���.

$$P_n(X=k) = C_n^k p^k q^{n-k}$$

���������� ������������� ������������� � �����������:

- k = 85
- n = 100
- p = 0.8
- q = 1 - p = 1 - 0.8 = 0.2

$P_{100}(X=85)=C_{100}^{85}{0.8}^{85}{0.2}^{100-85}=\frac{100!}{85!(100-85)!}0.8^{85}0.2^{25}=\frac{86\cdot87\cdot\cdot\cdot99\cdot100}{25!}0.8^{85}0.2^{25}=0.0481$

�����: 0.0481

## ������ 2

> ����������� ����, ��� �������� ��������� � ������� ������� ��� ������������, ����� 0.0004. � ����� ��������� ����� ������� � ���� ���� �������� 5000 ����� ��������.
>
>- ������ �����������, ��� �� ���� �� ��� �� ��������� � ������ ����?
>- ������ �����������, ��� ��������� ����� ���?

���������� ������������� ��������:

$P_m\approx\frac{\lambda^m}{m!}e^{-\lambda}$

- n = 5000
- p = 0.0004
- $e\approx2.72$
- $\lambda=pn=5000\cdot0.0004=2$ ��������

### 1. ������ �����������, ��� �� ���� �� ��� �� ��������� � ������ ����?

- m = 0

$P(0)\approx\frac{2^0}{0!}2.72^{-2}=1\cdot2.72^{-2}=0.1353$

�����: 0.1353

### 2. ������ �����������, ��� ��������� ����� ���?

- m = 2

$P(2)\approx\frac{2^2}{2!}2.72^{-2}=2\cdot2.72^{-2}=0.2703$

�����: 0.2707

## ������ 3

> ������ ���������� 144 ����.
>
>- ������ �����������, ��� ���� ������� ����� 70 ���?

� - ������ ������ 40 ���

- n = 144
- k = 70
- p = 0.5
- q = 0.5

$P_{144}(X=70) = C_{144}^{70}{0.5}^{70}{0.5}^{144-70}=\frac{144!}{70!(144-70)!}0.5^{70}0.5^{144-70}=0.0628$

�����: 0.0628

## ������ 4

>� ������ ����� ��������� 10 �����, �� ������� 7 - �����. �� ������ ����� - 11 �����, �� ������� 9 �����. �� ������� ����� ����������� ��������� ������� �� ��� ����.
>
>- ������ ����������� ����, ��� ��� ���� �����?
>- ������ ����������� ����, ��� ����� ��� ���� �����?
>- ������ ����������� ����, ��� ���� �� ���� ��� �����?

### 1. ������ ����������� ����, ��� ��� ���� �����?

B - ����, ������� �� ������� ����� ��� �����  
C - ����, ������� �� ������� ����� ��� �����  
� = B * C - ��� ���� �����

$P(B)=\frac{C_{7}^{2}}{C_{10}^{2}}=\frac{\frac{7!}{2!5!}}{\frac{10!}{2!8!}}=\frac{\frac{42}{2}}{\frac{90}{2}}=\frac{21}{45}=0.4667$

$P(C)=\frac{C_{9}^{2}}{C_{11}^{2}}=\frac{\frac{9!}{2!7!}}{\frac{11!}{2!9!}}=\frac{\frac{72}{2}}{\frac{110}{2}}=\frac{36}{55}=0.6545$

$P(A)=0.4667*0.6545=0.3055$

�����: 0.305

### 2. ������ ����������� ����, ��� ����� ��� ���� �����?

������������� ������

| ������ ������� | ������ ������� |
|:---:|:---:|
| 2 ����� | 2 ������ |
| 2 ������ | 2 ����� |
| ����� ������|����� ������|
| ������ �����|����� ������|
| ����� ������|������ �����|
| ������ �����|������ �����|

$P(A)=\frac{C_{7}^{2}}{C_{10}^{2}}\cdot\frac{C_{2}^{2}}{C_{11}^{2}}+\frac{C_{3}^{2}}{C_{10}^{2}}\cdot\frac{C_{9}^{2}}{C_{11}^{2}}+\frac{C_{7}^{1} * C_{3}^{1}}{C_{10}^{2}}\cdot\frac{C_{9}^{1} * C_{2}^{1}}{C_{11}^{2}}$

$P(A)+0.0084+0.0436+0.4666*0.3272=0.2047$  

�����: 0.2047

### 3. ������ ����������� ����, ��� ���� �� ���� ��� �����?

B - ��� ���� ������

$P(A)=1-P(B)$

$P(A)=1-\frac{C_{3}^{2}}{C_{10}^{2}}\cdot\frac{C_{2}^{2}}{C_{11}^{2}}=1-0.0012=0.9988$

�����: 0.9987