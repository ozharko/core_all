cmake_minimum_required(VERSION 3.9)
project(kostya_2_1)

set(CMAKE_CXX_STANDARD 11)

add_executable(kostya_2_1
        libft/ft_add_at_end.c
        libft/ft_addlast.c
        libft/ft_atoi.c
        libft/ft_bzero.c
        libft/ft_ch_to_hex.c
        libft/ft_dell_arr_str.c
        libft/ft_hex_to_int.c
        libft/ft_is_valid_hex.c
        libft/ft_is_valid_nbr.c
        libft/ft_isalnum.c
        libft/ft_isalpha.c
        libft/ft_isascii.c
        libft/ft_isdigit.c
        libft/ft_isprint.c
        libft/ft_itoa.c
        libft/ft_itoa_base.c
        libft/ft_len_arr_str.c
        libft/ft_lstadd.c
        libft/ft_lstdel.c
        libft/ft_lstdel_top.c
        libft/ft_lstdelone.c
        libft/ft_lstiter.c
        libft/ft_lstmap.c
        libft/ft_lstnew.c
        libft/ft_memalloc.c
        libft/ft_memccpy.c
        libft/ft_memchr.c
        libft/ft_memcmp.c
        libft/ft_memcpy.c
        libft/ft_memdel.c
        libft/ft_memmove.c
        libft/ft_memset.c
        libft/ft_printf.c
        libft/ft_printf.h
        libft/ft_putchar.c
        libft/ft_putchar_fd.c
        libft/ft_putendl.c
        libft/ft_putendl_fd.c
        libft/ft_putnbr.c
        libft/ft_putnbr_fd.c
        libft/ft_putstr.c
        libft/ft_putstr_fd.c
        libft/ft_strcat.c
        libft/ft_strchr.c
        libft/ft_strclr.c
        libft/ft_strcmp.c
        libft/ft_strcpy.c
        libft/ft_strdel.c
        libft/ft_strdup.c
        libft/ft_strequ.c
        libft/ft_striter.c
        libft/ft_striteri.c
        libft/ft_strjoin.c
        libft/ft_strlcat.c
        libft/ft_strlen.c
        libft/ft_strmap.c
        libft/ft_strmapi.c
        libft/ft_strncat.c
        libft/ft_strnchr.c
        libft/ft_strncmp.c
        libft/ft_strncpy.c
        libft/ft_strnequ.c
        libft/ft_strnew.c
        libft/ft_strnew_cpy.c
        libft/ft_strnstr.c
        libft/ft_strrchr.c
        libft/ft_strsplit.c
        libft/ft_strstr.c
        libft/ft_strsub.c
        libft/ft_strtrim.c
        libft/ft_swapbits.c
        libft/ft_tolower.c
        libft/ft_toupper.c
        libft/get_next_line.c
        libft/get_next_line.h
        libft/libft.h
        libft/pf_funcs.c
        libft/pf_get_sign_arg.c
        libft/pf_itoabase.c
        libft/pf_lst_ctr.c
        libft/pf_lst_res.c
        libft/pf_parse_fl_aux1.c
        libft/pf_parse_fl_aux2.c
        libft/pf_parse_fl_nbr.c
        libft/pf_parse_fl_str.c
        libft/pf_parse_nbr.c
        libft/pf_parse_p.c
        libft/pf_parse_str.c
        libft/pf_uchr.c
        main.c
        main.h
        op.c
        op.h
        read_bots.c
        visual.h make_cycle.c
        fun_cor/fun_ld.c
		fun_cor/fun_st.c
		fun_cor/fun_add.c
		fun_cor/fun_sub.c
		fun_cor/fun_and.c
		fun_cor/fun_or.c
		fun_cor/fun_xor.c
		fun_cor/fun_zjmp.c
		fun_cor/fun_ldi.c
		fun_cor/fun_sti.c
		fun_cor/fun_lld.c
		fun_cor/fun_lldi.c
		fun_cor/fun_aff.c
		fun_cor/fun_fork.c
		make_cycle.c
		)
