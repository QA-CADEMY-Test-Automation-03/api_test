pipeline {
  agent any
  tools {
    gradle "gradle69"
  }
  stages {
    stage("build") {
      steps {
        bat 'gradle --version'
      }
    }
    stage("test") {
      steps {
        bat 'echo test'
      }
    }
    stage("deploy") {
      steps {
        bat 'echo deploying'
      }
    }
  }
}
