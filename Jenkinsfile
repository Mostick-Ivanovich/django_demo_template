pipeline {
    agent any 
    stages {
        stage('Test') {
            steps {
                echo 'Запуск тестов Django...'
            
                sh '''
                    python manage.py test
                '''
            }
           
        }
    }
}