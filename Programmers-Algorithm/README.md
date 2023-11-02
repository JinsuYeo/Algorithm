# Programmers-Algorithm

* 프로그래머스 알고리즘 문제 풀이 및 풀이 방법 정리

--- 

## 풀며 배운 것들

### C++   

#### next_permutation() 함수를 이용해 다음 순열을 구할 수 있다.
```
string s = "01111";
next_permutation(s.begin(), s.end()); // => s == "10111"
```   

#### bitset의 count() 메서드로 십진수를 이진수로 변환했을 때 1의 갯수를 셀 수 있다.
```
int cnt = bitset<20>(15).count(); // 15(01111) => cnt == 4
```   

#### min_element(), max_element()로 인자로 들어간 구간 내에서의 최소 값, 최대 값의 주소(or iterator) 찾을 수 있다.
```
*min_element(arr.begin(), arr.end()); // => arr의 최소값
```   

