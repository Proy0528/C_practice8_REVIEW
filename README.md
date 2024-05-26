# C_practice8_REVIEW
## 2024/05/26 : 포인터

#### 배열의 0번째 = 986호
#### arr[0] = 20;
#### 986호 = 20;
#### -> 포인터
-----
    #define _CRT_SECURE_NO_WARNINGS
    #include <stdio.h>
    int main() {
    	int a;
    	int *ap;
    	ap = &a;
    	*ap = 20;
    	printf("%d\n", a);
    }
#### int main 함수 만들기
#### 정수형 변수 a를 만들기
#### 정수형 포인터 변수 ap 만들기
