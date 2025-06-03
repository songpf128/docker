FROM thetimeiswater/nginx:1.27.5

# 将修改后的 nginx.conf 复制到容器中
COPY ./nginx.conf /etc/nginx/nginx.conf
# 将站点信息也复制进去 
COPY conf.d /etc/nginx/conf.d