##
## EPITECH PROJECT, 2020
## Makefile
## File description:
## Makefile
##

SRC	=	my_putchar.c		\
		my_put_nbr.c		\
		my_putstr.c			\
		my_puterror.c		\
		my_strlen.c			\
		my_arrlen.c			\
		my_getnbr.c			\
		my_atof.c			\
		my_strcmp.c			\
		my_strncmp.c		\
		my_strcpy.c			\
		my_strdup.c			\
		my_revstr.c			\
		my_strcat.c			\
		my_str_isnum.c		\
		read_file.c			\
		str_tab.c			\
		malloc_arr.c		\
		free_arr.c			\
		display_helper.c	\

OBJ	=	$(SRC:.c=.o)

NAME	=	libmy.a

CPPFLAGS =	-I../include/

CFLAGS =	-W -Wall -Wextra

RM	=	rm -f

libmy:	$(OBJ)
	ar rc $(NAME) $(OBJ)
	mv $(NAME) ../$(NAME)

clean:
	$(RM) $(OBJ)

fclean: clean
	$(RM) ../$(NAME)

re:     fclean all

.PHONY: libmy clean fclean re
