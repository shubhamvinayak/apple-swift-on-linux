//run this job on a docker enabled build node
node('docker-cloud') {
  //this will pull the swift image, run it, and execute the following block of steps
  docker.image('swiftdocker/swift:latest').inside {
    //trivial, yes - but it works
    sh 'swift --version'
  }
}
