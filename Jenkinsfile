node {
    // Checkout whatever branch
    checkout scm 
        sh 'git config --get remote.origin.url > url'
        def url = readFile 'url'
        if (!url.contains("verified-oss-ath")) {
            error "Checked out resource (${url}) is not verified-oss-ath"
        }
}
