node(‘linux’){
  git url: 'https://github.com/devopscube/simple-maven-pet-clinic-app.git'
  def mvnHome = tool 'M2'
  env.PATH = "${MNHOME}/bin:${env.PATH}"
  sh 'mvn -B clean verify'
}
