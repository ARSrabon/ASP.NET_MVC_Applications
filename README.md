# ASP.NET_MVC_Applications
This Repository will contain my ASP.NET and MVC applications.

Create Procedure students_insert
(
	@Id int output,
	@Name nvarchar(max) = null 
)
As
Begin
	Insert into students
	(
		Name
	)
	Values
	(
		@Name
	)
	Set @Id = SCOPE_IDENTITY();
END

Create Procedure students_update
(
	@Id int output,
	@Name nvarchar(max) = null 
)
As
Begin
	update students
	
	Set Name = @Name
	where 
	Id = @Id
END


https://pages.github.com/

https://www.youtube.com/playlist?list=PL8E4DE07815022C1A

https://www.youtube.com/results?search_query=ms+sql+server+2012+tutorial+for+beginners

https://www.youtube.com/results?search_query=asp.net+mvc+5+tutorial+-+step+by+step


