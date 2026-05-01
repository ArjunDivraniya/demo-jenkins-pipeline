pipeline {
agent any

stages {

    stage('Build') {
        steps {
            bat 'javac CrudOperation.java'
        }
    }

    stage('Run') {
        steps {
            bat 'echo 5 | java CrudOperation'
        }
    }
}

}
