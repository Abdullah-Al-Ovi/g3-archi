### Features:    
    3 features of the project is given below: 
    #### 1. Course Selection:
        - Users can browse and select from a variety of available courses.
        - Once a course is selected, it becomes unavailable to other users to prevent double booking.
        - The system enforces a one-course-per-user policy, ensuring a fair distribution of courses.
    #### 2. User-friendly Interface:  
        - The user interface is intuitive and responsive.  
        - Making it easy for users to navigate and interact with the platform.
    #### 3. Credit Hour Management:  
        - The system calculates and displays the total credit hours of the selected courses.
        - The system calculates and displays the total credit hours of the selected courses.
        - Showing alertt when user exceeds the credit hour limit.  
### Discussion on management of state in my assignment project:  
    1. First useState hook is used to show all the courses with details in display.  
    2. Second useState hook is used to hold all the selected courses which is sent as a props to Cart component.  
       In the cart only the selected courses' titles are shown.
    3. Third useState hook is used to hold total credit which is used to ensure that one course can not be slelcted more than once.  
       Then it is sent to Cart component as a props where it is used to show the total credits on selected course.  
    4. Fourth useState hook is used to hold remaining credit.  
       As one user can not take courses more than 20 credit hours in total.  
       Then it is sent to Cart component to show the remaining to reach 20 credit hour.  
    5. At last the fifth and the final useState hook is set to calculate the total price on selected courses.  
       Then as props of Cart component it is shown in the cart.
     
 



