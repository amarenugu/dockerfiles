ARG version
FROM almalinux:${version:-9}
ARG course="docker" \
    trainer="SivaKumar" \
    duration="10hrs"
ENV course=${course} \
    trainer=${trainer} \
    duration=${duration}
RUN echo "Course ${course}, Duration ${duration}, Trainer ${trainer}, Version is: ${version}"