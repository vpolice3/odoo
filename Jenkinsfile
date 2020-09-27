pipeline{
  agent any
  stages{
    satge('Build images'){
      sh '''
        docker build -f "Dockerfile" -t vikaspolicedockerhub/odoo:latest .
      '''
    }
  }
}
