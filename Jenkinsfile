pipeline{
    agent any
    environment{
        firstName = "manoj"
        lastName = "gujjula"
    }
    stages{
        stage('Build'){
            environment{
                middleName = "kumar reddy"
                credentials = credentials('UsernamePassword')
            }
            steps{
                echo 'in steps section'
                echo "firstName is ${firstName}"
                echo "last name is ${lastName}"
                echo "userName is ${credentials_USR}"
                echo "password is ${credentials}"
                
            }
            
        }
    }
}
