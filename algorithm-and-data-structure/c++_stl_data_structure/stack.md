# stack

**생성자 예시**
- stack<자료형> st;
  - 비어있는 스택 생성

**함수**
###### iterator는 사용이 불가능 합니다
- st.size()
  - 스택에 들어가있는 원소의 개수를 반환
- st.empty()
  - 스택이 비어있으면 true 아니면 false를 반환
- st.push(x)
  - x를 스택에 넣음
- st.top()
  - 맨 상단에 있는 내용을 반환
  - 스택이 비어있을 때 사용시 에러
- st.pop()
  - 맨 상단의 원소 삭제
  - 반환값 x
  - 스택이 비어있을 때 사용시 에러 
