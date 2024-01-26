ARG version
FROM almalinux:${version:-8}
#ARG variable will work only before FROM and it will not work after FROM
#RUN  echo "version passed by user is:${version}"
ARG COURSE
ARG TRAINER
ENV COURSE=${COURSE} \
    TRAINER=${TRAINER}
RUN echo "Course is:${COURSE} and Trainer is:${TRAINER}"
