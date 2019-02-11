pipeline {

    agent any

    stages {

        stage ('Build Servlet Project') {

            steps {

                /*For windows machine */

               bat  'mvn clean package'



                /*For Mac & Linux machine */

               // sh  'mvn clean package'

            }



        

        }



        stage ('Deploy Build in Staging Area'){

            steps{



                build job : 'Deploy-StagingArea-Piple'



            }

        }



       



            

        }

    }

}
