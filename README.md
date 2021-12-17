# Staff-Planning_Optimization

##### Problem Introduction

An insurance company InsurePlus wants help with finding the optimal number of staff that they need for their insurance application approval process for the calendar year 2021.  In the industry, the number of staffs is considered as a continuous variable. This is also called a Full-Time Equivalent (FTE) of the staff. For example, if a full-time employee (FTE =1) works for 50 hours a week, 10 hours corresponds to 0.2 FTEs. If the pay for 50 hours a week is $ 5000, then 0.2 FTE who may be a part-time employee will be paid $ 1000 (5000*0.2). The information provided are as follows.

##### Problem Statement and Background

- The company operates in three states: A, B and C. The state-wise demand for insurance for the year is shown in the table provided below:

![image.png](attachment:image.png)

The company can either handle an application with the staff that they hire or outsource it to a vendor. Assume that there is no capacity limitation to outsourcing.
- If they hire staff, he/she can handle 40 insurance applications per month when he/she works 100% of the workdays. However, there are days that he/she will be unavailable to process applications due to training, off days, etc. 
- A staff member’s availability (in percentage) to work on processing the insurance applications for each month is shown in the table given below. As mentioned before, with 100% availability, each member can handle 40 applications.
![image-2.png](attachment:image-2.png)
           
        
- States A and B have a regulatory restriction that the outsourced insurance applications cannot be more than 30% and 40% of the total number of applications for each month, respectively. 
- The table given below shows the cost of the staff vs external resources:
 ![image-3.png](attachment:image-3.png)                                            
 
The objective is to optimise the total cost for the application approval process by distributing the right number of applications between the FTEs and the vendors while meeting the monthly demand for each state at the same time.
