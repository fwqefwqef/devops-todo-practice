# devops-todo-practice
worker-todo-test

## Endpoints

- `GET /add?content=<text>`: Add a todo item (with an autogenerated `id`) and return the updated list.
- `GET /list`: Retrieve all todo items.
- `GET /migrate`: Assign an `id` to items missing one and return the updated list.
- `GET /delete?id=<id>`: Delete a todo item by `id` and return the updated list.
