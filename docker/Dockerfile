FROM fedora:36

RUN dnf install -y dnf-plugins-core 
RUN dnf install -y jq 
RUN dnf config-manager --add-repo https://rpm.releases.hashicorp.com/fedora/hashicorp.repo 
RUN dnf install -y vault 
RUN setcap -r /usr/bin/vault
		