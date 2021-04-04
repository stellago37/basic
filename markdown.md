- **모든 직원의 연봉 구하기 (보너스도 포함해서) - 이름 포함, 칼럼 이름 연봉으로 변경**

    select ename, sal * 12 + nvl(comm, 0) as 연봉 from emp;
