2021.08.13
===
###  01. 정수형
+ 정수형 변수를 선언할 시에 쓰인다.
+ byte, short, int, long

       int winterAge=3
       
### 02. 실수형 
+ 실수형 변수를 선언할 시에 쓰인다.
+ float, double
+ float을 쓸 때에는 실수뒤에 F 나 f를 입력한 후 써야한다.
          
          float x= 0.2f;
          
### 03. 문자형
+ 문자형 변수를 선언할 시에 쓰인다.
+ char

### 04. 문자열 
+ 문자열을 쓸 때 쓰인다.
+ String
     
         String chicken = "치킨 먹고싶다.";
         
### 05. 논리형 
+ true 혹은 false 값을 가지는 변수를 선언할 때 쓰인다.
+ boolean

***
```javascript
        String name="홍길동";
        String age="50세";
        String adress="서울시";

        System.out.println("이름: "+name);
        System.out.println("나이: "+age);
        System.out.println("주소: "+adress);
```
***
```javascript
        int winterAge=3;
        int maxAge=7;

        boolean eq = winterAge==maxAge;
        boolean win= winterAge>maxAge;
        boolean max= maxAge>winterAge;

        System.out.println("윈터의 나이가 맥스의 나이와 같은가? " + eq);
        System.out.println("윈터의 나이가 맥스의 나이보다 많은가? " + win);
        System.out.println("윈터의 나이가 맥스의 나이보다 적은가? " + max);
```
***
