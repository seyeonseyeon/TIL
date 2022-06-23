# DAY41

1. HttpSession: 세션은 일정 시간동안 같은 클라이언트(브라우저)에서 들어오는 일련의 요구를 하나의 상태로 보고, 그 상태를 유지하는                   기술이며, 사용자가 웹서버에 접속한 후 브라우저를 종료할 때까지 세션 유지.
2. invalidate: 세션의 값들을 모두 사라지도록 하기 위해 사용
3. addAttribute(String name, Object value): value 객체를 name이름으로 추가
4. setAttribute: 선택한 요소의 속성 값을 정함

5. ModelAndView: 데이터를 전송시킬 수 있는 리턴 타입
    * addObject를 통해 데이터를 저장 (addobject: key와 value를 담아 보낼 수 있는 메서드)
    * setViewName을 통해 이동하고자 하는 View를 저장 (setViewName: 어떤 페이지를 보여줄 것인지)

6. Model: 데이터만 저장
