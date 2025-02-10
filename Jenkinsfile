pipeline {
    agent any
    stages {
        stage('Clone Repository') {
            steps {
                bat 'git clone https://github.com/Neeha-Sultana/CppAutomation.git'
            }
        }
        stage('Build C++ Program') {
            steps {
                bat 'cd CppAutomation && g++ -o hello.exe main.cpp'
            }
        }
        stage('Run C++ Program') {
            steps {
                bat 'cd CppAutomation && hello.exe'
            }
        }
    }
}