srpm:
	dnf -y install scl-utils-build
	spectool -g -R $(spec)/tomcat.spec
	rpmbuild -bs $(spec)/tomcat.spec --define 'scl sclt-tomcat70' --define '_rpmdir $(outdir)'
