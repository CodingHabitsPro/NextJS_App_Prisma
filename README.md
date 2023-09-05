 # Next.js Todo App with Prisma and Tailwind

This is a simple Next.js app that allows users to create and manage todo items. It uses Prisma for the database and Tailwind for styling.

## Prerequisites

To run this app, you will need the following:

* Node.js 16 or later
* npm 8 or later
* A PostgreSQL database

## Installation

1. Clone the repo:

```
git clone https://github.com/your-username/next-js-todo-app.git
```

2. Install the dependencies:

```
npm install
```

3. Create a `.env` file in the root directory of the project and add your database connection string to it:

```
DATABASE_URL=postgres://localhost:5432/next-js-todo-app
```

4. Start the development server:

```
npm run dev
```

5. Open your browser and go to `http://localhost:3000` to see the app.

## Usage

To create a new todo item, click on the "New" button in the header. A form will appear where you can enter the title of the todo item. Click on the "Create" button to save the todo item.

To mark a todo item as completed, click on the checkbox next to the todo item.

To delete a todo item, click on the "X" button next to the todo item.

## Code Explanation

The code for this app is located in the following files:

* `next.config.js`: This file contains the Next.js configuration for the app.
* `package.json`: This file contains the dependencies for the app.
* `prisma/migrations/20230905145332_dev/migration.sql`: This file contains the SQL migrations for the app.
* `prisma/schema.prisma`: This file contains the Prisma schema for the app.
* `src/app/layout.tsx`: This file contains the layout for the app.
* `src/app/new/page.tsx`: This file contains the page for creating new todo items.
* `src/app/page.tsx`: This file contains the page for listing todo items.
* `src/components/TodoItem.tsx`: This file contains the component for displaying todo items.
* `src/db
