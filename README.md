# Laravel + Next.js Pokemon List

## Get Started

1. Clone this repository on your computer
2. Navigate to the project's root directory and run the following command to set up your development environment:
```
ddev setup
```
This command will install all required Composer dependencies, generate a key for your application, execute Laravel migrations to create the database, and import Pokémon data.

3. After setting up the Laravel project, navigate to the `nextjs-pokemon-list` folder and install its dependencies with yarn install or npm install. Then, copy the `.env.example` file to `.env.local`, and provide the URL of your backend. Replace `APP_URL` with the actual backend URL from your Laravel project's `.env` file:

```
NEXT_PUBLIC_BACKEND_URL=APP_URL
```

4. To start the application, run the following command inside the `nextjs-pokemon-list` directory. The application will be available at [http://localhost:3000](http://localhost:3000):

```
npm run dev
```

## Usage

Once you've set up the project, you can access the frontend (FE) in your web browser at [http://localhost:3000](http://localhost:3000).

## Authors

- Vasilije Tomović
