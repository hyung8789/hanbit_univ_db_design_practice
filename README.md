# TEST

< 요구사항 명세서 >

1) 교수(Professor)는 아이디(ssn), 이름(name), 나이(age), 직위(rank), 연구 분야(speciality)를 가진다.
2) 학과(Department)에는 학과번호(dno), 학과이름(dname), 학과사무실(office)이 있다.
3) 대학원생(Graduate)은 아이디(ssn), 이름(name), 나이(age), 학위과정(deg_prog, 석사/박사)을 가진다.
4) 과제(Project)는 과제번호(pid), 지원기관(sponsor), 개시일(start_date), 종료일(end_date), 예산액(budget)이 있다.
5) 학과마다 그 학과를 운영(run)하는 교수(학과장이라고 한다)가 한 명씩 있다.
6) 한 교수가 여러 학과에서 근무(work-dept)할 수 있는데, 이때 각 학과별로 참여백분율(pct_time)이 기록된다.
7) 대학원생에게는 학위 과정을 밟을 전공학과(major)가 하나씩 있다.
8) 대학원생에게는 어떤 과목을 들으면 좋을지 조언(advisor)해주는 선임 대학원생(학생조언자라고 한다)이 있다.
9) 과제는 한 교수(연구책임자라고 한다)에 의해 관리(manage)된다.
10) 과제는 한 사람 이상의 교수(공동연구책임자라고 한다)에 의해 수행(work-in)된다.
11) 한 과제는 한 명 이상의 대학원생(연구조교라고 한다)에 의해 수행(work-prog)된다.
