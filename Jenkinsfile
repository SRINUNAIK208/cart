@Library('jenkins-shared-libraries')_ 


def configMap = [
    project = "roboshop",
    component = "cart"
]
if(! env.BRANCH_NAME.equalsIgnoreCase('main')){
    nodeEkspipeline.call(configMap)

}
else {
    echo 'proced with prod deployment'
}
