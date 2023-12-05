# 문자열

```java
str.length() // 문자열의 길이
str.substring(i, j) // i~j-1 까지의 문자열
```

# 배열

```java
import java.util.Arrarys;

arr.length // 배열의 크기
System.arraycopy(원본배열, 원본 배열의 복사 시작 지점, 복사할 배열, 복사할 배열의 복사 시작 지점, 복사할 크기) // 객체 유지
Arrays.copyOf(원본배열, 원본 배열에서 복사해올 길이) // 새로운 배열 생성, 객체 유지 x, 더 빠름
Arrays.copyOfRange(원본배열, 시작 지점, 복사할 크기)
Arrays.toString(배열) // 배열을 문자열로
```

# ArrayList

```java
list.size() // 리스트의 크기
```

# 형변환

```java
int a;
String str = Integer.toString(a); // 정수를 문자열로
int t = Integer.parseInt(str); // 문자열을 정수로
```

# 조건문

### if문 VS 삼항연산자

    1. if문 : 느린 대신 메모리를 덜 사용
    2. 삼항연산자 : 빠른 대신 메모리를 더 사용

# Math

```
Math.pow(밑, 지수); // **과 같은 제곱연산자가 없음
```
