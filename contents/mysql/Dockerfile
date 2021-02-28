FROM mysql:8.0
# 指定の場所にログを記録するディレクトリを作る
RUN mkdir /var/log/mysql
RUN chown mysql:mysql /var/log/mysql 
RUN chown mysql:mysql /var/lib/mysql
RUN chown mysql:mysql /usr/sbin/mysqld 
RUN touch /var/log/mysql/mysqld.log

EXPOSE 3306