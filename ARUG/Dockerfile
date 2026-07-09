ARG version 
FROM almalinux:${version:-9}
ARG course="docker" \
    trainer="Kotesh"\
    duration="2 weeks" 
ENV course=${course} \
    trainer=${trainer}\
    duration=${duration}
RUN echo "Course name is: ${course} and trainer name is: ${trainer} and duration is: ${duration}"