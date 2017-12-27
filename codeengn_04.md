# codeengn.com BASIC 04

Q. 이 프로그램은 디버거 프로그램을 탐지하는 기능을 갖고 있다. 디버거를 탐지하는 함수의 이름은 무엇인가 

A. 파일이 좀 크므로 odbg로 확인하자.

main 함수의 주소는 0x40100F이며, 내부로 들어가 트레이싱하다보면 답이 보인다.

![](./image/04_b.png)

정답은 IsDebuggerPresent