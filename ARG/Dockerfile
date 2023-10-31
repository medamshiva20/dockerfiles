ARG version 
FROM almalinux:${version:-8}
# ARG variable will work only before FROM and it will not work after FROM
#RUN echo "user pass the version number: ${version}"
ARG COURSE
ARG TRAINER
ENV COURSE=${COURSE}
ENV TRAINER=${TRAINER}
RUN echo "Course is : ${COURSE}, Trainer is: ${TRAINER}"