node {
    stage('Clone') {
    git branch: 'main', url: 'https://github.com/Ayoub-Ajdour1/testingjenkins/'
}
    stage('Build') {
    sh 'javac Main.java'
}
    stage('Run') {
    sh 'java Main'
}
}
