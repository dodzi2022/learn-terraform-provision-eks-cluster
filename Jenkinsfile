pipeline {
       agent any
      tools {
  terraform 'myTerraform'
}
  stages{
    stage('Terraform Init '){
      steps {
                 sh 'terraform init -upgrade'
              
             
      }
    }
   /*  stage('Terraform plan'){
      steps {
              sh 'terraform plan'
              
             
      }
    } */
     /* stage('Terraform apply'){
      steps {
           //   sh 'terraform apply --auto-approve'
            
             
      }
    } **/
         stage('Terraform destroy'){
      steps {
                sh 'terraform destroy --auto-approve'
     }
     } 
     
   } 
}

