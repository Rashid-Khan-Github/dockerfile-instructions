ARG version
FROM almalinux:${version:-8}
# default vaule of version can be given using :- after variable name
# ARG variable before FROM will not work after FROM instruction
RUN echo "verison passed by user is ${verison}"

ARG COURSE
ARG TRAINER 
ENV COURSE=${COURSE}
ENV TRAINER=${TRAINER}

RUN echo "Course is ${COURSE}, trainer is ${TRAINER}"


