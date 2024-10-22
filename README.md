# 개발 환경 설정
```
# Corretto 17
sudo yum install java-17-amazon-corretto-devel

# Gradle 8
curl -s "https://get.sdkman.io" | bash
source "/home/ec2-user/.sdkman/bin/sdkman-init.sh"
sdk install gradle

# Anne API:
cd ~/environment/anne-api
gradle bootRun

# 테스트
curl localhost:8080/owner/9HG5qPFWcfM2U2gvCskTmBCo5QF3/items
```
