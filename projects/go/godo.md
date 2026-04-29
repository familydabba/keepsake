# Godo
A todo list cli in Go. I am making this as a way to revise go fundamentals and get better at it. 

## Plan
- Add a new task: priority and deadline are optional
  `godo add <task> <priority> <deadline-timestamp>`
- Edit an existing task
  `godo edit <ID> --d “new description” --p “high” --t “24-04-2026”`
- List tasks: defaults to listing pending tasks
  `godo list` `--completed`, `--all`, `--priority high`, `--today`, `--timestamp 24-04-2026` 
- Mark tasks completed
  `godo mark <ID>`
- Search tasks:
  `godo search “keyword”`
- Get todays tasks
  `godo today`
- 