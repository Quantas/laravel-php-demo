# Dev Testing Repo

Preferably use the VS Code - Remote Containers extension.
Once the container has started run:
- composer install
- cp .env.example .env
- php artisan key:generate
- php artisan serve
- Expose 8000 in the remote containers extension
- navigate to localhost:8000 in your browser 
