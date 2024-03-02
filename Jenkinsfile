node {
    stage('clone') {
      git branch: 'main', url: 'https://github.com/abenfredj/jenkins-labs.git'
}
    stage('build') {
      sh 'javac Main.java'
}
    stage('run') {
      sh 'java Main'
}
}