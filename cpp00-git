# **************************************************************************** #
#                                                                              #
#                                                         :::      ::::::::    #
#    Makefile                                           :+:      :+:    :+:    #
#                                                     +:+ +:+         +:+      #
#    By: marvin <marvin@student.42.fr>              +#+  +:+       +#+         #
#                                                 +#+#+#+#+#+   +#+            #
#    Created: 2024/04/22 01:35:35 by svydrina          #+#    #+#              #
#    Updated: 2024/04/22 02:04:19 by marvin           ###   ########.fr        #
#                                                                              #
# **************************************************************************** #

NAME = megaphone

compile = c++

flags = -std=c++98 -Wall -Werror -Wextra

SRC = megaphone.cpp

OBJ = megaphone.o

all: $(NAME)

$(NAME): $(OBJ)
	$(compile) -o $(NAME) $(flags) $(OBJ)

%.o: %.cpp
	@$(compile) $(flags) -o $@ -c $<

clean:
	rm -f $(OBJ)

fclean: clean
	rm -f $(NAME)

re: fclean all  
