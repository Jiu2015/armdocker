FROM arm32v7/ubuntu:18.04
COPY BaiduPCS-Go /baidu/
RUN mkdir /baidu/download/ && \
ln -s /baidu/BaiduPCS-Go /usr/bin/
VOLUME [ "/root/Downloads" ]
CMD [ "BaiduPCS-Go" ]