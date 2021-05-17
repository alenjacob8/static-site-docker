<h1> Prerequisities </h1>
<h2> Configure the Jenkins to execute as Sudoers </h2>

Prerequisities
--------------------------
- Changes to be made for Jenkins to be able to run docker

<code>sudo su</code><br>

<code>echo "jenkins ALL=(ALL) NOPASSWD: ALL" >> /etc/sudoers</code></br>

<code>echo 'Defaults:jenkins !requiretty' >> /etc/sudoers</code></br>
