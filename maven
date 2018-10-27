####Install Maven using Jenkins########

#######Get the URL#########
wget http://mirrors.viethosting.vn/apache/maven/maven-3/3.3.9/binaries/apache-maven-3.3.9-bin.tar.gz

########Unpack Maven #######
sudo tar -xf apache-maven-3.3.9-bin.tar.gz  -C /usr/local
#####Create Symbolic link#########
cd /usr/local
sudo ln -s apache-maven-3.3.9 maven
######Export maven paths#########
touch /etc/profile.d/maven.sh
sudo vi /etc/profile.d/maven.sh
i
export M2_HOME=/usr/local/maven
export PATH=${M2_HOME}/bin:${PATH}
:wq!
source /etc/profile
mvn -v
