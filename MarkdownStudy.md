<br/>
Hi, I'm studying Markdown
===

<br/>
<br/>

* # 첫번째 글씨 크기 (평행선 자동생김)
* ## 두번째 글씨 크기
* ### 세번째 글씨 크기
* #### 네번째 글씨 크기
* ##### 다섯번째 글씨 크기
* ###### 여섯번째 글씨 크기

<br/>
<br/>

-----
<br/>

## 마크다운 개행문자 & 코딩입력란   <br/><br/>
<pre>
<code>
    br/ 입니다. html과 같은 개행문자 
    혹은 띄어쓰기 세번 후 엔터
    pre 
    code
    /code
    /pre 를 통한 코딩입력란

    public class void main(String[] args){

        System.out.println("Hi, Hello, How are you");
        
    }
</code>
</pre>

```
    br/ 입니다. html과 같은 개행문자
    혹은 띄어쓰기 세번 후 엔터
    ```을 이용한 코딩입력란

    public class void main(String[] args){

        System.out.println("Hi, Hello, How are you");

    }
```

``` java
    // br/ 입니다. html과 같은 개행문자
    // 혹은 띄어쓰기 세번 후 엔터
    // ```을 이용한 코딩입력란 &
    // ``` 뒤에 java 혹은 c 처럼 사용 언어를 넣어주면
    // 글씨색도 언어에 맞춰서 변경

    public class void main(String[] args){

        System.out.println("Hi, Hello, How are you");

    }
```


-----

## 리스트작성 요령
<br />

> ### 순서가 있는 리스트
<br />

1. hi
2. hello
3. how are you

<br />

> ### 순서가 없는 리스트 (*,   +,   -)

* +  - 가 존재 

* 첫번째 *
    * 두번째 *
        * 세번째 *

+ 첫번째 +
    + 두번째 + 
        + 세번째 +

- 첫번째 -
    - 두번째 - 
        - 세번째 -


-----
<br />

 ## Link 만들어보기 

<br />

> ### 일반 링크
<br />

* Link : [Google][googlelink]

[googlelink]: https://google.com "Go google"

```
    Link Label : [Title] [Link var]
    Link var : [Google](https://google.com, "google link")
```
<br />

* 외부링크: <http://example.com/>

<br />
<br />

> ### 이메일 주소 링크 

<br />

* 이메일링크: <address@example.com>

<br />

------ 
<br />

## 강조 & 취소선
<br />

1.  *강조1* <br />
```
    *강조1*
```
<br />

2.  _강조2_ <br />
<br />
```
    _강조2_
```

3.  **강조3** <br />
<br />
```
    **강조3**
```

4.  __강조4__ <br />
<br />
```
    __강조4__
```

5.  ~~취소선~~ <br />
<br />
```
    ~~취소선~~
```

<br />
<br />

-----
<br />

## IMAGE 
<br />

> ### 방법 1.    ``` <img src="#"> ```
<br />
<img src="/img/cat.jpg" width="450px" height="300px" title="image1" alt="Show Image Title"></img>
<br/>
<br/>

<br/>
<br/>

> ### 방법 2.     ``` ![Alt text](#경로) ```
<br />

![Alt text](/path/to/img.jpg "cat")

<br />
<br />

