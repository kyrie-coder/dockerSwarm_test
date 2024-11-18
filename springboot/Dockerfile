# 使用制品中心的openjdk作为基础镜像
FROM dragonwell-registry.cn-hangzhou.cr.aliyuncs.com/dragonwell/dragonwell:8

# 设置工作目录
WORKDIR /app

# 复制Spring Boot打包好的JAR文件到容器中
COPY app.jar app.jar

# 暴露应用运行的端口（Spring Boot 默认8080端口）
EXPOSE 8080

# 启动Spring Boot应用
ENTRYPOINT ["java", "-jar", "app.jar"]

