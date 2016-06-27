stage 'TestMayaScript'
node {
	echo "Starting TestMayaScript"
}

stage 'PushToProd'
node {
	echo "Starting PushToProd"
	sh echo $GIT_COMMIT
	sh echo $GIT_URL
	sh echo $GIT_AUTHOR_NAME
	sh echo $GIT_COMMITTER_NAME
	sh echo $GIT_AUTHOR_EMAIL
	sh echo $GIT_COMMITTER_EMAIL
}
