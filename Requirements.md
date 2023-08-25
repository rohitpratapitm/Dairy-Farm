#Landing Page: This should be a secure login system that supports two-factor authentication for additional security. It must have features like "Forgot Password" and "Remember me".
#Cows Page: This page should list all the cows in a card-based UI. Each card will contain key information about each cow. It will allow users to add, edit, and remove cow records. Each cow record will contain the following fields:
Unique Identification Number
Picture
Date of Birth
Breeding History (a sub-section to add, view, and edit details of every time a cow was inseminated, who the sire was, and when calves were born)
Performance Metrics (lactation data, health record etc.)
Current Status (pregnant, ready for insemination, in milking)
Next vaccination date
#Lactation Page: This page will allow users to log lactation data twice a day for each cow. It should show lactation data in a table format with options to filter and sort by date, cow ID, and lactation quantity. It should have the ability to export the table data in CSV format.
#Dashboard Page: This is the main page a user lands on after login. It should display key metrics and notifications for easy viewing. Metrics could include:
Total number of cows
Number of cows in pregnancy
Number of cows ready for insemination
Number of cows in milking
Average daily lactation
Next due vaccinations (a list of cows that have vaccination due in the next week)
Total quantity of fodder in stock
Status of farm crops (a short list of crops that are ready for harvest)
#Users Page: This page should be accessible only to the Admin and Manager. It should allow the creation, modification, and deletion of users along with their roles and access permissions. The roles and permissions could include:
#Admin: All access including user management
#Manager: All access excluding user management
#Supervisor: Can add, edit, delete cow records, lactation data, farm data and fodder data
#Worker: Can only add lactation data and fodder data
#Fodder Page: This page should manage all fodder-related data including what's in stock, what's been consumed, and what needs to be ordered. It should also manage TMR details for different groups of cows. Fields might include:
Fodder type
Quantity in stock
Consumption rate
TMR details (components and their quantities)
Required quantity for order replenishment
#Farm Page: This page should track information about crops being grown for fodder. Information could include:
Type of crop
Sowing date
Expected harvest date
Health status
Quantity expected
