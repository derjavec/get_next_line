### Functioning of get_next_line

This code implements the `get_next_line` function, which reads lines from a file descriptor (`fd`) and dynamically returns them.

#### Code Details:

- **Usage of Linked Lists:** The code utilizes linked lists to efficiently store the lines read from the file.

- **Score:** The project achieved a perfect score of 100/100.

#### Main Functions:

- `fill_list`: This function populates a linked list with the lines read from the file.

- `copy_list_to_line`: Copies the content of the linked list to a text line.

- `clean_completed_lines`: Removes completed lines from the linked list once they have been copied to a text line.

- `list_to_line`: Converts the linked list into a text line and cleans up completed lines from the list.

- `get_next_line`: The main function that reads lines from the file and returns the next available line.

This code allows for efficient reading of lines from a file and properly manages memory using linked lists.
