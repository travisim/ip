# **Sinatra: An assistant with Swing**

Sinatra can help you keep track of your life's events

- Inspired by Frank Sinatra
- Simply Spectacular
- Our most advanced chatBot yet

To get started:

1. Download the `Sinatra.jar` file from [here](https://github.com/travisim/ip/releases).
2. Run the command `java -jar "Sinatra.jar"`

## Features:

1. **Add tasks**
   Adds tasks to the list.
    - **Format**: `todo [task]`
    - **Examples**:
        - `todo dance`
        - `todo exercise`

2. **Add deadlines**
   Adds a deadline to the list.
    - **Format**: `deadline [task] /by [date and time]`
    - **Examples**:
        - `deadline return book /by 2/12/2019 1800`
        - `deadline submit report /by 5/10/2024 1200`

3. **Add events**
   Adds an event to the list.
    - **Format**: `event [task] /from [start time] /to [end time]`
    - **Examples**:
        - `event project meeting /from Mon 2pm /to Mon 4pm`
        - `event team lunch /from Fri 12pm /to Fri 1pm`

4. **Mark/unmark tasks**
   Marks a task as done or not done.
    - **Format**: `mark [task number]` or `unmark [task number]`
    - **Examples**:
        - `mark 1`
        - `unmark 2`

5. **Search for tasks**
   Searches for tasks content containing the keyword.
    - **Format**: `find [keyword]`
    - **Examples**:
        - `find project`
        - `find book`

6. **List all tasks**
   Lists all tasks in the task list.
    - **Format**: `list`
    - **Examples**:
        - `list`

7. **Delete tasks**
   Deletes a task from the list.
    - **Format**: `delete [task number]`
    - **Examples**:
        - `delete 2`
        - `delete 3`

8. **Duplicate tasks detection**
   Automatically detects and prevents adding duplicate tasks.
    - **Description**: When you try to add a task that already exists in the list, Sinatra will notify you that "Task
      already exists and was not added"
      
## Legal Disclaimer

This software, Sinatra, is provided "as is", without warranty of any kind, express or implied, including but not limited
to the warranties of merchantability, fitness for a particular purpose, and noninfringement. In no event shall the
authors or copyright holders be liable for any claim, damages, or other liability, whether in an action of contract,
tort, or otherwise, arising from, out of, or in connection with the software or the use or other dealings in the
software.

This project has referenced code and solutions from popular websites like Stack Overflow, GeeksforGeeks, and more.

## Credits

- **JavaFX**: This project uses JavaFX, an open-source, next-generation client application platform for desktop, mobile,
  and embedded systems built on Java.
- **Gradle**: This project is built using Gradle, an open-source build automation tool that is designed to be flexible
  enough to build almost any type of software.
- **Frank Sinatra**: The project is inspired by Frank Sinatra, an American singer, actor, and producer who was one of
  the most popular and influential musical artists of the 20th century.
- **GitHub**: This project is hosted on GitHub, a platform for version control and collaboration, allowing developers to
  work together on projects from anywhere.

## Image Sources

- [Dean Martin on IMDb](https://www.imdb.com/name/nm0001509/)
- [Frank Sinatra on The Movie Database](https://www.themoviedb.org/person/4347-frank-sinatra/images/profiles)

For more information, please visit the [GitHub repository](https://github.com/travisim/ip).
