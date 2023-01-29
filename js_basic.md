# Javascript 기본논리
## 변수
```bash
 a = 1
 let a = 1
 var a = 1
 const a = 1
```
## 함수
```bash
# 유형 1
function function_name(x) {
    let answer 2*x + 6;
    return answer;
}
# 유형 2
function_name = (x) => {
    let answer = 2*x + 6;
    return answer;
}
# 유형 3
((x) => {return 2*x + 6})(x값 입력)
```
- 입출력값이 없어도 동작(코드 묶기 위한 용도)
## 조건문
```javascript
if (money>5000) {
    console.log("택시를 탄다")
} else if (money > 2000) {
    console.log("버스를 탄다")
} else {
    console.log("걸어간다")
}
console
```
## 반복문
```javascript
for (let i = 0; i < 10; i++>) {
    console.log("나무찍기" + i)
}
```