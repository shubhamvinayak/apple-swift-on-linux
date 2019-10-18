//run this job on a docker enabled build node
node {
  checkout scm
  bat "docker images"
 // This step should not normally be used in your script. Consult the inline help for details.
withDockerRegistry(credentialsId: 'dockerhub', url: 'https://registry.hub.docker.com') {
    // some block
}
}
