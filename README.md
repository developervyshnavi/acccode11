# acccode11
print the sal is greater then 2000
'''81       3000             EMPNO ENAME      JOB              MGR HIREDATE         SAL       COMM      
---------- ---------- --------- ---------- --------- ---------- ----------      
    DEPTNO                                                                      
----------                                                                      
      7566 JONES      MANAGER         7839 02-APR-81       2975                 
        20                                                                      
                                                                                
      7698 BLAKE      MANAGER         7839 01-MAY-81       2850                 
        30                                                                      
                                                                                
      7782 CLARK      MANAGER         7839 09-JUN-81       2450                 
        10                                                                      
                                                                                

     EMPNO ENAME      JOB              MGR HIREDATE         SAL       COMM      
---------- ---------- --------- ---------- --------- ---------- ----------      
    DEPTNO                                                                      
----------                                                                      
      7788 SCOTT      ANALYST         7566 19-APR-87       3000                 
        20                                                                      
                                                                                
      7839 KING       PRESIDENT            17-NOV-81       5000                 
        10                                                                      
                                                                                
      7902 FORD       ANALYST         7566 03-DEC-   
      20 '''                                                                    
      select emp.*
  2  from emp
  3  where sal>2000;                                                                          
