1# Sql_sure_trust
Assignment 01

select * from emp;
select * from dept;

1.select count(*)  from emp;

2. select count(*)  from dept;

3. select ename from emp;

4. select dname from dept;  

5. select sum(sal) from emp;

6. select sum(comm)  from emp;

7. select job from emp where comm>0;

8. select sysdate from dual;

9. select avg(sal)  from emp;

10. select deptno , count(*) from emp group by deptno;

11. select deptno, sum(sal) from emp group by deptno;

12. select job , count(*) from emp group by job;

13. select job , avg(sal) from emp group by job;

14. select ename , hiredate from emp;

15. select ename , deptno from emp order by deptno;

16. select ename , job from emp order by job;

17. select ename,sal from emp order by sal desc;

18. select ename,deptno,sal from emp order by deptno asc,sal desc;

19. select count(*) from emp where length(ename) = 6;

20. select max(sal) , min(sal) from emp;

21. select deptno, max(sal), min(sal), avg(sal) , sum(sal) from emp group by deptno;

22. select ename,hiredate from emp order by hiredate;

23. select *
      from emp
      order by hiredate desc;

24. select *
      from emp
      order by hiredate asc;

25. select ename, hiredate,deptno from emp order by hiredate desc , deptno asc;

26. select ename ,sal
    from emp
    where sal>= avg(sal) ;

27. select ename ,sal
    from emp
    where sal<= avg(sal);

28. select ename,sal
      from emp
      where sal>2000 and sal < 4000;

29.  select *
from emp
where sal=min(sal)from emp or max(sal) from emp;

30. select count(*) from emp where to_char(hiredate, 'MON') = 'JAN';
