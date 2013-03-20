all: rmat rmat_matlab

rmat: rmat.c
	cc -o rmat rmat.c

rmat_matlab: rmat.c
	cc -DMATLAB -o rmat_matlab rmat.c

clean:
	rm rmat rmat_matlab
