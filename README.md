# d-app-expense-tracker-rahul
This is Rahul Lalwani
for the solidity 
the feature i am choosing is to get total no of registered users the code snippeet  is below
 #function gettotalUsers() public view returns (uint256) { \\This function uses .length to get total no. of users
    #return registeredPeople.length;
    #} (for using the solidity function in the website i am also adding a click button to call this solidity function)
    for app.js I am showing total registered people
    here are snippet
    #<p>Total Registered Users: {people.length}</p>
    also added a header
    #<h3>People ({people.length} registered)</h3>
    (in app js i have also changed the themes for beeter clarity)
   
update added FETchusers function(note i am not considering the console error as it would already show error for the register function) in app js to call solidity gettotalUsers function.
I’ve added a toggle button to switch between light and dark themes using inline styles

