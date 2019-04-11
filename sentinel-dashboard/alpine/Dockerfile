FROM openjdk:8-jre-alpine

ENV SENTINEL_DASHBOARD_VERSION 1.4.0

# -O 指定文件名
RUN wget -O sentinel-dashboard.jar https://github.com/alibaba/Sentinel/releases/download/1.4.0/sentinel-dashboard-1.4.0.jar

EXPOSE 8080

ENTRYPOINT java -jar sentinel-dashboard.jar