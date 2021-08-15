FROM debian:8
ENV host=www.google.com
COPY ping.sh .
CMD ["sh", "ping.sh"]

# docker build -t pinger .
# docker run --rm -e host=www.bing.com pinger