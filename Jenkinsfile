//run this job on a docker enable build node
node('docker-cloud') {
  docker.image('swiftdocker/swift:latest').inside {
    sh 'swift --version'
  }
}
