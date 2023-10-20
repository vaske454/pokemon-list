# Laravel + Next.js Pokemon Listing

## Get Started

1. Clone this repository on your computer
2. Navigate to the project's root directory and initiate it by running
```
ddev start
```
3. Install all required Composer dependencies: 

```
ddev composer install
```
4. Then, generate a key for your application by running this command:
```
ddev exec "php artisan key:generate"
```
5. Execute Laravel migrations to create the database:
```
ddev artisan migrate
```
6. Import Pokémon data:
```
ddev artisan app:import-pokemon-data
```
7. Next, navigate to the `nextjs-pokemon-list` folder, copy the `.env.example` file to `.env.local`, and supply the URL of your backend:

```
NEXT_PUBLIC_BACKEND_URL=http://localhost:8000
```

8. Run the application via `npm run dev`. The application will be available at `http://localhost:3000`:

```
npm run dev
```

## Usage

Once you've set up the project, you can access the frontend (FE) in your web browser at [http://localhost:3000](http://localhost:3000). Similarly, you can access the backend (BE) at [http://localhost:8000](http://localhost:8000).

## Authors

- Vasilije Tomović
