FROM fauria/vsftpd

# Default FTP root credentials
ENV FTP_USER=root
ENV FTP_PASS=toor
ENV PASV_ADDRESS=0.0.0.0
ENV PASV_MIN_PORT=21100
ENV PASV_MAX_PORT=21110

# Expose FTP ports
EXPOSE 20 21 21100-21110

# Add sample sensitive file
RUN echo "Sensitive information: Do not share!" > /home/vsftpd/root_secret.txt
