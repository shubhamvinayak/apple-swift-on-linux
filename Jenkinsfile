//run this job on a docker enabled build node
node {
  checkout scm
  bat "docker images"
  // This step should not normally be used in your script. Consult the inline help for details.
withDockerContainer('node:carbon') {
    sh 'node --version'

  }
}
