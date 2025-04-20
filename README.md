# d-app-expense-tracker-rahul
This is Rahul Lalwani
for the solidity I am attaching a text file with solidity code
the feature i am choosing is to get total no of registered users the codefix is below
 #function gettotalUsers() public view returns (uint256) { \\This function uses .length to get total no. of users
    #return registeredPeople.length;
    #}
    for app.js I am showing total registered people
    here are snippet
    #<p>Total Registered Users: {people.length}</p>
    also added a header
    #<h3>People ({people.length} registered)</h3>
    i am saving copy of the file as a text file
   
update added fetchusers function in app js to call solidity gettotal function
added a button for user to interact with solidity function
note i did not add contract error case in fetchuser function
