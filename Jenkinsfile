pipeline {
node(‘Ansible-Agent’){
  git url: 'https://github.com/pavankanna/Spring_PetClinic.git'
  sh 'mvn -B clean verify'
}
}	