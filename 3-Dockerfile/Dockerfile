FROM odise/busybox-curl
#ubuntu:xenial

#RUN apt-get update && apt-get install -y curl && apt-get clean && rm -rf /var/lib/apt/lists

RUN curl https://gist.githubusercontent.com/paulirish/292907/raw/b83979ea71f0eab58105c6b8ad825e82970bb483/gistfile1.js > art

CMD ["cat", "art"]