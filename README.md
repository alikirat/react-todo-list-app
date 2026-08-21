# React Todo List

A client-side todo list app built with React, using `useReducer` for state
management. Seeded with 20 sample todos (in the shape of the
[JSONPlaceholder](https://jsonplaceholder.typicode.com/todos) API) on load.

## Features

- Add new todos
- Toggle a todo complete/incomplete
- Edit a todo's title in place
- Delete a todo (**only allowed once it's marked complete**, as a small
  guard against accidentally deleting unfinished items)

## Tech Stack

React 19, Vite. No backend. All state lives in memory via `useReducer` and
resets on page refresh.

## Running it

```bash
npm install
npm run dev
```

The app runs on `http://localhost:5173` by default.
