@Library('dst-shared@master') _

dockerBuildPipeline {
        githubPushRepo = "Cray-HPE/hms-smd"
        repository = "cray"
        imagePrefix = "cray"
        app = "smd"
        name = "hms-smd"
        description = "Cray Hardware State Manager Service"
        dockerfile = "Dockerfile.smd"
        slackNotification = ["", "", false, false, true, true]
        product = "csm"
}
