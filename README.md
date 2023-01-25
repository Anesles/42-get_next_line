# **get_next_line (Cursus from 42 Porto)**
## **Grade: 112/100**
---
### **Summary:**

In this project I had to develop a function that reads a file line by line.

#### **Installing and running the project:**
* Clone this repository.
```
git clone git@github.com:Anesles/42-get_next_line.git
```
* Create a test file with a main that uses get_next_line.
``` C
#include "get_next_line.h"

int main(void)
{
	int	fd;

	fd = open("test.txt", O_RDONLY);
	printf("%s", get_next_line(fd));
	close(fd);
}
```
* Compile and run.
```
cc -Wall -Wextra -Werror name_of_file.c get_next_line.c get_next_line_utils.c
./a.out
```
## Disclaimer
> At [42School](https://en.wikipedia.org/wiki/42_(school)), almost every project must be written in accordance to the [Norm](./extras/en_norm.pdf), the schools' coding standard. As a result, the implementation of certain parts may appear strange and for sure had room for improvement. #42-get_next_line
