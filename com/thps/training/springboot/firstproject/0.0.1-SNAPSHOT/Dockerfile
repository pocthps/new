FROM docker-registry.default.svc:5000/sample/java-docker:latest
RUN git clone https://github.com/pocthps/new.git
RUN find ./ -name "firstproject-0.0.1-20180221.193621-1.jar" -exec cp -R {} ./  \\;
CMD ["java -jar firstproject-0.0.1-20180221.193621-1.jar"]
