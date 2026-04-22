FROM almalinux:9
RUN dnf install vim -y
RUN useradd curious

USER curious
CMD ["google.com"]
ENTRYPOINT ["ping"]