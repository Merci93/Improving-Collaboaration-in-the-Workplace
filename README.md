# Improving Company's Collaboration
An analysis of a company's six months of information on inter-employee communication using python networkx. The dataset was assessed for errors and cleared of duplicates and merged into a single master dataset. The communication between six departments (Sales, Operations, IT, Admin, Marketing and Operations) and about _664_ unique employee id's. The analysis involved creating a network visualization of the messages sent by each employee from a department to another employee in the same or different department. This was to observe the collaborations between employees/departments and also find out areas to improve collaboration within the department or with another department.

Extensive analysis was performed to determine the most active department when sending and receiving messages, in which the **_Sales_** department was the most active in both scenarios with an approximate average messages of **_258_** and **_204_** when sending and receiving messages for the six months period, respectively, while the **_Marketing_** department was the least active on both scenarios with approximate average messages of **_3_** and **_23_** when sending and receiving messages, respectively, for the period under study. The results also showed that the employee with id **_598_**, aside being among the top five most influential employee (including id's _128, 605 and 586_) also has the most connections. Whilst the **Sales** department is also the most influential department, more collaborative measures should be implemented by the HR to improve collaboration in the **IT**, **Marketing** and also the **Engineering** departments.

The visualization of the messages sent and received per department within the six months period under study showed a huge decline as the month progressed as shown in the trend plot. More messages were shared between departments in the 6th month than in other months, while the 11th month had the least messages.

Below is a description of the dataset used for this study.
#### Messages has information on the sender, receiver, and time.
- "sender" - represents the employee id of the employee sending the message.
- "receiver" - represents the employee id of the employee receiving the message.
- "timestamp" - the date of the message.
- "message_length" - the length in words of the message.

#### Employees has information on each employee;
- "id" - represents the employee id of the employee.
- "department" - is the department within the company. 
- "location" - is the country where the employee lives.
- "age" - is the age of the employee.
