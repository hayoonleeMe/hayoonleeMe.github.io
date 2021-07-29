---

title: "github.io 블로그 시작하기"
excerpt: "GitHub Blog 서비스인 github.io 블로그 시작하기로 했다."
categories:
  - Blog
tags:
  - Blog
last_modified_at: 2021-07-29 10:15:00 ~ 10:15:00
toc: true
toc_sticky: true
toc_label: "목차👀"
---

`해당 포스트는 포스트 작성 연습과 Markdown의 문법을 포함합니다. 추후 변경예정.`{: .notice--success}

GitHub Blog 서비스인 github.io 블로그 시작하기로 했다.

GitHub Blog 서비스의 이름은 Pages이다.



Pages가 다른 블로그 플랫폼 보다 편한 것 같아서 마음에 든다.

다른 사람들도 같이 많이 사용했으면 좋겠다는 생각이 든다.  



YFM에서 정의한 제목을 이중 괄호 구문으로 본문에 추가할 수 있다.

이 글의 제목은 {{ page.title }}이고

마지막으로 수정된 시간은 {{ page.last_modified_at }}이다.



1. 🐱‍🐉
2. 👍



### 강조

*single asterisks*

_single underscores_

**double asterisks**

__double underscores__

***triple asterisks***

___triple underscores___

~~cancel line~~



### 코드블록

```cpp
int main()
{
    std::cout << "Hello World" << std::endl;
    
    return 0;
}
```



### BlockQuote

```markdown
> 수
>>평
>>>선
```

> 수
>
> > 평
> >
> > > 선



### 수평선

```markdown
***
****
---
----
```

***

****

---

----



### 링크 추가

```markdown
[Google 링크](https://google.com)

<https://google.com>
```



[Google 링크](https://google.com)

<https://google.com>

 

### 이미지 삽입

#### 이미지 소스 URL만 입력

```markdown
![](https://github.com/hayoonleeMe/hayoonleeMe.github.io/blob/main/assets/images/moon.jpg?raw=true)
```

![](https://github.com/hayoonleeMe/hayoonleeMe.github.io/blob/main/assets/images/moon.jpg?raw=true)



#### 대체 텍스트(alt)를 입력

```markdown
![달 사진](https://github.com/hayoonleeMe/hayoonleeMe.github.io/blob/main/assets/images/moon.jpg?raw=true)
```



![달 사진](https://github.com/hayoonleeMe/hayoonleeMe.github.io/blob/main/assets/images/moon.jpg?raw=true)



#### 이미지(title)을 입력

```markdown
![달 사진](https://github.com/hayoonleeMe/hayoonleeMe.github.io/blob/main/assets/images/moon.jpg?raw=true "달 사진")
```



![달 사진](https://github.com/hayoonleeMe/hayoonleeMe.github.io/blob/main/assets/images/moon.jpg?raw=true "달 사진")



#### 이미지를 인라인으로 삽입하기 (보완 필요)

달 사진은 ![달 사진](https://github.com/hayoonleeMe/hayoonleeMe.github.io/blob/main/assets/images/moon.jpg?raw=true#style=max-width:200px;vertical-align:middle; "달 사진") 

입니다.



#### 참조형식으로 이미지 삽입

```markdown
![달 사진][참조이미지1]
[참조이미지1]: https://github.com/hayoonleeMe/hayoonleeMe.github.io/blob/main/assets/images/moon.jpg?raw=true 
```



![달 사진][참조이미지1]

[참조이미지1]: https://github.com/hayoonleeMe/hayoonleeMe.github.io/blob/main/assets/images/moon.jpg?raw=true



### 이미지 크기 조정

#### 픽셀(px) 단위의 크기 조정

```markdown
![달 사진](https://github.com/hayoonleeMe/hayoonleeMe.github.io/blob/main/
        assets/images/moon.jpg?raw=true "달 사진"){: width="100px" height="100"}
```



![달 사진](https://github.com/hayoonleeMe/hayoonleeMe.github.io/blob/main/assets/images/moon.jpg?raw=true "달 사진"){: width="100px" height="100"}



#### 비율(%) 단위의 크기 조정

```markdown
![달 사진](https://github.com/hayoonleeMe/hayoonleeMe.github.io/blob/main/
        assets/images/moon.jpg?raw=true "달 사진"){: width="50%" height="50%"}
```



![달 사진](https://github.com/hayoonleeMe/hayoonleeMe.github.io/blob/main/assets/images/moon.jpg?raw=true "달 사진"){: width="50%" height="50%"}



### 이미지 정렬

`{: .align-center}` : **가운데** 정렬   
`{: .align-left}` : **왼쪽** 정렬   
`{: .align-right}` : **오른쪽** 정렬   



```markdown
![달 사진](https://github.com/hayoonleeMe/hayoonleeMe.github.io/blob/main/
        assets/images/moon.jpg?raw=true "달 사진"){: width="50%" height="50%" .align-center}
```

![달 사진](https://github.com/hayoonleeMe/hayoonleeMe.github.io/blob/main/assets/images/moon.jpg?raw=true "달 사진"){: width="50%" height="50%" .align-center}

   



### 표 만들기

| 항목 | 가격  | 개수 |
| :--- | :---: | ---: |
| 라면 | 800원 | 10개 |
| 과자 | 900원 | 20개 |







