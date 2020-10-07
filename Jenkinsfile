pipeline{
  agent any
stages{
    stage('Git SCM'){
      options {
              timeout(time: 1, unit: 'HOURS')   // timeout on this stage
          }
      steps{
       sh'git url "https://github.com/vpolice3/odoo.git"'  
      }
    }
  }
}
