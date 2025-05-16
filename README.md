# 2025_Interview-Questions
--------------------------
HCL interview
-------------
![image](https://github.com/user-attachments/assets/e8242168-73e2-46e6-a80c-297d6755e65b)


1) Middlewares
2) Session management 
3) .net core life cycle 
4) Service life cycle
5) Extension methods
6) How to write a test cases what are the Types
7) Diff between ref and out 
8) Delegates vs events 
9) Sp vs function 
10) Static vs singleton
11) Ienumerable vs iqyerable
12) Constant vs readonly 
13) == vs Equal 
14) Var vs dynamic 
15) Lazy vs eager loading 
16) Concurrent vs parallel 
17) CTE Vs temp 
18) Normal collection vs generic

Technoforte interview
-----------------------
1) Life cycle of Dot net core
2) Service Lifetime Management in dotnet core
3) What is static binding and dynamic binding
4) Can u create method overloading in same class
5) Difference between Event and Delegate and where we will use
6) Factory method
7) Write 5th highest salary in sql and linq query
8) Delete truncate differece
9) function & sp difference
10) what are the different type of Table which is being used in Triggers
11) span and div difference
12) margin and padding difference
13) what are difference position in css
14) what are different way to create a css in web page
15) clustered and non clustered index difference
16) how you will increase the performace in sql
17) which one is faster clusted or non clustered
18) which one is faster join or subqueries
19) fibonacci code
20) difference between abstract and interface and when to use it

 New Interview Questions
 ------------------------
 1) what is auth and auth how it works in ur project
 2) what is async , await and sync explain
 3) how will u validate user token is going to expire
 4) Union
 5) Index in sql
 6) ref and out
 7) add scope and add transient explain
 8) Liskov substitution rule

    infosys

    1) what are indexers
    2) async and sync difference
    3) what are locks in c sharp
    4) soap and rest api difference


       GoAvega
       -------

       public abstract class GenericRepository<C, T> : 
    IGenericRepository<T> where T : class where C : DbContext, 

   new() {


    public IQueryable<T> FindBy(System.Linq.Expressions.Expression<Func<T, bool>> predicate) {
 
        IQueryable<T> query = _entities.Set<T>().Where(predicate);
        return query;
    }


join two tables table1 and table2, fetch table1 records.
 filter records 
where table1 id greater than 2 and table2 id less 10 
without where condition


select t1.* from table1 t1
join table2 t2 with (nolock) on t1.id = t2.id
where  between t1.id(2,10) 


select t1.* from table1 t1
join table2 t2 with (nolock) on t1.id = t2.id 
and  between t1.id(2,10) 



int[] a = int a[2,5,7,11,13];

int[] v = a.select(b=>b%2==0).List();

class Employee

id      salary    	name    dept
1       700000           A      dev
2       1000000          B      dev
3       500000           C      qa
4       800000           D      qa

based on the dept
get the 2nd highest salary based on the dept
employee.orderbydesc(a=>a.salary).skip(1).firstOrDefault();

in the below string need to get each word repeated how many times 

string name = "i am from bangalore and i stay in outskurt of bangalore"

private string Name(string name)
{
 string[] a = name.split(" ");
 Dictionary<int,string> frequency = new Dictionary<int,string>();

 foreach(var num in a)
{
  frequency = num.GetValueOrDefault(num,0)+1
}

frequency.orderByDescending(k=>k.key).select();


}
