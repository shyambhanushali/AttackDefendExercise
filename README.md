# AttackDefendExercise
<h3>Automated -configuring a vulnerable system with CVE of my choice using Ansible and demonstrating the attack on that machine</h3>
<h3> CVE-2019-14287- Sudo Privilege Escalation Vulnerability </h3>

<h1> Pre Configuration </h1>

<h2> SSH must be installed and enabled </h2>

<h4>sudo apt install ansible</h4>
<h4>sudo apt install openssh-server</h4>
<h4>sudo systemctl status ssh</h4>
<h4>sudo ufw allow ssh</h4>

<h2> Installing Ansible </h2>
<h4> sudo apt-add-repository --yes --update ppa:ansible/ansible</h4>
<h4> sudo apt install ansible</h4>

<h1>Usage</h1>

<h4>ansible-playbook playbook.yml</h4>
