@Library('jenkins_shared_library') _
def configMap = [
    PROJECT : 'roboshop',
    COMPONENT : 'payment'
]
/* if ( ! env.BRANCH_NAME.equalsIgnoreCase('main') ){
    pythonEKSpipeline(configMap)
}
else {
    echo 'Please Proceed with PROD Process'
} */

pythonEKSpipeline(configMap)