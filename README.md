php-jenkins-template
====================

jenkins模板

安装phploc
pear config-set auto_discover 1
pear install pear.phpunit.de/phploc

安装phpdepend
pear channel-discover pear.pdepend.org
pear install pdepend/PHP_Depend-beta

安装phpcs
pear install PHP_CodeSniffer

安装phpmd
pear channel-discover pear.phpmd.org
pear channel-discover pear.pdepend.org
pear install --alldeps phpmd/PHP_PMD

安装phpcpd
pear install pear.phpunit.de/phpcpd

安装phpdox
pear install -f pear.netpirates.net/phpDox-0.5.0

安装phpuint
pear install pear.phpunit.de/PHPUnit

安装phpcb
pear channel-discover pear.phpqatools.org
pear install --alldeps phpqatools/PHP_CodeBrowser

建立php-jenkins-template
cd $JENKINS_HOME/jobs
mkdir php-template
cd php-template
放入config.xml
chown -R www-data:www-data php-template/
