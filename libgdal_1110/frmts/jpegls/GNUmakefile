
OBJ	=	jpeglsdataset.o

include ../../GDALmake.opt

CPPFLAGS	:=	$(GDAL_INCLUDE) $(CPPFLAGS) $(CHARLS_INC)

default:	$(OBJ:.o=.$(OBJ_EXT))

clean:
	rm -f *.o $(O_OBJ)

install-obj:	$(O_OBJ:.o=.$(OBJ_EXT))
