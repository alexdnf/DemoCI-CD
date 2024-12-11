pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
    // Запускаем Java-приложение в фоновом режиме
    sh 'nohup java -jar ./artifacts/app-mbank.jar > /dev/null 2>&1 &'
    
    // Запускаем тесты с выводом информации
    sh './gradlew test --info'
}
        }
    }
}
