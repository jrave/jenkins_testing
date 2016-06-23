node {
    stage 'hello'
    echo 'Hello from Pipeline'
    echo 'Another Hello'

    stage 'branch name'
    echo "Branch: ${env.BRANCH_NAME}"

    stage 'checkout'
    checkout scm
}
