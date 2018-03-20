FROM docker-registry.default.svc:5000/sample/java-docker:latest
RUN git clone https://github.com/pocthps/new.git
RUN find ./ -name *.jar -exec cp {} ./root.jar \;
EXPOSE 7000
#RUN chmod u+x /home/java-app/firstproject-0.0.1-20180221.193621-1.jar
RUN echo "#!/bin/sh">/home/java-app/dead.sh
RUN echo 'a=10'>>/home/java-app/dead.sh
RUN echo 'while [ $a -lt 20 ]'>>/home/java-app/dead.sh
RUN echo 'do'>>/home/java-app/dead.sh
RUN echo '  date'>>/home/java-app/dead.sh
RUN echo 'done'>>/home/java-app/dead.sh
RUN chmod u+x /home/java-app/dead.sh

CMD ["/home/java-app/dead.sh"]
#CMD ["java -jar /home/java-app/firstproject-0.0.1-20180221.193621-1.jar"]
