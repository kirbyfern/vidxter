
# Vidxter

Vidxter is a site that allows people to sign up and create a course. It allows learners to enroll, educators to create content and pay for an online course. Technically it is a two sided video streaming marketplace platform, featuring credit card payment capabilities, user role management, complex user interfaces and advanced database relationships.

*Technical description: A two sided video streaming marketplace platform, featuring credit card payment capabilities, user role management, complex user interfaces and advanced database relationships.*

## Features

* Easy to use platform for admins/educators to make courses and make money.

* [Stripe API](https://stripe.com/docs/api) is used to process course credit card payments.

* Educators can customize course lessons and sections.

* [jQueryUI](https://jqueryui.com/) drag and drop interface allows instructors to reorder sections and lessons.

* Amazon Web Services (S3) for photo and video storage.

* [Devise](https://github.com/plataformatec/devise) for flexible user authentication.

* Users can be both educators and students with restricted  admin access if the user created a course.

* Dashboard that shows all courses a user is enrolled in and teaching.

## Demo
You can check the live version of the application at
[https://vidxter-kirby-james.herokuapp.com/][demo].

[demo]: https://dev-stream-courses.herokuapp.com/

## Screenshots
![Vidxter Homepage](https://raw.githubusercontent.com/kirbygit/vidxter/master/app/assets/images/vidxter-homepage.png "Vidxter Homepage")
![Vidxter Courses Interface](https://raw.githubusercontent.com/kirbygit/vidxter/master/app/assets/images/vidxter-courses.png "Vidxter Courses")
![Vidxter Payment](https://raw.githubusercontent.com/kirbygit/vidxter/master/app/assets/images/vidxter-payment.png "Vidxter Payment w/ Stripe")