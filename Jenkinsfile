@Library("test_library@main") _
pipeline {
    agent any
    stages {
        stage("Calling") {
            steps {
                echo "Calling the Global Library."
                script{
                    lib_module_1.func_from_module_1()
                }
            }
        }
    }
}
