stage 'TestMayaScript'
node {
	git url: "git@github.com:NathanBWaters/randomSpheres.git"
	sh 'make test'
}

stage 'PushToProd'
node {
	git url: "git@github.com:NathanBWaters/randomSpheres.git"
	sh 'make push'
}
