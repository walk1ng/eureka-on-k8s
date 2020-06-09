FROM java:8

EXPOSE 8761
ADD init.sh /init.sh
ADD eureka.jar /eureka.jar
RUN rm /bin/sh && ln -s /bin/bash /bin/sh
ENTRYPOINT [ "/bin/bash","-c","source /init.sh" ]
