# TIL(git νΉκ°) πβ°(*Β°β½Β°*)β―

> 2021-12-30 μ λ°°μ΄ λ§ν¬λ€μ΄ μΈμ΄μ λν λ³΅μ΅μ μ£Όμ λ‘ νλ€
>
> Ctrl + / λ‘ λ§ν¬λ€μ΄ λ¬Έλ²μ΄ μ΄μ° μμ±λμλ νμΈν μμλ€
>
> μΈμ©λ¬Έμ ν¬ν¨ν listλ€μ Enterν€λ₯Ό λλ²μ λ λλ₯΄λ©΄ λ²μ΄λ μμλ€.

## 1. λ§ν¬ λ€μ΄ κΈ°μ΄λ¬Έλ²

### 1.1`#` Header

`#` μ λν κ²μΈλ° κΈ°μ΄μ μΌλ‘ `#`μ λν λ΄μ©μ΄λ©° `#`μ κ°―μλ‘ λͺ©μ°¨λ₯Ό λλμ μμΌλ©° λ¬Έμμ λΌλ¦¬μ  νλ¦μ λ§μΆ°μ€μμλ€.

- `#` μ κ°μλ‘ νννκ±°λ `<h1></h1>` μ ννλ‘ νν κ°λ₯ν©λλ€.


# `#` νλ²μλλ€.

## `#` λλ²μλλ€.

### `#` μΈλ²μλλ€.

#### `#` λ€λ²μλλ€.

<h5> htmlνκ·Έμλλ€</h5>

###### `#` λ€μ― λ²μλλ€.

### 1.2`>` μΈμ©λ¬Έ

* `>` κ°μ κ²½μ°λ μΈμ©λ¬ΈμΌλ‘ μ’μΈ‘μ νμ μ€μ΄ νμκ° λλ€ 
* μ€μ²©ν΄μ μ¬μ©κ°λ₯νλ€ 

> for i in range(10):
>
> > print(i)



### 1.3 list

> λͺ©λ‘ λμ΄μ νμνλ€ '*' λλ '-'μΌλ‘ νμ νλ©° κ·Έ μν° νμ `tab`ν€λ‘ 
>
> λ€μ λ€μ¬μ°κΈ°λ₯Ό μμ±ν μμλ€.

* μμκ° μλ λͺ©λ‘
  * 1.  '1.'μ λλ₯Έ λ€μ μ€νμ΄μ€ λ°λ₯Ό λλ₯΄λ©΄ 1,2,3,4 λ‘ λ²νΈκ° λ§€κ²¨μ§λ λ¦¬μ€νΈλ‘€ μμ±κ°λ₯νλ€
* μμκ° μλ λͺ©λ‘
  * `-` (νμ΄ν) λλ `*` μ μ°κ³  μ€νμ΄μ€ λ°λ₯Ό λλ₯΄λ©΄ μμ±ν μμλ€
    * λν λ€μμ `tab`ν€λ₯Ό λλ₯΄λ©΄ μ΄μκ°μ΄ λ€μ μ΄λ‘ λ°κΏμμλ€.

μμ)

1. μμκ° μλν­λͺ©1
2. μμκ° μλ ν­λͺ© 1.1
   1. μμκ° μλν­λͺ© 2
   2. μμκ° μλν­λͺ© 2.1

* μμκ° μλ ν­λͺ©
* μμκ° μλ ν­λͺ©
  * μμκ° μλ νμ
  * μμκ° μλ νμ
    * μμκ° μλ νμ2
      * μμκ° μλ νμ3



### 1.4 Code Block

>  μ λ¦¬ νΉμ κ°μ‘°νκ³  μΆμλ μ°λ©΄ `(λ°±ν±)μΌλ‘ κ°μΈμ€μμλ€
>
> μΈλΌμΈκ³Ό λΈλ­μΌλ‘ λ¨μλ₯Ό κ΅¬λΆν μμλ€.
>
> \`#`  λ¬Έμμ΄ μ΄μ€μΌμ΄ν   λ§ν¬λ€μ΄ λ¬Έλ²μ μκ΄μμ΄ μ°κ³ μΆμλ 
>
> `` ` `` 	λ°±ν± μμ λ°±ν±μ΄ λΈλ­λλ νμ

* lnline

  * μΈλΌμΈ λΈλ­μΌλ‘ μ²λ¦¬νκ³  μΆμ λΆλΆμ `(λ°±ν±) μΌλ‘ κ°μΈμ€λ€.

* block

  * λ°±ν±μ 3λ² μλ ₯νλ©΄ μ¬μ©κ°λ₯νλ©° μΈμ΄ ν­λͺ©μ νμ΄μ¬μ κ³ λ₯΄λ©΄ νμ΄μ¬ νμμ΄ κ°λ₯νλ€

  ex) μ νμ€ νμ΄λΌμ΄ν μ΄λΌκ³  λΆλ₯΄κΈ°λ νλ€.

  ```python
  for i in range(10):
      print(i)
  ```

  



### 1.5 limage

> μ΄λ―Έμ§ μΊ‘μ³μμ μ¬μ©κ°λ₯ νλ€
>
> Shift + windows + s λ‘ νλ©΄ μ¦μ μΊ‘μ³κ° κ°λ₯νλ€.

![image-20211230155241537](TIL.assets/image-20211230155241537.png)

### 1.6 Link

> νΉμ μ£Όμ  λ§ν¬λ₯Ό κ±Έλ μ¬μ©ν©λλ€.
>
> Ctrl + μΌν΄λ¦­μΌλ‘ λ§ν¬μ μ μν μμλ€.

* `[]()` μ μμ±νκ³  `()` μμ λ§ν¬ μ£Όμλ₯Ό μμ±νκ³  `[]` μμ μ΄λ€ λ§ν¬ μ£ΌμμΈμ§ μμ±ν©λλ€.

[git κ³΅μλ¬Έμ](https://git-scm.com/)

[github κ³΅μλ¬Έμ](https://github.com/)



### 1.7  Table

> νλ₯Ό μμ± ν μμλ€.

* |(νμ΄ν) ν λμ΄μ°κΈ° '| | |' λ₯Όνλ©΄ μμ±μ΄λ€.
  * νμ Ctrl + Enter λ‘ μ΄λλ¦¬κΈ°κ° κ°λ₯νλ€
  * λλ ν μ’μΈ‘μλ¨μμ μ΄κ³Ό νμ λΉκ΅μ  μμ λ‘­κ² νΈμ§ν  μ μλ€.

| working directory | statging area |
| ----------------- | ------------- |
| working tree      | index         |



### 1.8 κΈ°ν

#### 1. μνμ 

* `---`,`***`,`___` μ μ¬μ©νμ¬ μμ±νλ€.

work space area

---

staging area

___



***





#### 2. κ°μ‘°

- μ΄ν€λ¦­μ²΄λ ν΄λΉ λΆλΆμ `*` νΉμ `_` (μΈλλ°) λ‘ κ°μΈμ€λλ€.
- λ³΄λμ²΄λ ν΄λΉ λΆλΆμ `**` νΉμ `__` (μΈλλ° 2κ°)λ‘ κ°μΈμ€λλ€.
- μ·¨μμ μ `~~` νμλ₯Ό μ¬μ©ν©λλ€.

μ΄κ²μ *μ΄ν€λ¦­μ²΄*μλλ€.

μ΄κ²μ **λ³΄λμ²΄**μλλ€.

μ΄κ²μ ~~μ·¨μμ ~~μλλ€.



## 2. Git 

### 2.1 κΈ°μ΄ κΈ°λ³Έ λͺλ Ήμ΄

| λͺλ Ήμ΄ | κΈ°λ₯                                                     |
| ------ | -------------------------------------------------------- |
| ls     | νμ¬ μμΉκ²½λ‘μ μλ νμΌλ€μ λ³΄μ¬μ€                     |
| cd     | change directory κ²½λ‘ μ΄λ κ°λ₯ (./) μ΄λ©΄ λ€μ (../)μ΄λ©΄ |
| clear  | ν°λ―Έλ νλ©΄ μ§μ°κΈ°                                       |
| touch  | 'νμΌ'μ λ§λ¬                                            |
| mkdir  | ν΄λλ₯Ό λ§λ¬                                              |
| start  | νμΌ μ΄κΈ°,μ€ν                                           |
| rm     | μ­μ  λͺλ Ήμ΄                                              |
| mv     | νμΌ μ΄λ λͺλ Ήμ΄                                         |
| code . | ν΄λΉ κ²½λ‘μμ vscode μ΄κΈ°                                |

#### 2.1.1 κ°λͺλ Ήμ΄ μΈλΆ λ΄μ©

> λ΄ μ»΄ν¨ν°μμ ν΄λ κ²½λ‘ κΈμ΄μ¬λ `/`λ₯Ό `\`λ‘ λ°κΏμ€μΌ ν  μ λμλ€.

* la -a μ¨κΉνμΌλ λ³΄κ² ν΄μ€
* mkdir test  testλΌλ μ΄λ¦μ  ν΄λ νμ¬ μμΉμ μμ±
* touch a.txt   aλΌλ μ΄λ¦μ txtνμΌ νμ¬ μμΉμ μμ±
* mv [μ΄λν  νμΌλͺ] [μ΄λν  μμΉ],  mv [μ΄λν  νμΌλͺ] [μ΄λν  ν΄λμ΄λ¦]
  * mv **file1 file2** dir1 νλ²μ μ΄λ κ°λ₯
* rm νμΌμ­μ  -> rm a.txt
  * ν΄λμ­μ  -> rm -r ν΄λμ΄λ¦
  * rm *.txt ν΄λΉ νμΌ κ²½λ‘ μμ txtνμ₯μμΈ νμΌ μ λΆ μ­μ 
    rm -rf * ν΄λΉ κ²½λ‘ ν΄λμμ νμΌ κ°μ λ‘ μ­μ 

### 2.2 git & vscode

vscode λ₯Ό μ΄μ©ν΄μ gitμ μ¬μ©νλ λ°©λ²μ λν κ²μ΄λ©° μλλ κ·Έ μμ λ‘ 

gitμ μ¬μ©νμ¬ μ¬μ©ν  κ²½λ‘μ vscodeλ₯Ό ν€κ³  ν΄λλ₯Ό νλ λ§λ€μ΄μ κ·Έ ν΄λλ₯Ό gitμ λ±λ‘νκ³  κ·Έ λ΄λΆ νμΌμ gitμ λ±λ‘ν΄μ κ·Έλμμ λ²μ μ΄ κΈ°λ‘λλλ‘ λ§λ€μλ€.

1. mkdir μ μ¬μ©ν΄μ `/c/Users/μ΄μ¬μ`κ²½λ‘μ git_practice νμΌμ λ§λ λ€

![μ λͺ© μμ1](TIL.assets/μ λͺ© μμ1.png)

2. ls λͺλ Ήμ΄λ‘ νμΌμ΄ λ§λ€μ΄ μ§κ²μ νμΈνκ³ 

![μ λͺ© μμ](TIL.assets/μ λͺ© μμ.png)

3. cd git_practice λ₯Ό μ¬μ©νμ¬ git_P ν΄λ μμΌλ‘ λ€μ΄κ°λ€
 κ·Έλ€μ μ git_practice μμμ `code .`λ₯Ό μλ ₯ν΄μ ν΄λΉ νμΌμμ vscodeλ₯Ό μ΄μ΄μ€λ€.

![image-20211230210215492](TIL.assets/image-20211230210215492.png)

4. κ·Έλ€μμ ν΄λμμ μ΄λ¦° vscode ν°λ―Έλμ μ¬μ©ν΄μ `touch` λ‘ κ°λ¨νκ² txtνμΌμ νλ μμ±νλ€.

> μΌμͺ½ νμΌμ μμ± κ²°κ³Όλ₯Ό λ³΄μ¬μ£ΌκΈ° μν΄ ν¬κ² μΊ‘μ³νλ€.

![image-20211230210821902](TIL.assets/image-20211230210821902.png)

5. κ·Έλ€μ git initμ μΉκ²λλ©΄ gitμ΄ ν΄λΉ ν΄λλ₯Ό μΆμ ν΄μ μ μ₯νκ² λλ€ 

β	μλκ·Έλ¦Όμ μλ νμΌ μ€λ₯Έμͺ½μ Uλ untracked μ΄νμΌμ μΆμ νκ³ μμ§ μλ€ λΌλ 	λ»μ΄λ©°  ν΄λλ μΆμ μ νμ§λ§ ν΄λ μμ λ΄μ©λ¬Όμ μμ§ μΆμ νκ³ μμ§ μλ€λ λ»μ΄	λ€.

![image-20211230211016170](TIL.assets/image-20211230211016170.png)

![image-20211230211149063](TIL.assets/image-20211230211149063.png)

λ°λ‘ μμ¬μ§μ λ³΄λ©΄ κ²½λ‘ μ°μΈ‘λμ (master)μ΄ μκΈ°λ©° μ¨κΉ νμΌλ‘ `.git/`μ΄ μλ‘ μμ±λμμ μμμλ€ `.git/` κ°μ κ²½μ° ν΄λκ° gitμ λ±λ‘λμλ€λ λ»μ΄λλ€.



6. κ·Έν νμΌμ `git add (νμΌμ΄λ¦).(νμ₯μ)`νλ€  new file λ¬Έκ΅¬μ ν¨κ» test.txtκ° λ¬Έμ  μμ΄ gitμμ μΈμνμμ μμμλ€

β		ν΄λΉ gitμ μνλ `git status`λ‘ νμΈν μμλ€.

![image-20211230211428456](TIL.assets/image-20211230211428456.png)

![image-20211230211610744](TIL.assets/image-20211230211610744.png)

β		νμΌμ Uκ° A add index λ‘ λ°λκ² λλ€.

7. `git commit -m 'μ»€λ°λ©μμ§'`λ‘ νμΌ μλ°μ΄νΈ

![image-20211230211850465](TIL.assets/image-20211230211850465.png)

8. `git log`λ‘ logλ₯Ό νμΈν μμμΌλ©° `git log --oneline`μΌλ‘ μ½λλ₯Ό μ£Όμμ μ»€λ°μ νλ²μ νμΈν μμλ€.

* ![image-20211230212414787](TIL.assets/image-20211230212414787.png)
* `git log --oneline` μ μ¬μ©νλ©΄ μλμ κ°μ΄ λ¨μΆν μ μλ€.

β	μ»€λ° μ£Όμμ μ»€λ° λ©μμ§κ° λμ€λ©° HEADλ κ°μ₯ λ§μ§λ§μ μ€νμ μ μ₯λ κΈ°λ‘μ΄λ€.

![image-20211230212620412](TIL.assets/image-20211230212620412.png)



#### μΆκ°λ΄μ©

gitμμ μ΄μ  λ²μ μ νμΈνκΈ° μν 2κ°μ λͺλ Ήμ΄κ° μλλ° νλλ

`git checkout head ~2 `2κ° μ μ λ³΄μ¬μ£Όκ³ 

`git checkout μ»€λ°λ©μμ§ μ£Όμ`μ΄λ€ 

μλ λͺλ Ήμ΄λ₯Ό λ³΄μ¬μ£Όλ©΄

![image-20211230213026979](TIL.assets/image-20211230213026979.png)

![image-20211230213015737](TIL.assets/image-20211230213015737.png)

ν΄λΉ μ»€λ° μ£Όμκ° νλ λ΄μ©μΌλ‘ λμκ°λ©° masterλ μ»€λ°μ£Όμλ‘ λ°λκ² λλ€.

λ€μ λμκ°λ λ°©λ²μ

`git checkout master`μ΄λ€.



#### vscode μΆκ°λ΄μ©

![image-20211230213415724](TIL.assets/image-20211230213415724.png)

vscode μ’μΈ‘νλ¨μ TIMELINEμμλ νμΈ κ°λ₯νλ©° 

![image-20211230213439563](TIL.assets/image-20211230213439563.png)

μ’μ°λ‘ κ΅¬λΆλΌ λ¬΄μμ΄ μΆκ°/μ­μ κ° λμλμ§ GUIλ‘ νμΈν  μ μλ€.

> νμ§λ§ λλ¬΄ νΉμ ν΄μ κΈ°λ₯μλ§ μμ§νμ§λ μλλ‘ νμ

### 2.3 μ£Όμ

ν΄λΉ νμκ° μλ€λ©΄ νμΌμ λ¨Όμ  `μ μ₯`ν νμ μμμ μ§μνλλ‘ νμ

![image-20211230212134357](TIL.assets/image-20211230212134357.png)

