LABEL AUTHOR="tae2089"

# jenkins에 awscli를 설치한 파일입니다.
FROM jenkins/jenkins
USER root

RUN apt-get update && apt install python3-pip jq -y && pip3 install awscli --upgrade && groupadd -g 992 docker && usermod -aG 992 jenkins

USER jenkins
