node {
    properties ([[$class: 'ParametersDefinitionProperty', parameterDefinitions: [[$class: 'BooleanParameterDefinition', defaultValue: false, description: 'If checked, a release is performed.', name: 'performRelease']]]])
    
    // Checkout whatever branch
    checkout scm
    
    stage "Build"
    echo "Building..."
    
    // Perform release if parameter says so
    if (performRelease) {
        stage "Build"
        echo "Building..."
    }
}