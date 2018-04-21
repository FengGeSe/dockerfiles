# 基础镜像
FROM mysql:5.7

# utf8mb4 一个字符4个字节存储，这样可以存储表情。
COPY conf.d/ /etc/mysql/conf.d/
COPY mysql.conf.d/ /etc/mysql/mysql.conf.d/

EXPOSE 3306

CMD ["mysqld"]
