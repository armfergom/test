node {
    // Checkout whatever branch
    checkout scm 
    sh 'git config --get remote.origin.url > url'
    def url = readFile 'url'
    echo "${url}"
}
