# TaskWave  

TaskWave is a powerful and intuitive task management application designed for individuals and teams. Built with **Laravel**, **Inertia.js**, and **Svelte**, it provides a seamless and efficient way to organize tasks, set deadlines, and track progress.

## Features  
- 📝 **Task Management** – Create, update, and delete tasks effortlessly  
- 🔔 **Reminders & Notifications** – Get notified about upcoming deadlines  
- 📅 **Task Scheduling** – Assign due dates and categorize tasks  
- 📊 **Progress Tracking** – View task completion rates and productivity insights  
- 📱 **Mobile-Responsive** – Optimized for both desktop and mobile users  
- 🔄 **Future Expansion** – Plans for mobile app deployment and integrations  

## Tech Stack  
- **Backend:** Laravel + Octane & RoadRunner  
- **Frontend:** Svelte (with Inertia.js)  
- **Database:** MySQL (with Redis for caching in the future)  
- **Infrastructure:** Docker (Kubernetes planned for scaling)  

## Installation  

### Prerequisites  
Ensure you have the following installed:  
- PHP 8.x, Composer  
- Node.js & npm  
- Docker & Docker Compose  

### Setup  

1. Clone the repository:  
   ```sh
   git clone https://github.com/yourusername/taskwave.git  
   cd taskwave
   ```

2. Install dependencies:
```
composer install  
npm install
```

3.Configure environment variables:
```
cp .env.example .env  
php artisan key:generate  
```

4. Start the development environment:
```
docker-compose up -d  

```

5. Run database migrations:
```
php artisan migrate --seed  

```

6. Start the application:
```
npm run dev
```
   
