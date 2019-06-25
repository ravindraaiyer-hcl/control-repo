forge 'https://forge.puppet.com'

# Modules from the Puppet Forge
# Versions should be updated to be the latest at the time you start
#mod 'puppetlabs/inifile',     '2.2.1'
#mod 'puppetlabs/stdlib',      '4.25.1'
#mod 'puppetlabs/concat',      '4.2.1'

# When adding a new module here, you must also ensure the corresponding mirror/repo is available.
# All modules will be directly sourced from the external repo.
# All custom modules will be sources from the private github repo of ravindraaiyer-hcl.

# Use the Puppetlabs official NTP Module
mod 'ntp',
  :git => 'git@github.com:puppetlabs/puppetlabs-ntp.git',
  :ref => '6.2.0'

mod 'node_encrypt',
  :git =>  'git@github.com:binford2k/binford2k-node_encrypt.git',
  :ref => 'v0.2.5'

mod 'puppetserver_gem',
  :git => 'git@github.com:puppetlabs/puppetlabs-puppetserver_gem.git',
  :ref => '0.2.0'

mod 'ssh',
  :git => 'git@github.com:ghoneycutt/puppet-module-ssh.git',
  :ref => 'v3.61.0'

mod 'puppetlabs/stdlib',
  :git => 'git@github.com:puppetlabs/puppetlabs-stdlib.git',
  :ref => '5.2.0'

mod 'puppetlabs/reboot',
  :git => 'git@github.com:puppetlabs/puppetlabs-reboot.git',
  :ref => '1.0.0'

mod 'thias/sysctl',
  :git => 'git@github.com:thias/puppet-sysctl.git',
  :ref => '1.0.6'

mod 'inifile',
  :git => 'git@github.com:puppetlabs/puppetlabs-inifile.git',
  :ref => '2.2.0'

mod 'puppetlabs/lvm',
  :git => 'git@github.com:puppetlabs/puppetlabs-lvm.git',
  :ref => '1.0.1'

mod 'selinux',
  :git => 'git@github.com:voxpupuli/puppet-selinux.git',
  :ref => 'v1.6.1'

mod 'dirtree',
  :git => 'git@github.com:puppetlabs/pltraining-dirtree.git',
  :ref => 'v0.3.0'

mod 'danieldreier/autosign', 
  :git =>  'git@github.com:danieldreier/autosign.git',
  :ref => 'v0.1.2'

mod 'puppetlabs/vcsrepo',
  :git => 'git@github.com:puppetlabs/puppetlabs-vcsrepo.git',
  :ref => '1.4.0'

mod 'puppetlabs/catalog_preview', 
  :git => 'git@github.com:puppetlabs/puppetlabs-catalog_preview.git',
  :ref => '2.2.0'

mod 'razorsedge/network',
  :git => 'git@github.com:razorsedge/puppet-network.git',
  :ref => '3.8.0'

mod 'leoarnold/cups',
  :git => 'git@github.com:leoarnold/puppet-cups.git',
  :ref => '1.2.2'

# Jenkins module support
# NOTICE: Pegged to commit because there are no recent tags, and last tag only supports Jenkinx 1.x
mod 'jenkins',
  :git => 'git@github.com:voxpupuli/puppet-jenkins.git',
  :ref => 'fc2e12f4185e7e68e649d5bcf35ecd3dc45efd03'

mod 'puppetlabs/java',
  :git => 'git@github.com:puppetlabs/puppetlabs-java.git',
  :ref => '1.6.0'

mod 'computology/packagecloud',
  :git => 'git@github.com:computology/computology-packagecloud.git',
  :ref => 'v0.3.1'

# This has been pinned to a commit because the maintainer
# didn't actually create a tag for the 1.2.2 release.
# TODO: Check for a tagged release
mod 'ktreese-jenkins_windows_agent',
  :git => 'git@github.com:ktreese/jenkins_windows_agent.git',
  :ref => '2273b719cbebad7ebf7a10d57b688e6e16a3de4e'

mod 'lwf-remote_file',
  :git => 'git@github.com:lwf/puppet-remote_file.git',
  :ref => 'v1.1.3'

mod 'counsyl-windows',
  :git => 'git@github.com:counsyl/puppet-windows.git',
  :ref => '1.0.6'

mod 'counsyl-sys',
  :git => 'git@github.com:counsyl/puppet-sys.git',
  :ref => '0.9.20'

mod 'puppetlabs-registry',
  :git => 'git@github.com:puppetlabs/puppetlabs-registry.git',
  :ref => '1.1.4'

mod 'ktreese-nssm',
  :git => 'git@github.com:ktreese/nssm.git',
  :ref => '1.1.0'

mod 'puppetlabs/apt',
  :git => 'git@github.com:puppetlabs/puppetlabs-apt.git',
  :ref => '2.2.2'

# TODO: Check for a tagged release
mod 'darin/zypprepo',
  :git => 'git@github.com:voxpupuli/puppet-zypprepo.git', 
  :ref => '64eb804e7da4bd22e153d6674caa4815daf20c41'

# TODO: Determine whether nanliu/staging needs to be retire in favor of puppet/archive
mod 'nanliu/staging',
  :git => 'git@github.com:nanliu/puppet-staging.git',
  :ref => '1.0.3'

mod 'puppet/archive',
  :git => 'git@github.com:voxpupuli/puppet-archive.git', 
  :ref => 'v1.1.1'

mod 'saz/sudo', 
  :git => 'git@github.com:saz/puppet-sudo.git',
  :ref => 'v4.1.0'

mod 'biemond/jdk7',
  :git => 'git@github.com:biemond/biemond-jdk7.git',
  :ref => 'v0.5.4'

# Rbenv
mod 'jdowning/rbenv',
  :git => 'git@github.com:jdowning/puppet-rbenv.git',
  :ref => '2.4.0'

# used for centrify rpm gpg key
mod 'gpg_key',
  :git => 'git@github.com:treydock/puppet-gpg_key.git', 
  :ref => '0.0.4'

# downloads a file to local server
# This Wget module is deprecated - Ravindra
mod 'wget',
  :git => 'git@github.com:voxpupuli/puppet-wget.git',
  :ref => 'v2.0.1'

# allows file download in the context of maven protocol, depends on wget
mod 'maestrodev/maven',
  :git => 'git@github.com:maestrodev/puppet-maven.git',
  :ref => 'v1.4.0'

mod 'sudoers',
  :git => 'git@github.com:NTTCom-MS/eyp-sudoers.git',
  :ref => 'master'

mod 'limits',
  :git => 'git@github.com:puppetlabs/puppetlabs-limits.git',
  :ref => '0.1.0'

# oracle database server module
mod 'oradb',
  :git => 'git@github.com:biemond/biemond-oradb.git',
  :ref => 'v3.0.17'

# dependency for many things
mod 'concat',
  :git => 'git@github.com:puppetlabs/puppetlabs-concat.git',
  :ref => '2.2.1'

# App Dynamcis MVP
mod 'java_ks',
  :git => 'git@github.com:puppetlabs/puppetlabs-java_ks.git',
  :ref => '1.6.0'

mod 'chocolatey',
  :git => 'git@github.com:puppetlabs/puppetlabs-chocolatey.git',
  :ref => '3.0.0'

mod 'powershell',
  :git => 'git@github.com:puppetlabs/puppetlabs-powershell.git',
  :ref => '2.1.2'

mod 'windows_env',
  :git => 'git@github.com:voxpupuli/puppet-windows_env.git',
  :ref => 'v2.3.0'

# EOC Monitoring Dashboard
# A hash is being used because the repo does not have
# release tags. - Tony Thayer 20180112
# TODO: Check for a tagged release
mod 'consul',
  :git => 'git@github.com:solarkennedy/puppet-consul.git',
  :ref => 'v5.0.4'

mod 'systemd',
  :git => 'git@github.com:camptocamp/puppet-systemd.git',
  :ref => '1.1.1'

mod 'transition',
  :git => 'git@github.com:puppetlabs/puppetlabs-transition.git',
  :ref => '0.1.1'

mod 'terraform_enterprise',
  :git => 'git@github.com:inkblot/puppet-terraform.git',
  :ref => 'master'

mod 'ca_cert',
  :git => 'git@github.com:pcfens/puppet-ca_cert.git', 
  :ref => 'v2.1.0'

# There are some changes made to the puppetlabs enterprise module during the process of configuration of websphere
# to make the module work as expected (changes in Regex , syntax error in heredoc ) . going forward we are still working
# on module for the remaining configuration . once the websphere is fully configured we will raise a PR suggesting changes
# to the enterprise module.Once we get approvals we will rollback to mirrors.
mod 'puppetenterprise-websphere_application_server',
  :git => 'git@github.com:ravindraaiyer-hcl/puppetenterprise-websphere_application_server.git',
  :ref => 'master'

# This snmp module is deprecated
mod 'puppet-snmp',
  :git => 'git@github.com:voxpupuli/puppet-snmp.git',
  :ref => 'e1132ca63b7'

mod 'puppetlabs-exec',
  :git => 'git@github.com:puppetlabs/puppetlabs-exec.git', 
  :ref => '0.3.0'

# forked the repo  to fix user_home parameter since it is not populating during initial
# puppet run , future plan will be updating with forked pge puppet repo created by tony's changes.
mod 'puppetlabs-ibm_installation_manager',
  :git => 'git@github.com:ravindraaiyer-hcl/puppetlabs-ibm_installation_manager.git',
  :branch => 'master'

mod 'puppet-install_maximo_admin',
  :git => 'git@github.com:ravindraaiyer-hcl/puppet-install_maximo_admin.git',
  :branch => 'master'

mod 'augeasproviders_grub',
  :git => 'git@github.com:hercules-team/augeasproviders_grub.git',
  :ref => '3.0.1'

mod 'augeasproviders_core',
  :git => 'git@github.com:hercules-team/augeasproviders_core.git',
  :ref => '2.1.4'

mod 'puppetlabs-dism',
  :git => 'git@github.com:puppetlabs/puppetlabs-dism.git',
  :ref => '1.3.1'

mod 'puppet-install_was',
 :git => 'git@github.com:ravindraaiyer-hcl/puppet-install_was.git',
 :branch => 'master'

mod 'puppet-config_was_maximo',
 :git => 'git@github.com:ravindraaiyer-hcl/puppet-config_was_maximo.git',
 :branch => 'master'

mod 'puppet-posix_acl',
 :git => 'git@github.com:voxpupuli/puppet-posix_acl.git',
 :ref => 'v0.1.1'
