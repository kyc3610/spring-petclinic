pipeline {
  agent any
//JAVA와 Maven Tool 등록
  tools {
    jdk 'jdk17'
    maven 'M3'
  }
  
  stages {
    stage('Git Clone') {
      //GitHub에서 Jenkins로 소스코드 복제
      steps {
        git url: 'https://github.com/kyc3610/spring-petclinic.git', branch: 'main'
      }
    }
      
      
      
  }
}
