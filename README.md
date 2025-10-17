# 📝 To-Do List Task Manager (Interactive Google Colab Notebook)

This project is a **simple console-based task manager** developed using **Python**.
Users can add, edit, delete, and view their tasks easily.
All tasks are saved into a `.txt` file, which can be downloaded after finishing the session.

## 🚀 Features

* ➕ Add new tasks
* 🧾 List all tasks
* ✏️ Edit existing tasks
* 🗑️ Delete tasks
* 💾 Automatically saves all tasks to `tasks.txt`
* ⬇️ Download your saved task list after finishing

---

## 🧠 How to Use

This notebook is designed to run on **Google Colab**.

1. Upload the notebook file to Google Colab.

2. Run each cell in order.

3. Interact with the menu using the console input:

   ```
   🔹 Task Manager Menu 🔹
   1. List Tasks
   2. Add New Task
   3. Edit Task
   4. Delete Task
   5. Exit
   ```

4. When finished, download your saved task file with:

   ```python
   from google.colab import files
   files.download('tasks.txt')
   ```

---

## 📁 Project Structure

```
📁 To-Do-List-Task-Manager/
├── ToDoList.ipynb        # Google Colab notebook file
├── tasks.txt             # Saved task data (auto-generated)
└── README.md             # Project description
```

---

## 💡 Example Outputs

<p align="center">
  <img src="screenshot.png" alt="Task Manager Menu Example" width="500, 45%"/>
  <img src="screenshot-2.png" alt="Saved Tasks File Example" width="500, 45%"/>
</p>


---

## ⚙️ Requirements

* Python 3.x
* Google Colab (or Jupyter Notebook)
* `tasks.txt` file (auto-generated on first run)

---

## 📜 License

This project is licensed under the **MIT License**.
You are free to use, modify, and distribute this code.

