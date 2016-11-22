node {
    dir("${projectWorkspace}@script") {
        ansiblePlaybook(
            playbook: 'tests/jenkins.yml',
            credentialsId: 'bndabbs',
        )
    }
}
