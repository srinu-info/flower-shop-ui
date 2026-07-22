@Library('jenkins-shared-library') _

def configMap = [
    component: "frontend"
]

if (env.BRANCH_NAME == "development") {

    nodeSharedJenkins(configMap)

}
else if (env.BRANCH_NAME == "main") {

    nodeProdJenkins(configMap)

}
