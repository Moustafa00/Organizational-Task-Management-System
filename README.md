<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

# The Project

This is a Organizational Employee Task Tracker and Management System built with Laravel and Livewire. It allows you to create, assign, and track tasks within your organization. The app comes with features such as user management, task creation with due dates, task assignment to employees, task completion tracking, and administrative task tracking.

## Features

- User Management: The app allows you to create users with different roles. You can assign roles to users based on their responsibilities within the organization.

- Task Creation: The admin can create tasks and specify a due date for each task. This helps in organizing and prioritizing tasks effectively.

- Task Assignment: Tasks can be assigned to specific employees. By assigning tasks to individuals, you can ensure clear ownership and streamline task distribution.

- Task Completion: Users can mark tasks as complete once they finish working on them. This provides a visual indicator of the progress made on each task.

- Administrative Task Tracking: Admin users have access to a task tracking feature. This allows them to monitor the tasks assigned to different users and track their progress. It helps in identifying bottlenecks, ensuring timely completion, and balancing workload among team members.

## Installation

To install and run the Task Management App locally, follow these steps:

1. Clone the project
2. Go to the project root directory and run `composer install` and `npm install`
3. Create `.env` file and copy content from `.env.example`
4. Run `php artisan key:generate` from terminal
5. Change database information in `.env`
6. Run migrations by executing `php artisan migrate` , Then Run  `php artisan db:seed` if you want use faker database records,
7. Start the project by running `php artisan serve` then `npm run dev`

8. Access the application in your web browser at `http://localhost:8000/admin`, with this credentials

````
test@example.com
password
````
## About Me

I'm Moustafa Jarjour, a CS graduate with hands-on experience in diverse projects and a strong foundation in computer science fundamentals. I enjoy working on projects that blend creativity and functionality. I focus on applying technology to solve interesting problems. Committed to continuous learning and improvement to grow as a developer.

- [Portfolio](https://moustafa00.github.io/).





