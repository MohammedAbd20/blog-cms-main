

### Project Description
This is CMS Blog Build with Laravel, It has full control panel functionality with users roles.

### What I use it this project
- Laravel Framework 11,
- Tailwind for front and admin,
- Laravel Policies,
- Laravel Gates,
- Laravel Mail,
- Laravel Queues ( Building weekly Newsletter ),
- Custom Validation Rule,
- Comments, Applied ( Polymorphic relationship ),
- Applied ( One to many and Many to many ) relationships betwen models,
- Posts Views Count using Cookies,
- Faker & Database Seeder,
- jQuery
- SEO friendly slug URLS,
l
### Screenshots

#### Data Base Schema
<img src="screenshot/schema-database-blog-cms.png" width="750" alt="Database Schema - BlogCMS">

#### Admin Panel
<img src="screenshot/admin-panel-admin.png" width="750" alt="Admin Panel - BlogCMS">

#### Writer Panel
<img src="screenshot/admin-panel-writer.png" width="750" alt="Writer Panel - BlogCMS">

#### Front Blog
<img src="screenshot/blog-front.png" width="750" alt="Front Blog - BlogCMS">

#### Front Blog - PostView
<img src="screenshot/post-view.png" width="750" alt="Front Blog - PostView - BlogCMS">


### Project Functionality
#### Admin Panel
- Edit General Blog informations,
- Create/ Update / Delete ( Categories, Posts, Tags and Custom Pages )
- Manage Roles

### Writer Panel
- Create, Update and Delete it own Posts
- Create, Update and Delete Tags.

### Roles
                    
Role Name  | Role_ID
------------- | -------------
Admin  | 1
Writer | 2 
User | 3
                

### Gate Function
There is a gate filter login when the user login to the admin panel if the user is Admin it will have full functions to manage the blog and if a Writer it will have few functions.

### Api Routes
                    
Method  | End_Point | Description
------------- | ------------- | -------------
GET | api/categories | Show All Categories
GET | api/categories/{id} | Show All Posts inside Specific Category
GET | api/posts | Show All Posts
GET | api/posts/{id} | Show Specific Post

## Requirements
- PHP >= 8.2
- MySQL or other database server
- Composer
- NodeJS

### How to Install
1. Clone the project
2. Go to the project root directory and run `composer install` and `npm install`
3. Create `.env` file and copy content from `.env.example`
4. Run `php artisan key:generate` from terminal
5. Change database information in `.env`
6. Run migrations by executing `php artisan migrate` , Then Run  `php artisan db:seed` if you want use faker database records,
7. Start the project by running `php artisan serve`

### Demo Account
- AdminURL: http://127.0.0.1:8000/admin
- Email: admin@example.com
- Password: password

## About Me

I am a Full-Stack Laravel Developer with expertise in building web applications using Laravel for the back-end and Blade for the front-end. I am capable of developing complete applications from scratch, handling everything from database setup and API development to creating interactive and user-friendly front-end interfaces using HTML, CSS, and JavaScript.

Back-End Development:

I use Laravel to build secure and robust applications, with experience in managing databases, APIs, and user authentication.

I focus on optimizing performance and developing business logic that aligns with project requirements.

Front-End Development:

I work with HTML, CSS, and JavaScript to create interactive interfaces and focus on delivering a seamless user experience using Blade within Laravel.

I ensure that the design is responsive and works well across different devices and screen sizes.

I am skilled at handling all aspects of application development from end to end, allowing me to efficiently execute both small and large-scale projects.

- [LinkedIn](https://www.linkedin.com/in/mohammed-abd-elrahman-9618a732b/).


#
