NAME = libft.a
CF = -Wall -Wextra -Werror  -I -c
SOURCE = 
ft_strlen.c \
ft_strrchr.c \
ft_atoi.c
OBJECTS = $(SOURCE:.c=.o)

all: $(SOURCE)
				$(NAME): $(OBJ)
				ar rcs $(NAME) $(OBJ)

				$(OBJ): $(SOURCE)
				gcc $(CF) $(SOURCE)

clean: 
				rm -f $(OBJ)
				rm -f $(SOURCE)

fclean:			rm -f $(NAME)

re: fclean all

.PHONY: clean fclean all re
