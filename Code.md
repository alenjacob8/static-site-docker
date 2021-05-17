sudo su
echo "jenkins ALL=(ALL) NOPASSWD: ALL" >> /etc/sudoers
echo 'Defaults:jenkins !requiretty' >> /etc/sudoers
