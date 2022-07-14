헤더입니다. 아래에 === 을 추가하면 헤더가 됩니다. H1
=====================================================


    헤더입니다. 아래에 === 을 추가하면 헤더가 됩니다. H1
    =====================================================



작은 헤더입니다. 아래에 --- 을 추가하면 작은 헤더가 됩니다 H2
-----


    작은 헤더입니다. 아래에 --- 을 추가하면 작은 헤더가 됩니다 H2
    -----




# H1 글머리
## H2 글머리
### H3 글머리
#### H4 글머리
##### H5 글머리
###### H6 글머리


    # H1 글머리
    ## H2 글머리
    ### H3 글머리
    #### H4 글머리
    ##### H5 글머리
    ###### H6 글머리





# 블럭 인용

> 1단 건너기
> > 2단 건너기
> > > 3단 ....


    > 1단 건너기
    > > 2단 건너기
    > > > 3단 ....



# 순서 있는 목록
```
1. 첫번째
2. 두번째
3. 세번째
```
1. 첫번째
2. 두번째
3. 세번째

**현재까지는 어떤 번호를 입력해도 순서는 내림차순으로 정의된다.**
```
1. 첫번째
3. 세번째
2. 두번째
```
1. 첫번째
3. 세번째
2. 두번째


# 순서 없는 목록
* + - 사용

```
* 빨강
  * 녹색
    * 파랑

+ 빨강
  + 녹색
    + 파랑

- 빨강
  - 녹색
    - 파랑
```
* 빨강
  * 녹색
    * 파랑

+ 빨강
  + 녹색
    + 파랑

- 빨강
  - 녹색
    - 파랑

혼합해서 사용하는 것도 가능하다(내가 선호하는 방식)

```
* 1단계
  - 2단계
    + 3단계
      + 4단계
```

* 1단계
  - 2단계
    + 3단계
      + 4단계


# 코드
4칸 들여쓰기, 탭으로 구분

This is a normal paragraph

    This is a code block
    
This is a normal paragraph



    This is a normal paragraph

        This is a code block

    This is a normal paragraph




한줄을 띄어 쓰지 않으면 인식이 잘 안된다.

This is a normal paragraph
    This is a code block
This is a normal paragraph



    This is a normal paragraph
        This is a code block    
    This is a normal paragraph


# 코드 블럭


    <pre><code>... </code></pre>


<pre>
<code>
#include <stdio.h>
int main() {
  start();
}
</code>
</pre>



    <pre>
    <code>
    #include <stdio.h>
    int main() {
      start();
    }
    </code>
    </pre>


뒤에 해당 언어를 붙이면 해당 언어의 문법강조 가능

    ```java
    public class BootSpringBootApplication {
      public static void main(String[] args) {
        System.out.println("Hello, Honeymon");
      }
    }
    ```

```java
public class BootSpringBootApplication {
  public static void main(String[] args) {
    System.out.println("Hello, Honeymon");
  }
}
```

# 수평선 ```<hr/>```

```
* * *

***

*****

- - -

---------------------------------------
```

* 적용예
* * *

***

*****

- - -

---------------------------------------
    
모두 수평선을 만든다


# 강조

```
*single asterisks*
_single underscores_
**double asterisks**
__double underscores__
~~cancelline~~
```

* *single asterisks*
* _single underscores_
* **double asterisks**
* __double underscores__
* ~~cancelline~~
    

# 줄바꿈

3칸 이상 띄어쓰기(` `)를 하면 줄이 바뀐다.

```
* 줄 바꿈을 하기 위해서는 문장 마지막에서 3칸이상을 띄어쓰기해야 한다. 
이렇게

* 줄 바꿈을 하기 위해서는 문장 마지막에서 3칸이상을 띄어쓰기해야 한다.___\\ 띄어쓰기
이렇게
```

* 줄 바꿈을 하기 위해서는 문장 마지막에서 3칸이상을 띄어쓰기해야 한다. 이렇게

* 줄 바꿈을 하기 위해서는 문장 마지막에서 3칸이상을 띄어쓰기해야 한다.    \
이렇게
    
