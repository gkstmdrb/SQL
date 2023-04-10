# SQL

1.연봉이 12000 이상되는 직원들의 LAST_NAME 및 연봉을 조회한다.


2.사원번호가 176 인 사람의 LAST_NAME 과 부서 번호를 조회한다.


3.연봉이 5000 에서 12000의 범위 이외인 사람들의 LAST_NAME 및 연봉을 조회힌다.


4.2002/02/20 일부터 2008/05/01 사이에 고용된 사원들의 LAST_NAME, 사번, 고용일자를 조회한다.
--    고용일자 순으로 정렬한다.


5.20 번 및 50 번 부서에서 근무하는 모든 사원들의 LAST_NAME 및 부서 번호를  조회한다. 단, LAST_NAME의 알파벳순으로 정렬한다.


6.20 번 및 50 번 부서에 근무하며, 연봉이 5000 ~ 12,000 사이인 사원들의 LAST_NAME 및 연봉을 조회한다.


7 .2004년도에 고용된 모든 사람들의 LAST_NAME 및 고용일을 조회한다.


8-1.매니저가 없는 사람들의 LAST_NAME 및 JOB_ID 를 조회한다.


8-2.매니저가 있는 사람들의 LAST_NAME 및 JOB_ID 를 조회한다.


9.커미션을 버는 모든 사원들의 LAST_NAME, 연봉 및 커미션을 조회한다.


10.LAST_NAME 의 네번째 글자가 a 인 사원들의 LAST_NAME 을 조회한다.


11.LAST_NAME 에 a 및(OR) e 글자가 있는 사원들의 LAST_NAME 을 조회한다.


12.연봉이 2,500, 3,500, 7000 이 아니며 직업이 SA_REP 이나 ST_CLERK 인 사람들을 조회한다.


13.직업이 AD_PRES 인 사람은 A 등급을, ST_MAN 인 사람은 B 등급을, IT_PROG 인 사람은 C 등급을,
         SA_REP 인 사람은 D 등급을, ST_CLERK 인 사람은 E 등급을 기타는 0 을 부여하여 조회한다.
         
         
14.모든 사원들의 LAST_NAME, 부서 이름 및 부서 번호을 조회한다.


15.부서번호 30과 90의 모든 직업들을 유일한 포맷(중복제외)으로 조회한다.


16-1.커미션을 버는 모든 사람들의 LAST_NAME, 부서 명, 지역 ID 및 도시 명을 조회한다.


16-2.옥스포드에 사는 사람 중 커미션을 버는 모든 사람들의 LAST_NAME, 부서 명, 지역 ID 및 도시 명을 조회한다.


17.LAST_NAME 이 Davies 인 사람보다 후에 고용된 사원들의 LAST_NAME 및 HIRE_DATE 을 조회한다.


18.Popp보다 급여가 높은 사원의 LAST_NAME과 급여를 조회하시오.(서브쿼리이용)


19.부서번호가 100인 부서에 속한 사원 중 전체 사원의 평균급여보다 높은 급여를 받는 사원의 LAST_NAME, 급여, 소속부서명을 조회하시오.


20.각부서별 최고 급여를 받는 사람의 LAST_NAME, 급여, 소속부서명을 조회하시오.


21.부서번호가 100 사원의 사원번호, LAST_NANE, 부서이름을 조회하시오. (인라인뷰 사용)


22.사원들의 LAST_NAME, 부서번호, 부서명을 조회하시오.(스칼라서브쿼리
--SELECT절에 사용하는 쿼리-- 이용)


23.전체 사원 중 Austin과 같은 직책(job_id) 인 사원들의 사원번호와 부서명을 출력하시오.


24.전체 사원의 평균급여보다 높은 급여를 받는 사원들의 사원번호, 부서명, 도시명을 출력하시오.(급여의 내림차순으로 정렬)


25.110번 부서에서 근무하는 사원 중 30번 부서에는 존재하지 않는 직책을 가진 사원의 LAST_NAME과 부서명을 출력하시오.


26.직책(job_id)이 SA_MAN 인 사람들의 최고급여보다 높은 급여를 받는 사원의 사원번호와 급여를 출력하시오.


27.회사 전체의 최대 연봉, 최소 연봉, 연봉 총 합 및 평균 연봉을 자연수로 포맷하여 조회한다.


28.각 JOB_ID 별, 최대 연봉, 최소 연봉, 연봉 총 합 및 평균 연봉을 자연수로 포맷하여 조회한다. (JOB_ID 오름차순)


29.동일한 직업(JOB_ID 동일)을 가진 사원들의 총 수를 조회한다.


30.매니저로 근무하는 사원들의 총 수를 조회한다.(서브쿼리 있는 쿼리물으로도 작성해보시오.)


31.사내의 최대 연봉 및 최소 연봉의 차이를 조회한다.


32.매니저의 사번 및 그 매니저 밑 사원들 중 최소 연봉을 받는 사원의 연봉을 조회한다.


33.부서 명, 위치 ID, 각 부서 별 사원 총 수, 각 부서 별 평균 연봉을 조회한다.


34.총 사원 수 및 2005, 2006, 2007, 2008 년도 별 고용된 사원들의 총 수를 조회한다.


35.각 부서의 직업 별 연봉 총 합 및 각 부서별 연봉 총 합을 조회한다.


36.각 직업 별 부서별(20, 30, 50, 100 부서만) 연봉의 총 합을 조회한다. (NULL 값인 경우 0으로 표시한다.)


37.LAST_NAME 이 Zlotkey 와 동일한 부서에 근무하는 모든 사원들의 사번 및 고용날짜를 조회한다.
--     결과값에서 Zlotkey 는 제외한다.


38.LAST_NAME 에 u 가 포함되는 사원들과 동일 부서에 근무하는 사원들의 사번 및 LAST_NAME 을 조회한다.


39.커미션을 버는 사원들의 부서와 연봉이 동일한 사원들의 LAST_NAME, 부서 번호 및 연봉을 조회한다.




* 조인문 연습
J-1) 급여가 3000이상인 사원번호, LAST_NAME, SALARY, 부서명, 도시명을 조회하시오.

J-2) 급여가 2500 이하이고 사원번호가 200이하인 사원의 LAST_NAME, 부서명을 조회하시오.

J-3) 급여범위가 JOBS 테이블의 최소급여(MIN_SALARY)와 최대급여(MAX_SALARY) 사이에 있는 사원의 LAST_NAME,

J-4)자신의 매니저보다 먼저 고용된 사원들의 LAST_NAME 및 고용일을 조회한다.

J-5) 사원정보(EMPLOYEE_ID,LAST_NAME, MANAGER_ID)와 사원의 직속 상관정보(EMPLOYEE_ID,LAST_NAME) 조회하시오.

* 테이블 생성
![image](https://user-images.githubusercontent.com/114748816/230804170-22e0d673-be6e-4bd2-9689-a11b28b5ff00.png)
















