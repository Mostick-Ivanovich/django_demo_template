pipeline {
    agent any 
    stages {
        stage('Test') {
            steps {
                echo 'Запуск тестов Django...'
            
                sh '''
                    python3 manage.py test
                '''
            }
           
        }
    }
}