
deploy Link :- https://mentor-task.herokuapp.com
# Mentor-task :-
For creating a mentor :-
use the link https://mentor-task.herokuapp.com/mentors/post with post method 
the request body should be like below:- {
     "name": "Monti Kumar",
     "email":"monti1713011@akgec.ac.in",
     "course":"Information technology"
     
}

for creating a students:-
https://mentor-task.herokuapp.com/students/post with post method
the request body should be like below:-
{
     "name": "rahul  Kumar",
     "email":"Rkt71@gmail.com",
     "batch":"2021"
}

To change mentor for particular student :-
the request body should be like below:-{
     "name": "rahul  Kumar",
     "email":"Rkt71@gmail.com",
     "batch":"2021",
     "mentorId": "61713e96f8eb085721ad0fe2"
}

