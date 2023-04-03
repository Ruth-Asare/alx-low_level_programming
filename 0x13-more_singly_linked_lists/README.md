C - More singly linked lists DIR 📁 Tests ✔️ test: Directory to the Tests.
lists.h: lists.h file contains prototypes to the functions.
File Prototype struct listint_s int n struct listint_s *next typedef listint_t struct listint_s 0-print_listint.c size_t print_listint(const listint_t *h); 1-listint_len.c size_t listint_len(const listint_t *h); 2-add_nodeint.c listint_t *add_nodeint(listint_t **head, const int n); 3-add_nodeint_end.c listint_t *add_nodeint_end(listint_t **head, const int n); 4-free_listint.c void free_listint(listint_t *head); 5-free_listint2.c void free_listint2(listint_t **head); 6-pop_listint.c int pop_listint(listint_t **head); 7-get_nodeint.c listint_t *get_nodeint_at_index(listint_t *head, unsigned int index); 8-sum_listint.c int sum_listint(listint_t *head); 9-insert_nodeint.c listint_t *insert_nodeint_at_index(listint_t **head, unsigned int idx, int n); 10-delete_nodeint.c int delete_nodeint_at_index(listint_t **head, unsigned int index); 100-reverse_listint.c listint_t *reverse_listint(listint_t **head); 101-print_listint_safe.c size_t print_listint_safe(const listint_t *head); 102-free_listint_safe.c size_t free_listint_safe(listint_t **h); 103-find_loop.c listint_t *find_listint_loop(listint_t *head); Tasks 📃 0. Print list
0. Print list
Write a function that prints all the elements of a listint_t list.

1. List length
Write a function that returns the number of elements in a linked listint_t list.

2. Add node
Write a function that adds a new node at the beginning of a listint_t list.

3. Add node at the end
Write a function that adds a new node at the end of a listint_t list.

4. Free list
Write a function that frees a listint_t list.

5. Free
Write a function that frees a listint_t list.

6. Pop
Write a function that deletes the head node of a listint_t linked list, and returns the head node’s data (n).

7. Get node at index
Write a function that returns the nth node of a listint_t linked list.

8. Sum list
Write a function that returns the sum of all the data (n) of a listint_t linked list.

9. Insert
Write a function that inserts a new node at a given position.

10. Delete at index
Write a function that deletes the node at index index of a listint_t linked list

100-reverse_listint.c: C function that reverses a listint_t linked list using a maximum of one loop and two variables. Returns a pointer to the first node of the reversed list. 12. Print (safe version)
101-print_listint_safe.c: C function that prints a listint_t linked list safely (ie. can free lists containing loops). Returns the number of nodes in the listint_t list. 13. Free (safe version)
102-free_listint_safe.c: C function that frees a listint_t linked list safely (ie. can free lists containing loops). Returns the size of the list that was freed. Sets the head to NULL. 14. Find the loop
103-find_loop.c: C function that finds the loop contained in a listint_t linked list using a maximum of two variables. If no loop is found - returns NULL. Otherwise - returns the address of the node where the loop starts.

