# To Do Tasks

A simple and handy extension for [Visual Studio Code](http://code.visualstudio.com/) to organize your to-do tasks.

![screenshot](https://user-images.githubusercontent.com/81008/44176006-0bf68f00-a0b6-11e8-8cfd-6df4825411e6.png)

## How to build and install

- Install vsce: `npm install -g vsce`
- Install deps: `npm install`
- Make glorious changes
- Update version number in `package.json`
- Build package: `vsce package`
- Install package: `code --install-extension todotasks-plus-x.x.x.vsix`

## How to use

Create a new file and save with todo or tasks file extension.

**NOTE:** Commands listed below are triggerred only on files with above extensions.

### Projects:

    * Anything with colon at the end of the line is a project title
    * You can nest projects inside each other
    * You can fold projects and sub projects

### Tasks:

    New Task:
        * Press Cmd+Enter (Ctrl+Enter on Windows and Linux) to add a new task
        * You can also use the Command pallette to create a new task by typing To Do:New Task
        * If you are on a new line, it will create a new task on the current line
        * If you are on a line with some text pressing new task shortcut will convert it to a task
        * New tasks are nested as much as the previous task

    More Actions:
        * Complete a task by pressing Alt+d @done
        * Re-open a completed task by pressing Alt+d
        * Cancel a task by pressing Alt+c @cancelled
        * Complete a cancelled task by pressing Alt+d
        * You can also use the Command pallette to complete or cancel a task by typing
          To Do:Complete Task or To Do:Cancel Task

    Tagging:
        * You can add tags using @ sign, like this @tag
        * You can use following pre-existing tags to mark tasks @critical @high @low @today
        * Auto intellisense is provided to help you in finding tags

More to come. See [Tasks](todotasks-project.tasks).

## License

[MIT](LICENSE.md)
