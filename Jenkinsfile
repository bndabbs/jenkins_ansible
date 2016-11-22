node {
    dir("${projectworkspace}@script") {
        ansiblePlaybook(
            playbook: 'tests/jenkins.yml',
            credentialsId: 'bndabbs',
        )
    }
}
