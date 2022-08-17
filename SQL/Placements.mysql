/*
Enter your query here.
*/
select s.Name from Students S
inner join Friends f on s.ID=f.ID
inner join Packages p1 on f.ID=p1.ID
inner join Packages p2 on f.Friend_ID=p2.ID
where p1.Salary<p2.Salary
order by p2.Salary;
