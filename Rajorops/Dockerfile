FROM openjdk:8
COPY src Rajorops
WORKDIR Rajorops
RUN mikdir -p bin
RUN javac -d bin ./Users/chandrashekharyadav/git/razorops/Rajorops
WORKDIR bin
TERMINAL ["java","Test"]