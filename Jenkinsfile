stage 'TestMayaScript'
node {
	echo "Starting TestMayaScript"
}

stage 'PushToProd'
node {
	git url: "https://github.com/NathanBWaters/randomSpheres.git"
	echo "Starting PushToProd"
	sh 'printenv'
	sh 'env'
	sh 'echo $BRANCH_NAME' 
	sh 'echo $GIT_COMMIT'
}
