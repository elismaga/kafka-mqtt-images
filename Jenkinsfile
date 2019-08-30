#!/usr/bin/env groovy

dockerfile {
    dockerPush = true
    dockerRepos = ['confluentinc/kafka-mqtt-image',]
    mvnPhase = 'package'
    mvnSkipDeploy = true
    nodeLabel = 'docker-oraclejdk8-eli-compose'  //'docker-oraclejdk8-compose'
    slackChannel = 'tools' //TODO: change to correct team
    upstreamProjects = ['confluentinc/common']
    dockerPullDeps = ['confluentinc/cp-base-new']
    usePackages = true
}
