node {
    def mvnHome
    stage('Preparation') { 
        println("Preparation")
        println("I'm sleeping")
        // sh "ssh cicd@10.148.0.3 'git clone'"

    }
    stage('Build') {
        println("Preparation")
        // sh "npm run test"
        sh "ssh cicd@10.148.0.3 'npm install'"
    }
    stage('Results') {
        println("Preparation")
        aloha()
    }
}
def aloha() {
    println("This is aloha method")
}
