JAVA와 MYSQL DB를 활용한 과제관리 프로그램입니다.

*실행 파일 다운로드 - [exe파일 다운로드](https://github.com/gianna-k/reportManagement/raw/master/project.exe)

*테스트용 아이디/비밀번호 - (학생) 321 / 321 , (강사) 123, 123

*개발 기간 - 2020.05.01 ~ 2020.06.30 (약 2개월)

*개발 환경 - JAVA , MYSQL

*개발 인원 - 4 명

요   약>

학교나 학원 등에서 과제를 관리할 때 활용할 수 있는 프로그램입니다. 
강사가 자신의 강의에 과제를 등록하면, 해당 강사의 강의를 듣는 수강생들은 과제물을 제출할 수 있고, 강사가 채점 및 피드백을 남길 수 있는 기능을 가지고 있습니다.

주요 기능>
1)	강의, 과제의 생성/수정/삭제/검색/기간별 조회
2)	과제 제출, 첨부파일 등록/다운로드, 채점 및 피드백
3)	회원가입, 조회, 로그인

담당한 구현 내용>
[pdf 보기](https://github.com/gianna-k/reportManagement/blob/master/4%EC%A1%B0%20%ED%94%84%EB%A1%9C%EC%A0%9D%ED%8A%B8%20%EB%B0%9C%ED%91%9C-%EA%B9%80%EC%A7%80%ED%98%84.pdf)
1)	과제 화면 구현
-	강의별 과제 목록 조회 기능
-	기간별 과제 조회 기능 구현
-	강의별 과제 생성/수정/삭제 기능 구현
-	해당 과제의 제출 현황 조회 및 표시 기능 구현
-	과제의 제출정보 조회 및 채점, 피드백 기능 구현
-	과제 생성/조회 시 첨부파일 업로드, 다운로드 기능 구현
-	엑셀로 내보내기 기능 구현

2)	과제와 관련된 데이터베이스 구현
-	과제 관리에 필요한 테이블 구현
-	과제 제출관리에 필요한 테이블 구현
-	강의별 학생 목록을 조회할 수 있는 뷰 구현
-	과제의 제출 현황을 조회할 수 있는 뷰 구현

3)	통합 화면 구현
-	화면전환 및 메인 메뉴 버튼의 기능 구현
-	CSS 작성

4)	Util 클래스 작성
-	여러 클래스에서 공용으로 사용하는 메서드 구현

5)	Navigator 클래스 작성
-	화면 간 전환을 수월하게 하는 클래스 작성
