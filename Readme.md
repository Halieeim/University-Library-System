# 								University library system 

the student can create his own account so he can sign up and if he already has an account then he can login and after that he will be redirected to the home page

there is also admin account and here its credentials:
username: halieeim
password: 123

he can login through the main login page or the login page of the django adminstrator. And ofcourse any user can logout ^_^

when the admin login then he will find an extra option "Admin" that exists in the navigation bar in the home page, and
when he clicks on that option, he will go directly to the admin page of django adminstrator.
and if that user is not an admin he won't find that option.

when any type of user go to the home page he will find a set of books with their details and between the navigation bar
and that set of books there's a filter bar he can filter this set of books according to these attributes:
	Category
	Price
	Publication_Year
	Book_Name
	ISBN

and underneath this filter bar there's a button "Borrow A Book" if the user clicked on that button then
he would be redirected to the page that contains Borrow form which take two inputs from the user:
	Book_Name
	Period (period of borrowing {days})
and at the end there's a button "Borrow" if he clicks on it then he will be redirected to the profile page and at there
he will find his own details {username, firstname, lastname, E-mail} and the books that he already borrowed and there he
will find two options {Extend Borrowing Period, Cancel Borrowing}
when he clicks on "Extend Borrowing Period" he will be redirected back to the borrowing page so he can edit the period field.
And when he clicks on "Cancel Borrowing" he will be redirected to page to confirm that he really wants to cancel this borrowing.

That's it, I hope you find it useful <3.
