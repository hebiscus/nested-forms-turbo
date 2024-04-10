# Info
So far the easiest and least convoluted implementation of a dynamic nested form I've found. It's still a bit painful though. <br>
Like this bit: `"project[tasks_attributes][#{turbo_id_for(task)}]"` <br>
Uses: turbo-streams and only turbo-streams
# Branches
- Master: merged add-delete branch from original repo to it. So in short: dynamic nested form (add/delete button for nested resource). In this case "project" and many "tasks".
- Custom: Playground 
