@Library('my-shared-lib')_

def configmap = [
    project : 'expense',
    env : 'dev',
    component : 'backend',
    acc_id : '343430925817',
    region : 'us-east-1',
    label : 'agent-1-label'
    
]


if( ! env.BRANCH_NAME.equalsIgnoreCase('main')){ // true, if branch is feature branch
    nodeJSEKSPipeline(configmap)
}
else{
    echo "Follow the process of PROD release"
}


//  Fix It: Use colons (:) instead of equals (=)







