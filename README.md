# Personal library manager
## Technical requirements

* Python 3.11
* olorama third party package
* Visual Studio Code
* Jupyter extension install in visual studio

## How the application works
### Start the applcations
* Open personal_library_manager.ipynb\
    ![Open relevant jupyter Note book](/img/notebook.png "Working Jupyter notebook")
* Select python environment you want to use by pressing ctrl+shift+p and then type python intpreter\
    ![Select the environment](/img/command_plate.png "Python intpreter")
* Any Python 3.11 should be fine\
    ![Select the environment](/img/env_selection.png "Python intpreter")
* Click on Run All\
    ![Run the code](/img/run_all.png "Run the code")

### Welcome screen
Colourful welcome message along with application version will be  printed.\
![Welcome message](/img/welcome_message.png "Welcome message")


### Main menu

Once the application is started Visual Studio will ask you to select on of the following options:
| Key | Description                                                                                      |
| --- | ------------------------------------------------------------------------------------------------ |
| a   | Will ask you to add a title and an author of a book to your library.                             |
| l   | Will list all the books registered in your library.                                              |
| r   | Will add short review for a book you have read.                                                  |
| s   | Will search for a book in your library.                                                          |
| q   | Will safely quit the application by saving book list to books.csv and review list to reviews.csv |

![Main Menu](/img/main_menu.png "Main Menu")

Note: As any application you should be able to quit using CTRL+C but it is not recommended as might lose/corrupt your data


### Add a Book.
* Select add a book from the main menu\
    ![Add a book from menu](/img/select_add_a_book.png "Add a book from the main menu")
* Enter the title of the new book\
    ![Title of the new book](/img/title_of_the_new_book.png "Title of the new book")
* Enter the author of the new book\
    ![Author of the new book](/img/author_of_the_new_book.png "Author of the new book")
* Receive a confirmation that the new book was added successfully\
    ![The new book was added successfully](/img/new_book_added_successfully.png "The new book was added successfully")

### List all books.
* Select List all books from the menu\
    ![List all books from the menu](/img/list_all_books.png "List all books from the menu")
* Enter the title of the new book\
    ![Printed list of the books](/img/list_all_book_result.png "Printed list of the books")
### Add a review.
* Select add a review from the main menu\
    ![Add a review from menu](/img/review_from_main_menu.png "Add a review from the main menu")
* Enter the title of the new book\
    ![Title of the new book](/img/book_to_review_title.png "Title of the new book")
* Enter the author of the new book\
    ![Short review of the new book](/img/actual_short_review_entry.png "Short review of the new book")
* Receive a confirmation that the new book was added successfully\
    ![The review was added successfully](/img/short_review_confirmation_messege.png "The review was added successfully")
### Search for books either by Title or by Author
* Select search for a book from the main menu\
    ![Select search from menu](/img/review_from_main_menu.png "Add a review from the main menu")
* Choose whether you want to search by title or author book
* If by title then enter t \
    ![Select search by title](/img/search_by_title.png "Select search by title")
* Enter the title you want to search for \
    ![Enter title in search](/img/title_search.png "Enter title in search")
* Now it will show the results of the search \
    ![Search by title results](/img/search_by_title_results.png "Search by title results")
* If by author then enter a in the search menu\
    ![Select search by title](/img/search_by_author.png "Select search by title")
* Enter the auth you want to search for \
    ![Enter author name in search](/img/author_search.png "Enter author name in search")
* Now it will show the results of the search \
    ![Search by author results](/img/search_by_author_results.png "Search by author results")

### Quit the application
* Select quit from the main menu\
    ![Quit from menu](/img/quit_from_menu.png "Quit from menu")
* Save books.csv and reviews.csv datasets from application in-memory\
    ![Save datasets](/img/save_data_results.png "Save datasets")



## Sample data
books_samle.csv is already uploaded in the project in sample_data folder just copy it to the main/working folder and then rename it to books.csv and run the application.

## Possible areas of improvement

* List all reviews.
* Search for reviews by title.
* Use pandas to load and save csv files.
* Join books and reviews datasets.
* Show reviews in books search results.
* Search for book titles by regular expression.