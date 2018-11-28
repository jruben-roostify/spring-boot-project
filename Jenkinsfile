@Library('jenkins-shared-libraries') _
def config = [runTest:true,buildFilePath:"./build.gradle",sonarNeeded:true,dockerNeeded:true,imageName:"roostify/boot-test"]
gradlePipeline(config)
