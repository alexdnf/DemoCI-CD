pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                // Запускаем Java-приложение в фоновом режиме
                java -jar ./artifacts/app-mbank.jar
                // Запускаем тесты с выводом информации
                ./gradlew test --info
            }
        }
    }
}
