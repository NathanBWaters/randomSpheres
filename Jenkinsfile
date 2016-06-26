stage 'TestMayaScript'
node {
	echo "Starting TestMayaScript"
	sh 'make test'
}

stage 'PushToProd'
node {
	echo "Starting PushToProd"
	sh 'make push'
}
