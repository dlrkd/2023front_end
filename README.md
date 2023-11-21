# 2023front_end

front end 과제

#과목명 및 각종 점수를 입력하여 성적을 저장하는 성적표 계산기 만들기

#기능
1. 추가버튼을 누르면 과목 정보를 입력할 수 있는 테이블 생성 (구현 완료)
2. 교양, 전공 선택은 select box로 선택 (구현 중) 
3. 필수, 선택 선택은 select box로 선택 (구현 중)
4. 과목명은 text box로 입력 (구현 중)
5. 학점은 1, 2, 3점을 select box로 선택 (구현 중)
   1) 학점이 1점일 경우 점수입력 못하고 성적만 P(Pass)/N(Non Pass) 으로 처리
7. 출석점수, 과제점수, 중간고사점수, 기말고사점수는 숫자로 입력가능하게 처리
   1) 출석, 과제 점수는 0보다 작을 수 없고 20보다 클 수 없다
   2) 중간, 기말 점수는 0보다 작을 수 없고 30보다 클 수 없다
   3) 과목별 총점은 0보다 작을 수 없고 100보다 클 수 없다
   4) 범위를 벗어날 경우 에러 출력 (ex: 입력된 점수가 올바르지 않습니다)
8. 총점, 평균, 성적, 합계는 따로 입력하지 않고 점수 입력한 걸로 계산하여 표시
   1) 총점은 출석, 과제, 중간, 기말 점수의 합계
   2) 평균은 각 과목에 표시하지 않고 전과목의 총점합계/전과목수 로 계산
9. 성적은 각 과목의 총점에 따라 등급으로 표시
    1) 100-95 A+
    2) 94-90 A0
    3) 89-85 B+
    4) 84-80 B0
    5) 79-75 C+
    6) 74-70 C0
    7) 69-65 D+
    8) 64-60 D0
    9) 59-0 F
10. 성적등급이 F인 경우 빨간색으로 표시
11. 각 항목은 중앙, 좌측 정렬
12. 테이블 색 입히기
13. 각 과목 테이블 선택 / 각 과목 테이블 체크표시 후 삭제버튼 누르면 그 과목이 삭제
14. 저장버튼 누르면 입력한 값에 따라 성적 합계 계산
15. 위에 내용으로 1~3학년 만들것
