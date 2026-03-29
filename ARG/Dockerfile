ARG version
FROM almalinux:${version:-9}
ARG NAME="Jaswanth" \
    COURSE="DEVOPS"
#It will not print version because the arg completed
RUN echo "Version: ${version}" && \
    echo "Name: ${NAME}" && \
    echo "Course: ${COURSE}"

# output - => [2/2] RUN echo "Version: ${version}" &&     echo "Name: Jaswanth" &&     echo "Course: DEVOPS"                                                       0.3s
#  => exporting to image                                                                                                                                   0.2s
#  => => exporting layers                                                                                                                                  0.1s
#  => => exporting manifest sha256:dc2bc504e249e474461bc6ebbf021f23e1b229cb36167f1bd96aebca4e681d58      