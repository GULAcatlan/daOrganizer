#
#	Makefile for daOrganizer
#	
#	-- daOrganizer is part of the StudentHelper project.
#
#	This project is released by the GULA group <gula@apolo.acatlan.unam.mx> and you can contact us for any question about it.
#   Every file has its own license, but we release a general license in the root of the project.
#
#
#	Authors of this Makefile:
#		- Sier (a.k.a Sinuhé Jaime Valencia) <sierisimo@gmail.com> <gula@apolo.acatlan.unam.mx>
#

#	Ubications
SRC_DIR=src

FILES=top body daOrganizer bottom
SRC_NAMES=$(addprefix $(SRC_DIR)/,$(addsuffix .js,$(FILES)))

NAME=daOrganizer
RESULT=$(addsuffix .js,$(NAME))

all: daOrganizer

daOrganizer: $(SRC_NAMES)
	cat $(SRC_NAMES) > $(RESULT)

clean:
	rm -rf $(RESULT)