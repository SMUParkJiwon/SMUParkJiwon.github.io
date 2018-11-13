##**Python Style Guidelines**


**LR**

**Default iterators and Operators**
   기본 iterator와 연산자를 쓸 것.
    연산자 오버로딩 같은걸 하지 말 것

**Imports**
   모듈과 패키지에만 사용할 것.
    import에 상대적인 경로 쓰지 말고 full path를 쓸 것

**packages**
   각 모듈과 패키지를 full pathname을 사용할 것
    e.g. from sound.effects import echo
    c.e.g. import sound.effects.echo

**SR**

**Imports formatting**
   import 할 때는 라인을 분리한다.
    do not use : import os, sys
    use : 
              import os
              import  sys
  
  **SR**
 
 **Indentation**
   탭을 사용하지 말고 띄어쓰기 4개로 사용할 것. 
   들여쓰기는 수직열이 맞아야 함

**SR**

**Whitespace**
   괄호사이 공백x, ,;: 전에 공백x, 괄호사이, 파라미터 리스트, 인덱스, 슬라이싱에 공백x
 
 **vim**
  Backgroud
   setting for vim files
![enter image description here](https://i.imgur.com/p5UzZtN.jpg)


#Vim Editor를 위한 설정파일을 제공하고 있음
https://google.github.io/styleguide/google_python_style.vim 


