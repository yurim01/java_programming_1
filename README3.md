 2021.08.03
 ===
### 산술 연산자
+ 종류
   + 덧셈 : +
   + 뺄셈 : -
   + 곱셈 : *
   + 나눗셈 : /
   + 나머지 : %
   
         System.out.println(2+3);
         System.out.println(5-2);
         System.out.println(2*3);
         System.out.println(6/2);
         System.out.println(7%3);
+ 우선순위
   : 기초적인 수학과 우선순위가 같다.
   
      System.out.println(1+2*3);
      System.out.println(2-4/2);
      System.out.println((2-4)/2);
 ***
### 대입 연산자
+ 연산자 : =
+ 대입 하고자 하는 변수의 타입과 대입값이 같아야 한다.

        int number;
        number = 5;
        
+ 정수형에 실수값을 대입하고자하면 실수값을 정수형으로 바꾸고 대입한다.
      
      int number;
      number=(int)1.6;
*** 
### 비교 연산자
+ 종류
   +  < : 왼쪽 값이 오른쪽 값보다 작은가? 
   +  <= : 왼쪽 값이 오른쪽 값보다 작거나 같은가?
   +  \> 
   +  \>= 
   +  == : 양쪽 값이 같은가?
   +  != : 양쪽 값이 다른가? 
+ 출력 시 ture 혹은 false로 출력된다.

      System.out.println(2<3);
      System.out.println(2>3);
