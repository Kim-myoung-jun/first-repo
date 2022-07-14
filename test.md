헤더입니다. 아래에 === 을 추가하면 헤더가 됩니다. H1
=====================================================

'''
헤더입니다. 아래에 === 을 추가하면 헤더가 됩니다. H1
=====================================================
'''


작은 헤더입니다. 아래에 --- 을 추가하면 작은 헤더가 됩니다 H2
-----

'''
작은 헤더입니다. 아래에 --- 을 추가하면 작은 헤더가 됩니다 H2
-----
'''



# H1 글머리
## H2 글머리
### H3 글머리
#### H4 글머리
##### H5 글머리
###### H6 글머리

'''
# H1 글머리
## H2 글머리
### H3 글머리
#### H4 글머리
##### H5 글머리
###### H6 글머리
'''




# 블럭 인용

> 1단 건너기
> > 2단 건너기
> > > 3단 ....

'''
> 1단 건너기
> > 2단 건너기
> > > 3단 ....
'''


# 순서 있는 목록
1. 첫번째
2. 두번째
3. 세번째

'''
1. 첫번째
2. 두번째
3. 세번째
'''

# 순서 없는 목록
* + - 사용

* 가
* 나
* 다

+ A
+ B
+ C

- 1
- 2
- 3

'''
* 가
* 나
* 다

+ A
+ B
+ C

- 1
- 2
- 3
'''

# 코드
4칸 들여쓰기, 탭으로 구분

This is a normal paragraph

    This is a code block
    
This is a normal paragraph


'''
This is a normal paragraph

    This is a code block
    
This is a normal paragraph
'''



한줄을 띄어 쓰지 않으면 인식이 잘 안된다.

This is a normal paragraph
    This is a code block
This is a normal paragraph


'''
This is a normal paragraph
    This is a code block    
This is a normal paragraph
'''

# 코드 블럭

'''
<pre><code>... </code></pre>
'''

<pre>
<code>
#include <stdio.h>
int main() {
  start();
}
</code>
</pre>


'''
<pre>
<code>
#include <stdio.h>
int main() {
  start();
}
</code>
</pre>
'''

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

# 수평선 <hr>

* * *
*****
- - - 
---------

    * * *
    *****
    - - - 
    ---------
    
모두 수평선을 만든다


# 강조

*single asterisks*
_single underscores_
**double asterisks**
__double underscores__
~~cancelline~~

    *single asterisks*
    _single underscores_
    **double asterisks**
    __double underscores__
    ~~cancelline~~
    

# 줄바꿈

스페이스 3칸을 두면 줄바꿈이 된다.

* 가나다
* 가나   다

    * 가나다
    * 가나   다
    
