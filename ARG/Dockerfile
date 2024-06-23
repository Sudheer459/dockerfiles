ARG version
FROM almalinux:${version:-8}
#RUN cat /etc/*release
ARG COURSE=Docker
ARG TRAINER=sudheer
ENV Duration=120mins
RUN echo "Course is: ${COURSE}, Trainer is: ${TRAINER}, Duration is: ${Duration}"
CMD [ "sleep","100" ]