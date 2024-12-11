pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
    // Запускаем Java-приложение в фоновом режиме
    sh 'java -jar ./artifacts/app-mbank.jar &'
    sh 'chmod +x ./gradlew'
    // Запускаем тесты с выводом информации
    sh './gradlew test --info'
}
        }
    }
}
