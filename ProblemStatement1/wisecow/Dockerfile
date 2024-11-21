FROM redhat
RUN dnf update && dnf install -y fortune-mod cowsay
COPY wisecow.sh /wisecow.sh
ENTRYPOINT ["/wisecow.sh"]
