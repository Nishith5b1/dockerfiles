FROM almalinux:9

RUN dnf install -y nginx

# No ENTRYPOINT here — CMD is the ENTIRE default command, not just default args.
CMD ["nginx", "-g", "daemon off;"]