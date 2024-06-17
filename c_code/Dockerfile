FROM gcc:4.9
# copy file from local to image
COPY main.c  .
RUN gcc -o count main.c
# run cmd during create a con.
CMD ["./count"]

